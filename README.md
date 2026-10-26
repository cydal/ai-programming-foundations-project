# ai-programming-foundations-project

This project implements a reproducible data workflow that loads, cleans, and explores the Road Traffic Accident Severity dataset using Python, Pandas, Matplotlib, and Seaborn. It identifies when and under what conditions road accidents are more likely to occur and how severe their outcomes tend to be. The workflow includes two documented data-cleaning functions, an exploratory analysis function, and three labeled visualizations, all contained in a single Jupyter notebook.

**Dataset:** [Road Traffic Accident Severity (RTA) Dataset](https://www.kaggle.com/datasets/saurabhshahane/road-traffic-accidents) — 12,316 accident records across 32 driver, vehicle, road, and environmental fields.

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Running the notebook

```bash
source .venv/bin/activate
jupyter notebook data_workflow.ipynb
```

Run all cells from top to bottom to reproduce the cleaning, exploratory analysis, and visualizations.
