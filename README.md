# PROGRAMMING I - FINAL PROJECT
### Combining Python Fundamentals, Agent-Based Modeling, and Data Analytics
##### Nil Belluda Méndez: u213152
##### Tom Owen Prats: u213139
##### Armand Vidal Costa: u213212
## Real Estate Toolkit for Housing Market Analysis

### Overview
This repository contains the real_estate_toolkit, a Python package designed to analyze housing markets. The project leverages Python fundamentals, agent-based modeling, and modern data analysis libraries to provide insights into the housing market.

### Dataset
The project uses the Ames Housing Dataset, a rich dataset featuring detailed house pricing information, neighborhood characteristics, and utility details.

### Key Features
* Data Loading, Cleaning, and Analysis.
* Agent-Based Market Simulation.
* Machine Learning for Price Prediction.
* Learning Objectives
* Apply fundamental Python concepts in a real-world scenario.
* Design a well-structured Python project with clean code principles and type hints.
* Implement a basic Agent-Based Model to simulate the real estate market.
* Conduct comprehensive data analysis workflows.
* Utilize modern data analysis libraries (e.g., Polars, Plotly, Scikit-Learn).
* Develop machine learning pipelines for predictive modeling.
* Project Structure
* The repository is organized as follows:

### scss
##### ├── data/ (DataLoader, Cleaner, Descriptor)
##### ├── agent_based_model/ (Houses, Markets, Consumers, Simulations)
##### ├── analytics/ (EDA, Visualizations, Outputs)
##### ├── ml_models/ (Machine Learning Pipelines)
##### └── main.py (Orchestrates the toolkit)

### Components
* data/: Handles data loading, cleaning, and descriptive statistics.
* agent_based_model/: Simulates housing markets using classes for houses, consumers, and market dynamics.
* analytics/: Conducts exploratory data analysis (EDA) and generates visualizations.
* ml_models/: Builds predictive models using Scikit-Learn.

### Methodology
#### 1. Data Handling
* Load and validate the Ames Housing dataset.
* Clean the data (e.g., handle missing values, rename columns, standardize formats).
* Compute key descriptive statistics.
#### 2. Exploratory Data Analysis (EDA)
* Analyze price distributions.
* Compare neighborhood house prices with visualizations like boxplots.
* Examine feature correlations using heatmaps.
#### 3. Agent-Based Modeling
* Simulate a housing market with agents representing buyers and sellers.
* Model consumer behavior based on preferences like affordability and quality.
* Implement mechanisms for market clearing.
#### 4. Machine Learning
* Train predictive models to forecast house prices.
* Evaluate models using metrics like Mean Absolute Error (MAE) and R-squared (R²).
* Use the model for forecasting and analysis.

### Data Insights:
Interactive visualizations of price trends and neighborhood comparisons.
Statistical summaries to inform market trends.

### Market Simulations:
* Insights into consumer behavior and market dynamics.
* Evaluation of policies (e.g., affordability improvements).
* Predictive Analysis:

* Accurate house price forecasts using machine learning.
* Identification of key features driving housing prices.
