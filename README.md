# Titanic Dataset – Data Visualization Project

This project creates histograms, box plots, scatter plots, bar charts, and a correlation heatmap from the public Titanic passenger dataset.

## Files
- `Titanic_Data_Visualization.ipynb` – complete notebook with explanations and one-line takeaways.
- `requirements.txt` – required Python libraries.
- `charts/` – generated PNG charts (created after running the notebook).

## Run the notebook
1. Install Python and Jupyter, or upload the notebook to Google Colab.
2. Install dependencies: `pip install -r requirements.txt`
3. Open `Titanic_Data_Visualization.ipynb` and run all cells.
4. The notebook downloads the CSV from the public seaborn-data GitHub repository and saves seven PNG charts in `charts/`.

## Dataset source
Public Titanic dataset: https://github.com/mwaskom/seaborn-data/blob/master/titanic.csv

## Notes on honesty
The notebook computes chart values and takeaways from the dataset at run time. Missing age and fare values are disclosed. The scatter plot uses only rows with both original values present. Correlation is not interpreted as causation.
