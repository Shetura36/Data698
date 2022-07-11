# Data 698 Research Project

### Title
Comparative Study on Classifying Anomalous Card Transactions with Decision Trees, Random Forest, and SVM using Various Sampling Algorithms. 

### Abstract
This research utilized anonymized real card transaction dataset from a small business organization to study the performance of Decision Trees, Random Forest, and SVM classification models with various sampling algorithms. These sampling algorithms include undersampling, a combination of undersampling and oversampling, and synthetic oversampling techniques – RWO, SMOTE, MWMOTE, and ADASYN. In addition, the raw card transaction dataset was explored to understand data patterns related to anomalous behavior. The data was transformed to create metrics that could be utilized as features in the models. These features are then validated by the various models. Finally, a recommendation is made to the small business organization as to which models and sampling techniques should be investigated more for further future work.

### Saved Data Used to Generate Results Published in Paper

Below are the saved CSV files for the data used to generate the results published in the paper. 

- Training-Testing dataset: Paper Data/paper_train_test_20k.csv
- Training set: Paper Data/paper_train_20k.csv
- Testing set: Paper Data/paper_test_20k.csv
- Sampled training sets: 
- Paper Data/sampled training sets/undersampling_20k.csv
- Paper Data/sampled training sets/both_20k.csv
- Paper Data/sampled training sets/rwo_20k.csv
- Paper Data/sampled training sets/smote_20k.csv
- Paper Data/sampled training sets/mwmote_20k.csv
- Paper Data/sampled training sets/adasyn_20k.csv
- Results:Paper Data/Results_test_train_20k_A.csv

### R Markdown Files

Data 698 - Part 1 - Process Private Data
- Input files used by this file is not published in this repository for security reasons 

Data 698 - Part 2 - Data Exploration, Metrics, and Imputation
- Input file: Data/preprocessed_transactions_anonymized.csv
- Output file: Data/transformed_imputed.csv, Data/transformed_imputed_scaled.csv

Data 698 - Part 3 - Data Exploration and Feature Selection
- Input file: Data/transformed_imputed_scaled.csv
- Output file: Data/transactions_final.csv, Data/transactions_scaled_final.csv

Data 698 - Part 4 - Modeling
- Input file: Data/transactions_scaled_final.csv
- For results published in paper see above

S. Tinapunan, 7/11/2022
  

