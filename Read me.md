# READ ME - Fake News Detector - Iron Hack group 2
**Group members** : Ambrose, Guy, Aurele

## Description

**Project:** Build a Fake News Detector using NLP models

Input: Enter a news title

Output: Models categorize it as "Likely real" / "Likely fake"


Required to:

- Test & assess multiple combinations of: 
    - Data Cleaning
    - Natural Language Processing
    - Vectorization techniques
    - Modeling
- Analyze results on test set to try to come up with optimizations

## Repository content

- Notebooks
    - 'Final model-1.ipynb' ->  Notebook contanting the best performing model
    - 'result comparator.ipynb' -> Notebook comparing the results of the top accuracy model created by each group member to compare differences in predictions
    - 'Categorisation.ipynb' ->  Notebooks created to compare group members predictions VS. test data categorization

- CSVs
    - 'training_data_lowercase.csv' -> CSV used for model creations
    - 'testing_data_lowercase_nolabels.csv' -> CSV used by Iron Heck for evaluation
    - 'Predictions Fake News - Final Group 2.csv' -> CSV edited for model evaluation by Iron Hack

- Other:
    - 'SVM_App_files.zip' -> Deployed version of the model
    - G2 Fake news presentation.pdf -> Group presentations
    - Folder "Workfiles" contains notebooks by students with the models tested
    

## Technology used

- Python 3

Best model library requirements:
- matplotlib
- nltk
- pandas
- re (built-in Python library, no installation required)
- seaborn
- sklearn