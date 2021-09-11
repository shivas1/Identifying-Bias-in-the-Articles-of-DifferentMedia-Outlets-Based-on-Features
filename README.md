# Identifying-Bias-in-the-Articles-of-DifferentMedia-Outlets-Based-on-Features
The repository contains the data files and also the python files that are generated during the master thesis project at University of Passau
# Description of the attached Data files

Finale.csv: The data file contains the initial sentences with the opinions and annotations related to the dataset

dt_final_new_features.csv: This data file contains the final words and vectors for each word

seed_words.xslx: This data file contains the manually selected bias words

bias_word_lexicon_top1000_10times.xslx : This data file contains bias words for each random sample of batches 

# Bias_lexicon.ipynb 
In this python script we create a semi automated bias lexicon

files needed to run the script note: The initial four files are not attached can be downloaded through apis
1. GoogleNews-vectors-neagtive300.bin
2. wordsim353.tsv
3. men.tsv
4. question-words.txt
5. seed_words.xlsx 

# Features_engineering.ipynb

To run the script we need

Finale.csv data file is attached 

Dictionaries needed for ruuning the files are described in the script

# Features_analysis.ipynb

The run the script we need 

dt_final_new_features.csv attached

In this scipt we visualize the features by the word frequency present in the features

libraries require to run the file are described in the script

# Model_Fitting-copy1.ipynb 

To run this script we need 

dt_final_new_features file is attached

In this script we trail and error the models used in traditional machine learning 

We also try to use the xg_boost optimization and the evaluation of the model in this python script

We also use the visualization of bootstrap .632 in this python script

# features_selection.ipynb

To run this script we need 

dt_final_new_features file is attached

In this script we analyse the features on the tuned xg_boost model with including and without including some of the features
