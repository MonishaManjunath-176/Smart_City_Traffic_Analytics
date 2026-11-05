# Smart City Traffic Analytics and Congestion Prediction

## Data Processing Assignment

### Project Overview
Traffic congestion is a major challenge in urban areas. This project uses historical traffic and weather data to analyze traffic patterns and predict traffic volume using machine learning.

The project explores data preprocessing, exploratory data analysis, feature engineering, model development and performance evaluation.

### Dataset
**Metro Interstate Traffic Volume Dataset**

- Source: UCI Machine Learning Repository
- Dataset ID: 492
- Observations after duplicate removal: 48,187
- Target variable: `traffic_volume`
- Data includes traffic volume, weather conditions, holiday information and timestamps.

Dataset: https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume

### Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

### Project Workflow
1. Dataset loading and exploration
2. Data quality assessment
3. Missing-value handling and anomaly treatment
4. Exploratory data analysis and visualization
5. Feature engineering
6. Categorical encoding and preprocessing
7. Chronological train-test split
8. Random Forest Regression
9. Model evaluation and error analysis

### Model Performance

The Random Forest model achieved the following results on the test dataset:

| Metric | Result |
|---|---:|
| MAE | 283.16 |
| RMSE | 489.40 |
| R² Score | 0.9381 |

A Dummy Regressor was also implemented as a baseline for comparison.

### Repository Contents
- `Smart_City_Traffic_Analytics_final.ipynb` – Complete project notebook containing implementation, visualizations and evaluation.

### Limitations
The dataset represents traffic observations from a single monitoring station on westbound I-94 in the Minneapolis–St Paul area. Therefore, the findings should not be interpreted as representing an entire city's road network.

### Author
Monisha Manjunath

B.Tech – Mathematics and Computing  
M S Ramaiah University of Applied Sciences
