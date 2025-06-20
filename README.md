# DataScience_Assignment_2
This is the second Data Science Assignment were the task was to create a Spam Filter with a Supervised Machine Learning Algorithm.

For that we should take a dataset from the SpamAssassin Website, which is a collection of emails that are labeled as spam or ham. The dataset can be found at the following link: 
[Apache Spam Assassin](https://spamassassin.apache.org/old/publiccorpus/)

All the steps taken are documented in the ipynb file, which includes data preprocessing, feature extraction, model training, and evaluation.

To run the code, just create a `.venv` and install the requirements from the `requirements.txt` file or uncomment the lines from the first cell of the notebook.

On Linux or MacOS use:
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

On Windows use:
```bash
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
```
Also make sure to properly download the dataset and place it in the same directory as described in the notebook.