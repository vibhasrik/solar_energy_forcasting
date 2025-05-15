# Forecasting Renewable Energy Generation using Climate and Weather Data

## Project Overview
This project explores the potential of using historical and forecasted weather data to predict renewable energy generation, with a focus on **solar power**. By analyzing:
- Historical climate norms,
- Real-time weather forecasts,
- Actual solar energy output data,

we aim to uncover patterns and relationships that help forecast solar energy production. Ultimately, this can support **sustainable energy planning and usage**.

---

## Datasets Used

### 1. US Solar Energy Output
- **Source**: [USGS](https://energy.usgs.gov/uspvdb/)
- **Description**: Annual production records for large-scale solar energy facilities in the U.S. from 1985–2023.
- **Use**: Baseline data for comparing with historical and forecasted weather conditions.

### 2. NOAA Climate Normals
- **Source**: [NOAA NCEI](https://www.ncei.noaa.gov/cdo-web/datasets)
- **Description**: Long-term climate averages (temperature, precipitation, etc.) used for identifying trends.
- **Use**: Historical climate context for solar output.

### 3. ECMWF Forecast Data
- **Source**: [ECMWF](https://data.ecmwf.int/forecasts/)
- **Description**: 6-hourly global forecasts including temperature, pressure, wind, and solar radiation.
- **Use**: Predictive input for modeling future solar output.

---

## Data Quality Highlights

- **Credibility**: All datasets come from reputable government or research organizations.
- **Timeliness**: ECMWF updates every 6 hours; NOAA data is updated daily; USGS updates annually.
- **Completeness**: Most datasets are complete with some minor missing values (e.g., tilt angles).
- **Accuracy**: All sources follow validation protocols with consistent units and formats.
- **Limitations**:
  - USGS focuses only on large-scale facilities.
  - ECMWF’s GRIB file format requires preprocessing.
  - NOAA has occasional gaps due to station outages.

---

## Project Goals
- Analyze the relationship between climate data and solar power generation.
- Evaluate forecasting methods for predicting energy output.
- Identify environmental factors most strongly correlated with energy production.
- Demonstrate how open data can inform smarter energy infrastructure decisions.

---

## File Structure
project-root/
│
├── data/ # Raw and cleaned datasets
├── notebooks/ # Jupyter notebooks for analysis and modeling
├── scripts/ # Scripts for data preprocessing and visualization
├── results/ # Outputs, charts, and findings
└── README.md # This file


---

## How to Run

1. Clone the repository:
``` bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
```
2. (Optional) Set up a virtual environment:
``` bash
   python -m venv env
   source env/bin/activate  # or env\Scripts\activate on Windows
```
3. Run analysis notebooks or scripts from the notebooks/ or scripts/ directory.

## Contact
If you have any questions or would like to collaborate, feel free to reach out via GitHub or email.

## License
This project is for educational purposes. Please credit the original datasets and contributors if reused.
