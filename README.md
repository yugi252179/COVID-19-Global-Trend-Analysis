

# COVID-19 Global Trend Analysis

This project analyzes the global trends of COVID-19 cases, deaths, and recoveries over time using Python. It provides insights into the spread and impact of the virus across countries and regions.

## 📊 Project Overview

The main objectives of this project are:

* Analyze COVID-19 confirmed, death, and recovered cases over time.
* Visualize global trends using plots and charts.
* Understand the progression of COVID-19 across different countries and WHO regions.

The dataset includes daily reported cases globally from January 22, 2020, to July 27, 2020.

---

## 🗂 Dataset Description

The dataset used contains the following columns:

| Column Name    | Description                                     |
| -------------- | ----------------------------------------------- |
| Province/State | Name of the province or state (if applicable)   |
| Country/Region | Name of the country/region                      |
| Lat            | Latitude of the location                        |
| Long           | Longitude of the location                       |
| Date           | Date of reporting                               |
| Confirmed      | Number of confirmed COVID-19 cases              |
| Deaths         | Number of deaths                                |
| Recovered      | Number of recovered cases                       |
| Active         | Active cases (Confirmed - Deaths - Recovered)   |
| WHO Region     | WHO regional classification                     |
| date_number    | Date in `YYYY-MM-DD` format (used for plotting) |

---

## 🧰 Tools & Libraries

This project uses the following Python libraries:

* `pandas` – for data manipulation and analysis
* `matplotlib` – for data visualization
* `numpy` – for numerical operations
* `seaborn` – for enhanced visualizations (optional)

---

## 📈 Visualizations

An example plot generated from the analysis:

![Global COVID-19 Trend](be56d97f-ae6b-47b5-bf2a-b1206abe03e8.png)

**Figure:** Global trend of COVID-19 cases showing Confirmed, Deaths, and Recovered cases over time.

---

## 🔧 Key Features

1. **Trend Analysis**
   Track the growth of confirmed, death, and recovered cases over time globally.

2. **Country-wise Summary**
   Analyze COVID-19 impact at the country level.

3. **WHO Region Analysis**
   Compare the pandemic spread across WHO regions.

---

## 💻 How to Run

1. Clone the repository:

   ```bash
   git clone <your-repo-url>
   ```
2. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn numpy
   ```
3. Run the analysis:

   ```bash
   python covid_analysis.py
   ```
4. Visualizations will be generated and saved in the project directory.

---

## ⚡ Conclusion

This project provides insights into the global progression of COVID-19 and highlights patterns in confirmed, recovered, and death cases over time. It can serve as a foundation for further predictive modeling and country-specific analysis.

---




