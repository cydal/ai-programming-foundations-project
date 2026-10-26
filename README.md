# ai-programming-foundations-project

A reproducible data workflow that loads, cleans, explores, and visualizes the Road Traffic Accident Severity dataset to surface patterns in when and under what conditions road accidents occur.

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
