Abstract- This study investigates oxidative stress in children exposed to cell phone and cell tower radiation by developing a predictive model for Superoxide Dismutase (SOD) activity by analyzing key parameter radiation exposure levels and fibrinogen concentration to predict SOD activity.A neural network model and decision tree regression algorithms is used. A neural network model with polynomial feature transformation was implemented to capture non-linear relationships between exposure and oxidative stress markers. The model achieved accuracy of 85%.

Model performence
| Metric                     | Value  |
|----------------------------|--------|
| Mean Absolute Error (MAE)  | 0.7863 |
| Mean Squared Error (MSE)   | 0.8273 |
| Root Mean Squared Error    | 0.9096 |

Classification Report
| Class        | Precision | Recall | F1 Score | Support |
|--------------|-----------|--------|----------|---------|
| Not exposed  | 1.00      | 0.82   | 0.90     | 11      |
| Exposed      | 0.50      | 1.00   | 0.67     | 2       |
| **Accuracy** |           |        | **0.85** | 13      |
| Macro Avg    | 0.75      | 0.91   | 0.78     | 13      |
| Weighted Avg | 0.92      | 0.85   | 0.86     | 13      |

Correlation Heatmap
![Screenshot 2025-05-24 124437](https://github.com/user-attachments/assets/6139133e-583d-45bd-9927-de5f2a7be584)


Index Terms- Neural Network Model,Decision Tree Regression ,Superoxide Dismutase(SOD), Fibrinogen Concentration, Oxidative Sress.
