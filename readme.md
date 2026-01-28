# Pump & Valve Predictive Maintenance

This repository demonstrates a machine learning approach to **Predictive Maintenance (PdM)** for industrial pumps and valves. By leveraging sensor data, the project aims to predict equipment failures before they occur, helping to reduce unplanned downtime and maintenance costs in industrial operations.

## 📌 Project Overview

In industries like Oil & Gas, pump failure can lead to significant production losses. This project uses historical sensor readings to train a classification model that identifies the state of the equipment (Normal vs. Failure/Warning).

### Key Objectives:

* **Failure Prediction:** Classify equipment status based on real-time sensor inputs.
* **Feature Importance:** Identify which sensors (pressure, temperature, vibration) are the strongest indicators of imminent failure.
* **Optimization:** Provide actionable insights for maintenance scheduling.

## 📂 Repository Structure

* `pump_data.csv`: Dataset containing sensor readings and corresponding equipment status labels.
* `Predictive_Maintenance_Pumps_Valves.ipynb`: The main Jupyter Notebook containing data preprocessing, exploratory analysis, model training, and evaluation.
* `readme.md`: Project documentation.

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Data Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (Random Forest, XGBoost, etc.)
* **Visualization:** Matplotlib, Seaborn

## 🚀 Workflow

1. **Data Preprocessing:** * Handling missing values and sensor noise.
* Feature scaling and encoding of categorical status labels.


2. **Exploratory Data Analysis (EDA):**
* Correlation heatmaps to see relationships between sensors.
* Time-series plots of sensor data leading up to failure events.


3. **Modeling:**
* Training a **Random Forest Classifier** to handle non-linear sensor relationships.
* Evaluating performance using Precision, Recall, and F1-Score (crucial for imbalanced failure data).


4. **Insights:**
* Generating a Feature Importance plot to show which parameters (e.g., "Discharge Pressure" or "Motor Vibration") contribute most to failure prediction.



## 📊 Business Impact

* **Reduced Downtime:** Shift from reactive "fix-it-when-broken" to proactive maintenance.
* **Cost Savings:** Minimize emergency repair costs and extend the lifespan of expensive machinery.
* **Safety:** Prevent catastrophic failures that could lead to environmental or safety hazards.

## 📈 Getting Started

1. Clone this repository:
```bash
git clone https://github.com/anmolshukla13/Pump-Predictive-Maintenance-.git

```


2. Install dependencies:
```bash
pip install pandas scikit-learn matplotlib seaborn

```


3. Open the notebook:
```bash
jupyter notebook Predictive_Maintenance_Pumps_Valves.ipynb

```



---

**Author:** [Anmol Shukla](https://www.google.com/search?q=https://github.com/anmolshukla13)
