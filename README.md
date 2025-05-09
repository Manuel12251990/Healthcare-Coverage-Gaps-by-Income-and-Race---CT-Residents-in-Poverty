# Healthcare-Coverage-Gaps-by-Income-and-Race---CT-Residents-in-Poverty

This project visualizes disparities in healthcare insurance coverage across income levels and racial groups in Connecticut from 2013 to 2021, using synthetic data.

https://public.tableau.com/app/profile/manuel.lizardo/viz/HealthcareInequityinCT/HealthcareInequityinCT

## Objective 
To highlight how race and income influence healthcare access, with an interactive Tableau dashboard featuring KPIs, maps, and year-over-year trends.

## Tools Used
- SQL Server (data preprocessing)
- Excel (cleaning, structuring)
- Tableau (dashboard and geospatial mapping)

## Features 
- Uninsured rate by race, age group, income level, and county
- Geospatial drill-downs to city leel
- Socioeconomic barrier heatmap
- Trend analysis (2013-2021, excluding 2020)

## File Structure
- `data/`: synthetic dataset
- `sql/` : query to generate master dataset
- `visuals/`: dashboard screenshots
- `README.md`: project documentation

## Limitations
- Synthetic data used to protect privacy
- No clinical outcomes included (ER visits, chronic illness)

## Next Steps
- Integrate Medicate claims and real-world data securely
- Add zipcode level forecasts for uninsured risks

## License
This project is for educational and portfolio purposes only.
