# How to Load the Dataset

This project includes zipped CSV files under the `dataset/` folder. Follow these steps to unzip and load the data:

## Step 1: Unzip the files

```python
import os
import zipfile

dataset_dir = "dataset"
unzipped_dir = "dataset/unzipped"
os.makedirs(unzipped_dir, exist_ok=True)

zip_files = [
    "train.csv.zip",
    "test.csv.zip",
    "test_labels.csv.zip",
    "sample_submission.csv.zip"
]

for file in zip_files:
    with zipfile.ZipFile(os.path.join(dataset_dir, file), 'r') as zip_ref:
        zip_ref.extractall(unzipped_dir)
```

## Step 2: Load the data
```
import pandas as pd

train_df = pd.read_csv("dataset/unzipped/train.csv")
test_df = pd.read_csv("dataset/unzipped/test.csv")
test_labels_df = pd.read_csv("dataset/unzipped/test_labels.csv")
sample_submission_df = pd.read_csv("dataset/unzipped/sample_submission.csv")
```
