# North Carolina Public Defender Analysis  

This project analyzes public defender case data in North Carolina for 2023-24. Using data visualization, it highlights case distribution, case length, and trends in public defense.  

## Overview  

Public defenders play a crucial role in the justice system, but managing caseloads efficiently can be challenging. This analysis aims to provide insights into how cases are handled, helping stakeholders identify inefficiencies and improve resource allocation. The project leverages data from the [North Carolina Court System](https://www.nccourts.gov/documents/publications/public-defender-case-disposition-activity-report) and presents findings in an interactive Tableau dashboard.  

## Data Sources  

- **[Public Defender Case Disposition Activity Report](https://www.nccourts.gov/documents/publications/public-defender-case-disposition-activity-report)** – Official case data from the North Carolina Court System.  
- **Case Age by Attorney** – Tracks how long cases remain open per attorney.  
- **Cases by Attorney** – Shows the number of cases handled per attorney.  
 

## Tableau Dashboard  

The dashboard visualizes key insights, including case distribution, attorney workloads, and case trends.  
[View the dashboard here](https://public.tableau.com/views/NorthCarolinaPublicDefenderAnalysis2023-24/Dashboard1)  

## Repository Contents  

- `public_defender_analysis.twb` – Tableau workbook with data visualizations  
- `public_defender_data.csv` – Primary dataset  
- `case_age_by_attorney.csv` – Case duration per attorney  
- `cases_by_attorney.csv` – Case volume per attorney  
- `cases_over_time.csv` – Case trends over time  
- `queries.sql` – SQL queries for data processing  

## Getting Started  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/tanneragle/North-Carolina-Public-Defender-Analysis.git
   ```
2. **Open in Tableau** – Load `public_defender_analysis.twb` to explore visualizations.  
3. **Review the Data** – CSV files are available for further analysis.  

## Contributing  

Contributions are welcome! Fork the repo, make changes, and submit a pull request.  

## License  

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.  