# EV Population Analysis

## Project Overview
This project focuses on analyzing Electric Vehicle (EV) adoption trends using historical data. It employs Python libraries for data processing and visualization, and compares several machine learning regression models to predict the ratio of EVs to total vehicle population. The Decision Tree model proved to be the most effective, achieving the lowest Mean Squared Error (MSE).

## Key Features
- **Data Processing & Visualization**: Cleaned and visualized data using Pandas, Matplotlib, and Seaborn.
- **EV Adoption Trend Analysis**: Analyzed historical data to identify growth trends in EV adoption.
- **Model Comparison**: Compared various regression models (Decision Tree, Random Forest, Gradient Boosting, SVR, Neural Network, and KNN) to predict EV-to-total vehicle ratios.
- **Best Model Performance**: The Decision Tree model achieved the lowest MSE, making it the most effective in predicting future EV adoption patterns.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning Algorithms**: 
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - Support Vector Regression (SVR)
  - Neural Network
  - K-Nearest Neighbors (KNN)

## Results
- EV adoption has seen substantial growth, with the highest growth rate observed in 2023.
- The **Decision Tree Regression** outperformed other models in terms of predicting EV adoption trends based on the Mean Squared Error (MSE).
  
## Visualizations
- **EV-to-total vehicle ratio trends**: A time series visualization showing how EV adoption has evolved over the years.
- **Correlation heatmap**: Displays relationships between EV-related variables.
- **Model performance comparison**: A plot comparing MSE across all tested models.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/ev-population-analysis.git
    ```
2. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the analysis:
    ```bash
    python EV_population_analysis.py
    ```

## Future Improvements
- Incorporating additional datasets (e.g., government policies, fuel prices) to improve prediction accuracy.
- Refining the models with hyperparameter tuning to enhance their performance.

## License
This project is open-source and available under the MIT License.

