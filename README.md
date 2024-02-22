
# Live Covid Dashboard For Berlin  


This project entails the development of a dynamic dashboard delivering daily updates on key COVID-19 metrics within Berlin districts. The dashboard will showcase the 7-day-incidence, representing the number of cases per 100,000 inhabitants, along with the rolling 7-day-average of new cases and the raw count of newly reported COVID-19 cases. Users will have the flexibility to select and compare specific districts. The data presented is sourced directly from the latest official figures provided by the Berlin government, accessible through berlin.de. This initiative aims to provide a comprehensive and user-friendly tool for monitoring and analyzing COVID-19 trends at the district level in Berlin.

## Deployment

To deploy this project run

Streamlit run BerlinDashboard.py 

run in terminal and make sure you are in the file path folder
```


## Roadmap

1. Dashboard Purpose:

Develop a Streamlit dashboard for daily COVID-19 updates in Berlin districts.
Data Source:

Retrieve the latest official COVID-19 data from the Berlin government via berlin.de.

2. Data Manipulation:

Organize data manipulation into a function.
Create a Total column for all Berlin districts.
Convert the 'Datum' column to a datetime format.
Define district lists and corresponding populations.

3. User Input (Sidebar):

Allow users to select and compare districts.
Include a slider for adjusting the number of days to display.
Add a checkbox for toggling between light and dark styles.

5. Data Visualization:

Plot the 7-day incidence for selected districts.
Plot the rolling 7-day average of new cases.
Plot the raw number of newly reported cases.

6. Code Organization:

Wrap code sections into functions for better structure.
Document functions for clarity and maintainability.

7. Documentation:

Include comments to describe the purpose of each code block.
Provide explanations for data manipulation steps and user input options.

## Authors

- [@siddharthiyervarma](https://github.com/siddharthiyervarma)


## Screenshots

[Alt Text](https://github.com/siddharthiyervarma/Live_Covid_Report_Berlin/blob/main/1.png)




