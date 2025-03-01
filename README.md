# 🏙️ NYPD Crime Data Analysis: Complaint and Arrest Insights 🚨

[![Python](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/seaborn-%234CB391.svg?style=for-the-badge&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/matplotlib-%23E35A2C.svg?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)

## 📋 Overview

This project explores crime patterns in New York City by conducting an in-depth analysis of NYPD complaint and arrest data. Through data exploration, cleaning, merging, and analysis, the project seeks to uncover insights into the most frequent crime complaints and arrests, demographic characteristics of individuals involved in crimes, and temporal variations in crime occurrences.

## 🎯 Project Goals

* Identify the most frequent crime complaints and arrests.
* Analyze the demographic characteristics of individuals involved in crimes.
* Investigate temporal variations in crime occurrences.
* Provide insights for law enforcement agencies, policymakers, and community stakeholders.

## 📂 Data Sources

* **NYPD Complaint Data:**
    * Historic data consisting of felony, misdemeanor, and violation crimes reported from 2006 to 2019.
    * Retrieved a random sample from the New York City Open Data API.
* **NYPD Arrest Data:**
    * Data consisting of every arrest made in NYC by the NYPD during the current year.
    * Manually extracted quarterly and reviewed by the Office of Management Analysis and Planning.
    * Data is in CSV format.

## 💻 Analysis Performed

* **Data Exploration:**
    * Explored the structure and initial data of both complaint and arrest datasets.
    * Identified common data points for merging.
* **Data Cleaning:**
    * Handled missing values using imputation techniques. 🧹
    * Converted time columns into datetime objects. ⏱️
    * Standardized column names to lowercase. ⚙️
* **Data Merging:**
    * Merged complaint and arrest datasets using common crime code columns (pd_cd and ky_cd). 🖇️
* **Analysis and Summaries:**
    1.  **Top 10 Most Frequent Crime Complaints:**
        * Identified and visualized the top 10 most frequent crime complaints. 📈
    2.  **Most Frequent Crime Arrests:**
        * Identified and visualized the top 10 most frequent crime arrests. 📊
    3.  **Demographic Analysis:**
        * Analyzed age and racial distribution in arrests and complaints. 👥
    4.  **Temporal Analysis:**
        * Examined arrests and complaints by day of the week. 📅

## 🔑 Key Findings

* Petit Larceny, Harassment, and Assault are the most frequently reported crimes. 🚨
* Dangerous Drugs, Assaults, and Theft-related offenses are the most frequent types of arrests. 🚔
* Individuals aged 25-44 are most frequently involved in both arrests and complaints. 👨‍👩‍👧‍👦
* Black, White, and Hispanic individuals appear most frequently in both arrests and complaints. 🤝
* Crime distribution is relatively uniform across weekdays, with a moderate peak in complaints on Fridays. 📈

## 📊 Visualizations

* Bar charts of top 10 crime complaints and arrests. 📊
* Histograms of age distribution in arrests and complaints. 📈
* Bar plots of racial distribution in arrests and complaints. 👥
* Count plots of arrests and complaints by day of the week. 📅

## 💡 Actionable Insights

* Targeted strategies for crime prevention focusing on prevalent crimes like Petit Larceny and drug-related offenses. 🎯
* Community engagement and resource allocation based on demographic and temporal analysis. 🤝
* Informed decision-making for law enforcement agencies and policymakers. 📝

## 🚀 Future Enhancements

* Incorporate additional datasets for a more comprehensive analysis. 📂
* Develop predictive models for crime forecasting. 🤖
* Create an interactive dashboard for real-time crime data visualization. 🖥️

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to suggest improvements or report bugs. 🐞
