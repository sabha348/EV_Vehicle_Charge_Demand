# EV Adoption Forecasting Tool

## Overview
Machine learning-based system to forecast electric vehicle adoption across counties using Washington State DOL registration data. Supports multi-year projections to help urban planners and utility providers anticipate future EV charging infrastructure needs.

## Problem Statement
As electric vehicle adoption accelerates, urban planners face the challenge of proactively developing adequate charging infrastructure. Without accurate forecasting: 
- Charging infrastructure bottlenecks may develop in high-adoption areas.
-  User satisfaction could decline due to charging limitations.
-  Resources might be misallocated to areas with lower actual demand.

## Features
- County-specific EV adoption forecasts  
- 36–60 month multi-year projections  
- Historical vs. forecast trend visualizations  
- Cumulative EV penetration tracking  
- Comparative analysis across counties  

## Technologies Used
- **Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Joblib, Matplotlib, Seaborn  
- **Tools**: Jupyter, Colab, Streamlit  
- **Models**: Random Forest, RandomizedSearchCV  

## Methodology
- **Data Preprocessing**: Clean dates, handle missing/outliers, convert types  
- **Feature Engineering**: Lag features, rolling stats, growth metrics  
- **Model Development**: Random Forest with hyperparameter tuning  
- **Multi-Step Forecasting**: Recursive 3–5 year predictions  
- **Visualization**: Actual vs. predicted plots, cumulative curves  

## Installation
Instructions for setting up the environment and dependencies.

## Usage
- Run the Streamlit web app  
- Use the model directly in Python scripts  

## Results
- **Santa Clara, Fairfax**: Accelerating adoption  
- **Orange County**: Rapid growth, possible plateau  
- **Honolulu**: Stable moderate growth  
- **Los Angeles**: Strong but slower momentum  

## Future Scope
- Add external predictors (economy, incentives, gas prices)  
- Forecast by vehicle type (BEV vs. PHEV)  
- Analyze grid load impacts  
- Build interactive scenario dashboard  
- Explore deep learning models  
- Study socioeconomic adoption drivers  

## Contributors
- Sahil Bhat

## License
MIT License – see `LICENSE` file

## Acknowledgments
- Washington State Department of Licensing  
- AICTE Internship Cycle 2 by S4F
