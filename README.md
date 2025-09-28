# Assignment 1 — Predictive Modelling of Eating-Out Problem

This project analyses a dataset of restaurants in Sydney (2018).  
It applies the full data science workflow: **Exploratory Data Analysis (EDA), Predictive Modelling (Regression & Classification), Geospatial Visualisation, and Reproducibility with Git, Git LFS, and DVC**.

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MuhammadAhmad-Flutter-Developer/DataScienceTechnologyAndSystem_Assignmnet1/tree/main
   cd assignment1-eatingout
2. **Create and activate a virtual environment (recommended)**
python -m venv .venv
# On Windows
.venv\Scripts\activate
# On macOS/Linux
source .venv/bin/activate
3. **Install dependencies**
pip install -r requirements.txt
▶️ How to Run
1. Run Jupyter Notebook

The full analysis is inside the notebook:

jupyter notebook git.ipynb

1. Reproduce Pipeline with DVC

If using DVC stages, you can reproduce the workflow with:

dvc repro

3. Run PySpark Models

PySpark regression and classification models are included in the notebook.
Make sure Java and Spark are installed before running those cells.

📊 Results to Expect

EDA

Missing values handled and summary statistics reported.

Distribution of cost, ratings, and restaurant types.

Top suburbs with the most restaurants.

Geospatial maps showing cuisine density across Sydney.

Interactive Plotly visualisation comparing costs of "Excellent" vs "Poor" rated restaurants.

Regression Models

Linear Regression and Gradient Descent compared using Mean Squared Error (MSE).

PySpark Linear Regression benchmarked for scalability.

Classification Models

Binary classification of ratings (Poor/Average vs Good+).

Logistic Regression, Random Forest, Gradient Boosted Trees, and SVM compared (F1, Precision, Recall).

PySpark Logistic Regression evaluated with class balancing.

Reproducibility

Git used for version control.

Git LFS tracks large files (datasets, visualisations, models).

DVC manages dataset and modelling pipeline for reproducibility.

👤 Author

Muhammad Ahmad
Master of Data Science, University of Canberra





