
# Project Success Analysis

This repository contains a synthetic dataset and analysis notebook demonstrating exploratory data analysis and predictive modelling for project outcomes. The project is designed to showcase data-analytic skills relevant to roles like business analyst, program manager, and data analyst.

## Dataset

* **synthetic_project_dataset.csv** — A synthetic dataset with 200 samples of hypothetical projects. Each row includes:
  * `Project_ID` — unique identifier for each project.
  * `Team_Size` — number of team members (5–20).
  * `Budget_kUSD` — project budget in thousands of US dollars (50–500).
  * `Duration_Months` — project duration in months (3–24).
  * `Complexity` — subjective complexity rating (1–5).
  * `Success` — binary indicator of project success (1) or failure (0).

The dataset is generated with simple relationships: higher budget, smaller team, lower complexity, and shorter duration tend to increase the probability of success.

## Notebook

The Jupyter notebook `project_analysis.ipynb` walks through:

1. Loading and inspecting the dataset.
2. Computing basic statistics and understanding the distribution of each feature.
3. Visualizing relationships between variables via histograms, scatterplots, and a correlation matrix.
4. Building two predictive models — logistic regression and random forest — to predict project success. The models are trained on 70% of the data and evaluated on the remaining 30% using classification metrics.

Run the notebook locally or in a cloud environment (e.g., JupyterLab, VS Code) using the provided `requirements.txt` file.

## Requirements

To set up the environment, install the following packages (listed in `requirements.txt`):

```
```

## Instructions

1. Clone this repository.
2. Create a virtual environment (optional but recommended).
3. Install dependencies with `pip install -r requirements.txt`.
4. Open `project_analysis.ipynb` in Jupyter Notebook or your preferred IDE and run the cells to reproduce the analysis.

This project is intentionally simple and self-contained so that it can be easily extended—for example, by experimenting with additional features, hyperparameter tuning, or different modelling approaches.
