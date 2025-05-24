# Toxic Comment Classification Using Machine Learning on Social Media Data

This project aims to classify toxic comments using natural language processing and machine learning techniques. It walks through data preprocessing, exploratory data analysis (EDA), model training, and evaluation to identify toxicity in online comments.

## Project Overview

Online platforms often struggle to moderate harmful or toxic comments. This project explores automated toxic comment classification using supervised learning models. The notebook provides:

- Text preprocessing (cleaning, tokenization, TF-IDF vectorization)
- Exploratory data analysis (EDA)
- Model training (Logistic Regression, Naive Bayes, etc.)
- Evaluation using accuracy, precision, recall, and F1-score

## Dataset

The dataset is sourced from the [Kaggle Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge). It contains comments labeled with six different categories:

- Toxic
- Severe toxic
- Obscene
- Threat
- Insult
- Identity hate

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- NLTK / re for text processing
- Jupyter Notebook

### Authors: Tam Tran, Viet Vi
### Report Contributors: Tam Tran, Viet Vi, Tram Tran, An Nguyen, Thu Nguyen

### Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Getting Started

### Running the Notebook

1. Clone the repository:
   ```
   https://github.com/itistamtran/Toxic_Comment_Classification.git
   ```

2. Launch the notebook:
   ```
   jupyter notebook Toxic_Comment_Classification.ipynb
   ```
3. Dataset Instructions
   
   The dataset is stored in zipped CSV format under the `dataset/` folder.  
   To unzip and load the data, follow the steps in [`load_dataset.md`](load_dataset.md).
   If you're running the notebook locally, **skip the Google Drive loading cell** and use the local dataset instructions instead.

### Prerequisites

Ensure you have Python 3.7+ installed. Then install dependencies:

```
pip install pandas numpy scikit-learn matplotlib seaborn nltk
```


