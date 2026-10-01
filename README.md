# Carbon Emission Analysis and Environmental Factors Using Python

## Project Overview
This project analyzes global sustainable-energy data to study CO₂ emission patterns and their relationship with energy and economic indicators.

## Objectives
- Clean and validate the dataset.
- Explore CO₂ emission trends across years and countries.
- Compare major emitting countries.
- Analyze relationships between CO₂ emissions and environmental/economic variables.
- Build a multiple linear regression model.
- Evaluate the model using MAE, RMSE, and R².
- Present findings through clear visualizations.

## Dataset
The project uses the uploaded Kaggle **Global Data on Sustainable Energy** dataset covering 2000–2020.

The dataset is included in `data/` for reproducibility. Please retain the original Kaggle attribution when publishing the repository.

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure
```text
carbon-emission-analysis-python/
├── data/
│   └── global_data_on_sustainable_energy.csv
├── images/
│   ├── global_co2_trend.png
│   ├── top_10_countries_co2.png
│   ├── india_co2_trend.png
│   ├── india_china_usa_co2.png
│   ├── correlation_heatmap.png
│   └── regression_actual_vs_predicted.png
├── notebooks/
│   └── carbon_emission_analysis.ipynb
├── .gitignore
├── requirements.txt
├── analysis_summary.json
└── README.md
```

## Analysis Workflow
1. Data loading
2. Data cleaning
3. Missing-value and duplicate checks
4. Exploratory data analysis
5. CO₂ trend analysis
6. Country comparison
7. Correlation analysis
8. Regression modeling
9. Model evaluation
10. Visualization and interpretation

## How to Run
```bash
git clone <your-repository-url>
cd carbon-emission-analysis-python

pip install -r requirements.txt
jupyter notebook
```

Open:
`notebooks/carbon_emission_analysis.ipynb`

## Model Evaluation
The notebook calculates:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The exact values are generated from the uploaded dataset and should be interpreted from the notebook output.

## Portfolio Skills Demonstrated
- Data cleaning
- Data validation
- Exploratory data analysis
- Data visualization
- Correlation analysis
- Regression modeling
- Model evaluation
- Python data analysis

## Author
**Trishala Phatangade**  
B.E. – Computer Science Engineering and Data Science
