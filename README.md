# Aviation Accidents Analysis README

## Overview
This README provides an overview of an analysis of aviation accident data. The analysis includes visualizations and insights derived from the dataset.

## Business Understanding

### Stakeholders and Key Business Questions
Stakeholders include aviation safety regulators, airline operators, and aviation safety researchers. Key business questions addressed by the analysis include:

1. What are the trends in aviation accidents over the years?
2. Which aircraft categories and regions are associated with the highest risk of accidents?
3. How severe are the injuries typically resulting from aviation accidents?

## Data Understanding and Analysis

### Source of Data
The data used for analysis is sourced from an aviation accident dataset. It includes information on accident dates, locations, aircraft details, injury severity, and other relevant factors.

### Description of Data
The dataset contains structured information including:

- Event ID
- Investigation Type
- Accident Number
- Event Date
- Location
- Country
- Latitude
- Longitude
- Airport Code
- Injury Severity
- Aircraft Damage
- Aircraft Category
- Registration Number
- Make and Model
- Number of Engines
- Engine Type
- Weather Conditions
- Phase of Flight
- Report Status
- Publication Date, etc.

### Three Visualizations
1. **Visualization 1: Number of Accidents per Year**
   - A line plot showing the trend in the number of aviation accidents per year.
   
2. **Visualization 2: Risk Assessment by Aircraft Category**
   - A bar plot depicting the risk scores calculated for different aircraft categories based on the severity of accidents.
   
3. **Visualization 3: Top 20 Risky Regions by Accident Frequency**
   - A bar plot illustrating the top 20 regions (countries) with the highest frequency of aviation accidents, ranked by their risk scores.

## Conclusion

### Summary of Conclusions
1. **Increasing Trend in Accidents**: The analysis reveals a fluctuating but generally increasing trend in aviation accidents over recent decades.
2. **High-Risk Aircraft Categories**: Certain aircraft categories such as small private planes show higher risk scores due to fatal accidents.
3. **Regional Risk Variability**: There is significant variability in aviation accident frequencies across different regions, with some regions consistently showing higher accident rates.

## How to Run the Project

### Prerequisites
Make sure you have the following installed:
- Python 3.12
- pip (Python package installer)

### Install Dependencies
1. Clone the repository or download the project files.
2. Navigate to the project directory.
3. Install the required Python packages using the following command:
   ```bash
   pip install -r requirements.txt

### Run the Jupyter Notebook
1. Start Jupyter Notebook from the project directory:
   ```bash
   jupyter notebook
2. Open the notebook file assignment.ipynb and run the cells to perform the analysis and generate the visualizations.
### Run the Dashboard
1. Navigate to the project directory.
2. Run the Python file for the dashboard:
   ```bash
   python aviation_dashboard.py
3. Open a web browser and go to http://127.0.0.1:8050/ to view the interactive dashboard.
### File Descriptions
- `requirements.txt`: Contains the list of Python packages required to run the project.
- `assignment.ipynb`: Jupyter notebook containing the data analysis and visualizations.
- `aviation_dashboard.py`: Python file to run the interactive dashboard using Dash.
### Example Commands
To install the requirements:
   ```bash
   pip install -r requirements.txt
   ```
To run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
To run the Dashboard:

   ```bash
   python aviation_dashboard.py
   ```