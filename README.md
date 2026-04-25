#  Household Electricity Consumption Predictor

##  Project Overview
This project leverages **Machine Learning** to predict household electricity consumption (kWh) based on environmental and lifestyle factors. Using a **Linear Regression** model, the project provides a data-driven approach to understanding energy demand.

---

##  Tech Stack
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
*   **Model:** Linear Regression
*   **Environment:** Google Colab

---

##  Features & Methodology
The model analyzes four primary drivers of electricity usage:
1.  **Residents:** Number of occupants.
2.  **Area (m2):** Total living space.
3.  **Appliances:** Number of electrical devices.
4.  **Temperature (°C):** External environmental temperature.

### Workflow:
*   **Data Cleaning:** Controlled dataset shape and handled features for optimal training.
*   **Modeling:** Split data (80% Train / 20% Test) and trained a Linear Regression model.
*   **Comprehensive Audit:** Evaluated the model using a multi-metric approach (MAE, MSE, RMSE, R²).

---

##  Final Evaluation Report
The model's performance was rigorously tested, yielding the following results:


| Metric | Value | Interpretation |
| :--- | :--- | :--- |
| **MAE** | **~114 kWh** | The average prediction error is approximately 114 kWh. |
| **MSE** | **~20,752** | Penalizes larger errors, indicating a stable performance. |
| **RMSE** | **~144 kWh** | On average, predictions deviate by about 144 kWh from actual values. |
| **R² Score** | **0.807 (80.7%)** | The model explains **80.7%** of the variance in consumption. |

### 📈 Statistical Summary:
An **R² Score of 80.7%** is considered a **strong performance** for a linear prediction model, demonstrating that the chosen features (Residents, Area, etc.) are highly effective indicators of energy demand.

---

## 📉 Visualizations
The repository includes several diagnostic plots:
*   **Actual vs. Predicted:** Comparison of real consumption vs. model estimates.
*   **Error Analysis:** Dedicated bar charts for MAE and MSE to audit prediction outliers.
*   **Goodness-of-Fit:** R² and RMSE scatter plots featuring the "Perfect Fit" line.


