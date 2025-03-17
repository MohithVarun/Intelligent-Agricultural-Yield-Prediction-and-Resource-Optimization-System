# Intelligent Agricultural Yield Prediction and Resource Optimization System

## Project Overview
This project is designed to help improve agricultural decision-making by predicting crop yields and optimizing resource allocation. By utilizing machine learning and time-series forecasting, it provides insights into farming conditions, minimizes resource waste, and helps farmers adapt to changing environmental factors.

## Features
- Predicts crop yield using machine learning models such as Random Forest and Neural Networks.
- Uses time-series forecasting to estimate future temperature and yield trends.
- Implements feature engineering techniques, including Growing Degree Days, Soil Moisture Index, and Pest Pressure.
- Detects anomalies using Isolation Forest, One-Class SVM, and Local Outlier Factor (LOF).
- Applies clustering and association rule mining to uncover patterns in farming practices.
- Includes data visualization techniques such as heatmaps, scatter plots, and trend graphs to present insights effectively.

## Dataset
The dataset used in this project consists of:
- **Year**: The recorded year of data collection.
- **hg/ha_yield**: Crop yield per hectare, which serves as the target variable.
- **average_rain_fall_mm_per_year**: Annual rainfall in millimeters.
- **pesticides_tonnes**: Amount of pesticides used, measured in tonnes.
- **avg_temp**: Average annual temperature in degrees Celsius.
- **Item**: Type of crop.

## Technologies Used
- **Programming Language**: Python
- **Libraries & Frameworks**:
  - `pandas`, `numpy` for data handling and processing.
  - `matplotlib`, `seaborn`, `plotly` for data visualization.
  - `scikit-learn`, `tensorflow` for machine learning models.
  - `statsmodels` for time-series forecasting.
  - `mlxtend` for association rule mining.

## Installation and Setup
### Step 1: Clone the Repository
```sh
 git clone https://github.com/your-username/agriculture-yield-prediction.git
 cd agriculture-yield-prediction
```

### Step 2: Install Dependencies
```sh
pip install -r requirements.txt
```

### Step 3: Run the Project
```sh
python final_project.py
```

## Project Workflow
1. **Data Preprocessing** – Cleans and standardizes data to ensure quality.
2. **Exploratory Data Analysis (EDA)** – Identifies trends, correlations, and patterns in the dataset.
3. **Feature Engineering** – Creates new variables to improve model accuracy.
4. **Time-Series Forecasting** – Predicts future yield and temperature trends.
5. **Machine Learning Models** – Uses regression and classification models for yield prediction.
6. **Anomaly Detection** – Identifies unexpected patterns or outliers in the data.
7. **Clustering & Data Mining** – Extracts insights about different farming conditions.

## Results and Insights
- Machine learning models were evaluated using RMSE and MAE, providing accurate yield predictions.
- Time-series forecasting helped in understanding seasonal variations in yield and climate.
- Anomaly detection methods identified irregularities that could indicate crop failures or extreme conditions.
- Clustering and association rule mining provided useful insights into farming conditions and their impact on yield.

## License
This project is licensed under the MIT License. You are free to modify and use it as needed.

## Contributing
Contributions are welcome. If you have suggestions for improvements, feel free to submit a pull request.

## Contact
For inquiries or collaboration opportunities, reach out via email at **mohithvarunr@gmail.com** or visit [GitHub]((https://github.com/MohithVarun)).
