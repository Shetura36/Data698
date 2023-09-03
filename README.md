# Data 698 Research Project

### Research Paper
[Comparative Study on Classifying Anomalous Card Transactions with Decision Trees, Random Forest, and SVM using Various Sampling Algorithms](https://github.com/Shetura36/Data698/blob/main/Data%20698%20Research%20Paper.pdf)

### Abstract
This research utilized anonymized real card transaction dataset from a small business organization to study the performance of Decision Trees, Random Forest, and SVM classification models with various sampling algorithms. These sampling algorithms include undersampling, a combination of undersampling and oversampling, and synthetic oversampling techniques – RWO, SMOTE, MWMOTE, and ADASYN. In addition, the raw card transaction dataset was explored to understand data patterns related to anomalous and normal behavior. The data was transformed to create metrics that could be utilized as features in the models. These features are then validated by the various models. Finally, a recommendation is made to the small business organization as to which models and sampling techniques should be investigated more for further future work.

### Data Used to Generate Results Published in Research Paper

Below are the saved CSV files for the data used to generate the results published in the paper. 

Training-Testing dataset: [Paper Data/paper_train_test_20k.csv](https://github.com/Shetura36/Data698/blob/main/Paper%20Data/paper_train_test_20k.csv)

Training set: [Paper Data/paper_train_20k.csv](https://github.com/Shetura36/Data698/blob/main/Paper%20Data/paper_train_20k.csv)

Testing set: [Paper Data/paper_test_20k.csv](https://github.com/Shetura36/Data698/blob/main/Paper%20Data/paper_test_20k.csv)

Sampled Training Sets: 
- [Paper Data/sampled training sets/undersampling_20k.csv](https://github.com/Shetura36/Data698/blob/main/Paper%20Data/sampled%20training%20sets/undersampling_20k.csv)
- [Paper Data/sampled training sets/both_20k.csv](https://github.com/Shetura36/Data698/blob/main/Paper%20Data/sampled%20training%20sets/both_20k.csv)
- [Paper Data/sampled training sets/rwo_20k.csv](https://github.com/Shetura36/Data698/blob/main/Paper%20Data/sampled%20training%20sets/rwo_20k.csv)
- [Paper Data/sampled training sets/smote_20k.csv](https://github.com/Shetura36/Data698/blob/main/Paper%20Data/sampled%20training%20sets/smote_20k.csv)
- [Paper Data/sampled training sets/mwmote_20k.csv](https://github.com/Shetura36/Data698/blob/main/Paper%20Data/sampled%20training%20sets/mwmote_20k.csv)
- [Paper Data/sampled training sets/adasyn_20k.csv](https://github.com/Shetura36/Data698/blob/main/Paper%20Data/sampled%20training%20sets/adasyn_20k.csv)

Results:
- [Paper Data/Results_test_train_20k_A.csv](https://github.com/Shetura36/Data698/blob/main/Paper%20Data/report%20of%20results/Results_test_train_20k_A.xlsx)

### Data Processing (R Markdown)

[Data 698 - Part 1 - Process Private Data](https://github.com/Shetura36/Data698/blob/main/Data%20698%20-%20Part%201%20-%20Process%20Private%20Data.Rmd)
- Input files used by this process file is not published in this repository for security reasons.

[Data 698 - Part 2 - Data Exploration, Metrics, and Imputation](https://github.com/Shetura36/Data698/blob/main/Data%20698%20-%20Part%202%20-%20Data%20Exploration%2C%20Metrics%2C%20and%20Imputation.Rmd)
- Input file: [Data/preprocessed_transactions_anonymized.csv](https://github.com/Shetura36/Data698/blob/main/Data/preprocessed_transactions_anonymized.csv)
- Output file: [Data/transformed_imputed.csv](https://github.com/Shetura36/Data698/blob/main/Data/transformed_imputed.csv), [Data/transformed_imputed_scaled.csv](https://github.com/Shetura36/Data698/blob/main/Data/transformed_imputed_scaled.csv)

[Data 698 - Part 3 - Data Exploration and Feature Selection](https://github.com/Shetura36/Data698/blob/main/Data%20698%20-%20Part%203%20-%20Data%20Exploration%20and%20Feature%20Selection.Rmd)
- Input file: [Data/transformed_imputed_scaled.csv](https://github.com/Shetura36/Data698/blob/main/Data/transformed_imputed_scaled.csv)
- Output file: [Data/transactions_final.csv](https://github.com/Shetura36/Data698/blob/main/Data/transactions_final.csv), [Data/transactions_scaled_final.csv](https://github.com/Shetura36/Data698/blob/main/Data/transactions_scaled_final.csv)

[Data 698 - Part 4 - Modeling](https://github.com/Shetura36/Data698/blob/main/Data%20698%20-%20Part%204%20-%20Modeling.Rmd)
- Input file: [Data/transactions_scaled_final.csv](https://github.com/Shetura36/Data698/blob/main/Data/transactions_scaled_final.csv)
- Results: [Published in paper]((https://github.com/Shetura36/Data698/blob/main/Data%20698%20Research%20Paper.pdf)


S. Tinapunan, 7/11/2022
  

