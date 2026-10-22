# Hotel Occupancy & Revenue Analysis

## Project Overview

This MATLAB project analyses hotel occupancy and revenue data to generate insights for hotel performance and revenue management. The analysis focuses on key hospitality metrics including Occupancy Rate, Average Daily Rate (ADR), Room Revenue, and RevPAR.

The project also examines demand patterns, compares weekday and weekend performance, identifies high-demand periods, and evaluates the relationship between occupancy and room rates.

## Objectives

- Analyse daily hotel occupancy and revenue performance.
- Calculate and evaluate key hotel performance indicators.
- Identify monthly and seasonal demand patterns.
- Compare weekday and weekend occupancy.
- Identify high-demand periods.
- Analyse the relationship between occupancy and ADR.
- Generate visualisations to support management decision-making.

## Key Performance Indicators

**Occupancy Rate**  
Measures the percentage of available rooms that are occupied.

**Average Daily Rate (ADR)**  
Measures the average revenue earned per occupied room.

**RevPAR**  
Measures room revenue generated per available room and combines occupancy and room-rate performance.

## Technologies Used

- MATLAB
- MATLAB Statistics and Data Analysis functions
- MATLAB Data Import and Visualisation
- CSV data processing

## Project Structure

```text
Hotel-Occupancy-Revenue-Analysis/
│
├── data/
│   └── hotel_occupancy_2025.csv
│
├── src/
│   └── hotel_occupancy_analysis.m
│
├── figures/
│   ├── daily_occupancy_trend.png
│   ├── monthly_occupancy_revpar.png
│   └── occupancy_vs_adr.png
│
├── results/
│   └── kpi_summary.csv
│
└── README.md
```

## Analysis Performed

The MATLAB script:

1. Imports and validates the hotel dataset.
2. Cleans and prepares the data.
3. Calculates hotel performance KPIs.
4. Performs monthly performance analysis.
5. Compares weekday and weekend occupancy.
6. Measures the correlation between occupancy and ADR.
7. Identifies high-demand dates.
8. Generates performance visualisations.
9. Exports a summary of the calculated KPIs.

## Key Insights

The analysis demonstrates how hotel operational data can be transformed into actionable information for revenue management. Occupancy, ADR, and RevPAR should be evaluated together when assessing hotel performance, while periods of unusually high demand can provide opportunities for strategic pricing adjustments.

## Dataset

The dataset is **synthetic** and was created for educational and portfolio purposes. It does not contain real guest information or personally identifiable data.

## How to Run

1. Open MATLAB.
2. Set the project folder as the MATLAB Current Folder.
3. Open `src/hotel_occupancy_analysis.m`.
4. Run the script.
5. Review the generated figures in the `figures` folder.
6. Review the KPI results in the `results` folder.

## Skills Demonstrated

This project demonstrates practical skills in:

- Data analysis
- Data cleaning and validation
- Statistical analysis
- KPI development
- Data visualisation
- Hospitality analytics
- Revenue management analysis
- Business-oriented interpretation of data

## Future Improvements

Future versions could extend the project by incorporating:

- Hotel demand forecasting
- Dynamic pricing models
- Machine learning for occupancy prediction
- Booking cancellation prediction
- Customer segmentation
- Interactive MATLAB dashboards

---

**Project:** Day 01 – Hotel Occupancy & Revenue Analysis  
**Tools:** MATLAB | Statistics | Data Analysis | Visualisation
