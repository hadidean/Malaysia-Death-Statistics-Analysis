<img width="794" height="1123" alt="Heatmap" src="https://github.com/user-attachments/assets/42450983-4aa7-4036-b261-dcf774973d8f" /># Malaysia Death Statistics Analysis (2001–2021)

An interactive Power BI dashboard analysing mortality statistics in Malaysia from 2001 to 2021. This project explores national death trends, geographical differences across states, and demographic patterns based on age groups and gender.

## Project Overview

The objective of this project is to analyse historical mortality data in Malaysia and communicate meaningful patterns through data analytics and interactive visualisation.

The dashboard provides three analytical perspectives:

1. **National Overview** – Examines overall deaths, annual mortality trends, age category distribution, and gender distribution.
2. **State Analysis** – Compares death counts across Malaysian states and examines annual mortality trends by state.
3. **Demographic Analysis** – Investigates mortality patterns across age groups, age categories, and gender.

## Tools and Technologies

- **R:** Data cleaning and preparation.
- **Microsoft Power BI:** Interactive dashboard development and data visualisation.
- **DAX:** Measures and calculations.
- **Power Query:** Data transformation and preparation.
- **CSV:** Dataset storage and exchange.

## Dataset

The dataset contains Malaysian death statistics from 2001 to 2021.

Main variables include:

| Variable | Description |
|---|---|
| YEAR | Year of recorded deaths |
| STATE | Malaysian state or federal territory |
| AGE GROUP | Specific age group |
| AGE CATEGORY | Broad demographic category |
| SEX | Male or female |
| NUMBER OF DEATH | Recorded number of deaths |

**Data source:** Department of Statistics Malaysia (DOSM).

Add the original dataset URL and any relevant attribution or usage conditions here.

## Project Workflow

1. Data collection
2. Data cleaning and preprocessing using R
3. Exploratory data analysis (EDA)
4. Data transformation using Power Query
5. DAX measure development
6. Interactive dashboard development using Power BI
7. Data validation and visualisation

## Visualization Preview

### 1. Line Graph (YEAR)

<img width="794" height="1123" alt="Line Graph" src="https://github.com/user-attachments/assets/b193ac5b-5d4c-4922-804b-285b6f03547c" />

### 2. Heatmap (STATE)

<img width="794" height="1123" alt="Heatmap" src="https://github.com/user-attachments/assets/51e7c737-f073-4816-b464-f05c17d10e54" />

### 3. Bar Chart (AGE)

<img width="794" height="1123" alt="Bar Chart" src="https://github.com/user-attachments/assets/98fb8884-33d7-4402-a2c2-9adb694a97db" />

### 1. Pie Chart (SEX)

<img width="794" height="1123" alt="Pie Chart" src="https://github.com/user-attachments/assets/089bac8e-65d7-432f-8407-163a8b5fa032" />

## Dashboard Preview

### 1. National Overview

Displays national mortality trends, total deaths, age category distribution, and gender distribution.

<img width="1063" height="591" alt="National Overview" src="https://github.com/user-attachments/assets/decb6190-598d-4c5d-8a1b-01dbf0192f40" />

### 2. State Analysis

Compares mortality across Malaysian states and examines yearly trends.

<img width="1062" height="596" alt="State Analysis" src="https://github.com/user-attachments/assets/7efd14e1-e125-4356-a120-137ab3deaaca" />

### 3. Demographic Analysis

Explores death distributions across age groups and gender, with interactive filters.

<img width="1058" height="592" alt="Demographic Analysis" src="https://github.com/user-attachments/assets/5b02418d-f9a5-4d11-9eb1-cd6da2314325" />

## Key Analytical Areas

- National mortality trends over time.
- Differences in death counts across states.
- Mortality distribution by age group.
- Male and female mortality comparisons.
- Changes in demographic mortality patterns.

## Repository Structure

- `data/` – Original and cleaned datasets.
- `scripts/` – R data cleaning scripts.
- `powerbi/` – Power BI dashboard file.
- `screenshots/` – Dashboard screenshots.
- `documentation/` – Project documentation and report.

## How to Use

1. Clone or download this repository.
2. Open the Power BI file in Microsoft Power BI Desktop.
3. If necessary, update the dataset source path.
4. Refresh the data.
5. Explore the three dashboard pages using the navigation buttons and interactive slicers.

## Disclaimer

This project is intended for educational and analytical purposes. The findings describe historical recorded death counts and should not be interpreted as individual mortality risk or causal relationships.

## Author

**Abdul Hadi Mahyudin**

Bachelor of Computer Science (Data Science)  
International Islamic University Malaysia (IIUM)
