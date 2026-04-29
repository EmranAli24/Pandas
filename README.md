# Pandas — Personal Learning Notes (Beginner-Friendly)

Beginner-friendly personal learning notes while practicing **pandas**.

This repo is mainly based on Kaggle Learn’s Pandas course (tutorial lessons):
https://www.kaggle.com/learn/pandas

> **Note:** I completed the tutorial lessons. **Kaggle course exercises are not included** in this repository.

## Contents (notebooks in repo root)
- `pandas.ipynb` — notes from **Kaggle Learn Pandas**.
- `Pandas DataFrame UltraQuick Tutorial.ipynb` — notebook studied from Google/Colab (ML Crash Course / eng-edu):
  https://colab.research.google.com/github/google/eng-edu/blob/main/ml/cc/exercises/pandas_dataframe_ultraquick_tutorial.ipynb

## Kaggle Learn — Topics Covered (lesson modules)
- Creating, Reading and Writing
- Indexing, Selecting & Assigning
- Summary Functions and Maps
- Grouping and Sorting
- Data Types and Missing Values
- Renaming and Combining

## Run locally (Jupyter)
```bash
git clone https://github.com/EmranAli24/Pandas.git
cd Pandas
pip install pandas numpy jupyter
jupyter notebook
```

## Datasets (Kaggle API)
Some examples use datasets hosted on Kaggle. To use those datasets locally:
1. Install/configure the Kaggle API: https://github.com/Kaggle/kaggle-api
2. Download a dataset:
```bash
kaggle datasets download -d <dataset-slug> -p data/ --unzip
```
3. Update file paths inside the notebook if needed.

## Open in Google Colab (optional)
1. Go to https://colab.research.google.com/
2. **File → Open notebook → GitHub**
3. Paste: `https://github.com/EmranAli24/Pandas`

## Credits
- Kaggle Learn Pandas: https://www.kaggle.com/learn/pandas
- Google Developers / Google LLC (eng-edu, ML Crash Course): UltraQuick tutorial notebook (contains Apache 2.0 license header)

## License
MIT License — see `LICENSE`.