# ENE_TO_END_CRICKET_DATA_ANALYTICS



This repository contains the code and resources for an end-to-end cricket data analytics project. The project focuses on selecting players for a T20 World Cup team using web scraping, Python, Pandas, and Power BI.

## Project Overview

The project aims to create an algorithm for selecting players based on specific criteria for a T20 World Cup team. The final team is designed to score 180 runs while defending 150 runs, with an emphasis on having specialist bowlers.


## Contents

- `web_scraping.ipynb`: Jupyter Notebook containing the web scraping code using Bright Data's proxy network to collect T20 World Cup data.
- `data_transformation.ipynb`: Jupyter Notebook demonstrating the transformation of JSON data to CSV format using Python Pandas.
- `power_bi_dashboard.pbix`: Power BI file containing the cricket dashboard with visualizations and player analysis.
- `README.md`: This file, providing an overview of the project and instructions.

## Credits

- Special thanks to [Code Basics] for sharing educational content on data science and programming.



##appoach



1. **Bright Data for T20 World Cup:**
   w  used Bright Data, a proxy network, to perform seamless web scraping. The web scraping process involves collecting match results, batting scorecards, and player-specific data. JavaScript code is employed to gather this information efficiently.

2. **Transforming JSON to CSV using Python pandas:**
   The collected data is in JSON format and needs to be transformed into CSV format for better presentation in Power BI. Python pandas, a powerful data manipulation library, is used to perform this transformation, as it provides robust tools for handling structured data.

3. **Connecting two tables using a match IDs dictionary:**
   demonstrates how to link two tables using a match IDs dictionary. They also showcase how to transform the dismissal column into an "out" or "not out" column using the `apply` method and a Lambda function.

4. **Performing data transformation on three files:**
   The project covers various data transformation steps, such as extracting relevant data from columns, removing duplicates, creating new columns based on date, and renaming columns. Additionally, a "balls" column is created from the "overs" column for statistical analysis.

5. **Data transformation, data modeling, and DAX measures:**
   The process of data transformation involves tasks like replacing null values, creating custom columns, and renaming columns. Data modeling is discussed, which includes establishing relationships between fact and dimension tables based on column names. DAX (Data Analysis Expressions) measures are introduced as essential for calculating and aggregating data to create visuals in Power BI.

6. **Building a cricket dashboard in Power BI:**
   The project showcases the construction of a cricket dashboard in Power BI. The presenter demonstrates how to filter and sort players based on criteria like batting average and strike rate. The dashboard is enhanced with various visual elements, connecting different pieces of information for insightful analysis.

7. **Learning Power BI for data-driven insights and creativity:**
   The presenter emphasizes the importance of developing skills in Google searching, which is vital for problem-solving and designing effective dashboards. 

8. **Final eleven selection and player analysis:**
   The final cricket team's composition is revealed, and a player analysis is conducted. Notably, Marcus Stoinis is chosen to replace Hardik Pandya for increased batting strength. The selection process is discussed, including considerations for the sixth position. 

9. **Final 11 cricket team and analysis exercise:**
   This project concludes with a discussion of the selected final 11 players in the cricket team. The decision to exclude Mitchell Starc due to his bowling performance is highlighted.

