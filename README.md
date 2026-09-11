# Ames House Price Prediction

Predict house sale prices in Ames, Iowa using the Kaggle House Prices dataset.

## Milestones

| No. | Title | Description |
| --- | --- | --- |
| 1 | Data Exploration and Cleaning | Load the dataset, perform exploratory analysis, handle missing values, and summarize data insights. |
| 2 | Feature Engineering and Selection | Create new features, transform variables, and select the most relevant features for modeling. |
| 3 | Model Building and Tuning | Implement and tune at least two regression models (e.g., Linear Regression, Random Forest) and compare their performance. |
| 4 | Evaluation and Submission | Generate predictions on the test set, evaluate results, and submit the final notebook and report. |

## How to run

```bash
py -m pip install -r requirements.txt
py -m jupyter notebook notebooks/ames_house_price_prediction.ipynb
```

## Milestone files

- [`milestones/01-data-exploration-and-cleaning.md`](milestones/01-data-exploration-and-cleaning.md)
- [`milestones/02-feature-engineering-and-selection.md`](milestones/02-feature-engineering-and-selection.md)
- [`milestones/03-model-building-and-tuning.md`](milestones/03-model-building-and-tuning.md)
- [`milestones/04-evaluation-and-submission.md`](milestones/04-evaluation-and-submission.md)

## Files

- `data/train.csv` — training set
- `data/test.csv` — test set
- `data/data_description.txt` — column descriptions
- `data/sample_submission.csv` — submission format
- `notebooks/ames_house_price_prediction.ipynb` — milestone notebook
- `REPORT.md` — short write-up
