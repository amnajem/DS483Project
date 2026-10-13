1. Dataset and class distribution The SMS Spam Collection contains [N_original] messages labelled ham or spam. We found [N_dup] exact duplicates and removed them before splitting to avoid leakage between training and test sets, leaving 5,169 unique messages. The data is imbalanced: 4,516 ham (87.37%) and 653 spam (12.63%). A classifier that always predicts ham would reach about 87% accuracy while detecting no spam, so later tasks use precision, recall and F1 for the spam class and a stratified split.How to run
Open DS483Project.ipynb in Google Colab or Jupyter Notebook.
Upload the dataset file (SMSSpamCollection or spam.csv) into a data/ folder.
Install dependencies if needed: pip install nltk seaborn scikit-learn pandas matplotlib
Run all cells from top to bottom.
