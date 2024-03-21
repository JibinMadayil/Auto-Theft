## README

This README file provides an overview of the data analysis performed on the Auto Theft Open Data dataset and the Python code used to conduct the analysis.

### Dataset Overview

The Auto Theft Open Data dataset contains information about auto theft incidents reported in a certain area. The dataset includes various fields such as the unique ID of each incident, the date and time of the report, the division where the offense occurred, the type of location, the premises type, and geographical coordinates.

### Code Overview

The Python code provided in this repository performed data cleaning, exploratory data analysis, and visualization on the Auto Theft Open Data dataset. Here's a brief overview of the code:

1. **Data Loading and Cleaning**: The code starts by loading the dataset into a Pandas DataFrame and performing initial data cleaning tasks such as dropping unnecessary columns, handling missing values, and converting data types.

2. **Exploratory Data Analysis (EDA)**: The code conducts exploratory data analysis to gain insights into the dataset. It includes:

   - Analysis of theft incidents by year, month, day of the week, and hour.
   - Visualization of the distribution of theft incidents by police division, location type, premises type, and neighborhood.

3. **Data Visualization**: The code uses Matplotlib and Seaborn libraries to create various plots and visualizations.

4. **Data Export**: The cleaned and processed dataset is exported to a CSV file named `clean.csv` for further analysis or integration with other tools.

### Analysis Outputs

1. **Incidents Reported by Year**: The number of theft incidents reported each year showed an increasing trend, with a significant rise observed from 2018 onwards.

2. **Incidents by Day of the Week**: Theft incidents were found to be most frequent on Thursdays, followed by Wednesdays and Tuesdays.

3. **Incidents by Month**: November had the highest theft incidents, followed by October and September.

4. **Incidents by Police Division**: Division D14 had the highest number of theft incidents, followed by D11 and D51.

5. **Top 10 Location Types with Incidents**: Most theft incidents occurred in "Outside" locations, followed by "House" and "Commercial" locations.

6. **Top 30 Neighborhoods with Incidents**: Palmerston-Little Italy, North Riverdale, and Dovercourt Village were among the neighborhoods with the highest theft incidents.

### Conclusion

The analysis and visualizations provided by the code aim to help stakeholders understand patterns and trends in auto theft incidents, identify high-risk areas, and inform decision-making for crime prevention and law enforcement efforts.
