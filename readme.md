# Travel Recommendation — Notebook Project

A Python/Jupyter project exploring travel recommendations using destination, review, user, and user-history data.

## Repository contents

| File | Role |
| --- | --- |
| `Travel recomm.ipynb` | Main exploratory notebook |
| `Expanded_Destinations.csv` | Destination information |
| `Final_Updated_Expanded_Reviews.csv` | Reviews |
| `Final_Updated_Expanded_UserHistory.csv` | User activity/history |
| `Final_Updated_Expanded_Users.csv` | User data |

## Run the notebook

1. Create a Python environment with Jupyter and the packages imported by the notebook.
2. Keep the CSV files with the notebook or adjust the input paths.
3. Open `Travel recomm.ipynb` and run the cells in order.

```bash
python -m pip install notebook pandas numpy scikit-learn
jupyter notebook
```

Additional dependencies may be required depending on the notebook cells.

## Purpose

This is an exploratory recommendation-system project for practicing dataset preparation and user/review-based recommendation techniques. It is not a deployed booking or recommendation API.

## Data considerations

The CSV files are sample project inputs. For real datasets, protect personal information and evaluate recommendations for quality and bias before production use.
