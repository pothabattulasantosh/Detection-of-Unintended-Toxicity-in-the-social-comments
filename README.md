# Detection of Unintended Toxicity in the social comments

## Description¶
The Conversation AI team, a research initiative founded by Jigsaw and Google (both part of Alphabet), builds technology to protect voices in conversation. A main area of focus is machine learning models that can identify toxicity in online conversations, where toxicity is defined as anything rude, disrespectful or otherwise likely to make someone leave a discussion.
Here’s the background: When the Conversation AI team first built toxicity models, they found that the models incorrectly learned to associate the names of frequently attacked identities with toxicity. Models predicted a high likelihood of toxicity for comments containing those identities (e.g. "gay"), even when those comments were not actually toxic (such as "I am a gay woman"). This happens because training data was pulled from available sources where unfortunately, certain identities are overwhelmingly referred to in offensive ways. Training a model from data with these imbalances risks simply mirroring those biases back to users

Please find more details of the problem at
Reference: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/overview/timeline

### Description of the files:
1. "Part1_EDA_FE.ipynb"-- this file contains all Exploratory Data Analysis and Feature Engineering
2. "part2_Applying_ML_algos.ipynb"--In this file some Machine Learing algorithms are appiled on preprocessed data 
3. "part_3_DL_algos.ipynb"-- In this file both Bidirectional LSTM/GRU are applied. 
