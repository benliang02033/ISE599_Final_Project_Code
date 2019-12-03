# ISE599_Final_Project_Code

# 1. Dataset

There are two dataset used in this project. However, both of them are too big to repo. Therefore, we will provide the data link here for you to download.

10K_Files: http://www.cs.cmu.edu/~ark/10K/
Kaggle_stock_prices: 


# 2. Data preprocessing

In the Data preprocessing folder, it includes the csv files, and code for our data prepartion.
a. cik_ticker.csv ---- include the correspondend stock symbol with their CIK
b. nasdaqlisted.txt --- include all of the CIK of companies listed in NASDAQ
c. otherlisted.txt --- include CIK of companies not in NASDAQ
d. CIK --- CIk of all 10K files 
e. finance digit --- experiement on extracting financial ratios in 10K files
f. Final_code_Mapping.ipynb --- code for merging CIK and Stock symbol
g. FInal_mapping_Previous.ipynb --- experiment on mapping using nasdaqlisted and otherlisted.
h. Final_Stop_words.ipynb --- code for creating stopword list.


# 3. Document Embedding Folder

In the Document_Embedding_model_build, it includes several models' code.
a. Document Embedding Parameter Tuning
b. Baseline Model -- Document Embedding
c. Baseline model -- Price feature
d. MSE plot of baseline modelse. Build All-feature Predictors
f. Parameter tuning of regression model

There are two csv files contains the MSE results of e. Build All-feature Predictors  and f.Parameter tuning of regression model


# 4. TF-IDF Folder 

The TF-IDF folder contains two sub-folder, TF-IDF_Baseline and TF-IDF_all_feature.
a.TF-IDF_Baseline contains the code for TF-IDF baseline model builder, After-preprocessing data, and stopword list.
b.TF-IDF_all_feature contains the code for TF-IDF all features model builder, After-preprocessing data, and stopword list.
