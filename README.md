readme_content = """
# Hurricane Intercept & Field Data Analysis

## Independent, Vehicle-based Observations & Analysis

This repository presents field observations and comprehensive analyses collected during vehicle-based intercepts of landfalling hurricanes during the 2024 Atlantic hurricane season. All data were recorded using a custom-built, truck-mounted weather station logging meteorological conditions at high resolution (1-minute intervals).

The primary focus of these analyses includes:
- Surface pressure and pressure tendencies at multiple temporal resolutions
- Sustained wind speeds and gust observations
- Rainfall rates and total accumulations
- Temperature and dewpoint trends

The observations captured are documented through detailed plots for each intercepted storm event, presented below chronologically with the most recent hurricane first.

---

## Hurricane Milton (October 9, 2024) – Sarasota, FL

**Minimum Recorded Pressure**: 961.4 mb (8:34 PM EDT)

### Available Plots:
- ![Multi-Panel Summary](images/Hurricane_Milton_MultiPanel.png)
- [Pressure Time Series](images/Hurricane_Milton_MSLP.png)
- Pressure Tendencies:
  - [5-minute](images/Hurricane_Milton_PTendency_5min.png)
  - [10-minute](images/Hurricane_Milton_PTendency_10min.png)
  - [15-minute](images/Hurricane_Milton_PTendency_15min.png)
  - [30-minute](images/Hurricane_Milton_PTendency_30min.png)
- [Wind Speed and Gusts](images/Hurricane_Milton_WindSpeed.png)
- [Temperature and Dewpoint](images/Hurricane_Milton_Temp_Dew.png)
- [Rain Rate and Accumulation](images/Hurricane_Milton_RainRate.png)

---

## Hurricane Helene (September 26, 2024) – Perry, FL

**Minimum Recorded Pressure**: 947.9 mb (11:33 PM EDT)

### Available Plots:
- ![Multi-Panel Summary](images/Hurricane_Helene_MultiPanel.png)
- [Pressure Time Series](images/Hurricane_Helene_MSLP.png)
- Pressure Tendencies:
  - [5-minute](images/Hurricane_Helene_PTendency_5min.png)
  - [10-minute](images/Hurricane_Helene_PTendency_10min.png)
  - [15-minute](images/Hurricane_Helene_PTendency_15min.png)
  - [30-minute](images/Hurricane_Helene_PTendency_30min.png)
  - [1-hour](images/Hurricane_Helene_PTendency_1hour.png)
- [Wind Speed and Gusts](images/Hurricane_Helene_WindSpeed.png)
- [Temperature and Dewpoint](images/Hurricane_Helene_Temp_Dew.png)
- [Rain Rate and Accumulation](images/Hurricane_Helene_RainRate.png)

---

## Methods

The observational platform comprises:
- A barometric pressure sensor
- Temperature and humidity sensors
- An anemometer mounted at an elevation for minimal wind interference
- A rain gauge capable of high-resolution precipitation measurements

All observations were logged continuously at 1-minute intervals. Data analyses and visualizations were performed using Python (pandas, numpy, matplotlib), generating comprehensive time-series analyses, pressure tendency calculations, and multi-parameter visualizations.

---

## Future Work

Planned expansions and improvements:
- Deployment of three additional autonomous weather stations for simultaneous multi-site data collection.
- A reinforced apparatus to elevate the anemometer to a height of approximately 25–30 feet to standardize wind measurements.
- Further intercepts of tropical cyclones in future hurricane seasons to expand the dataset.

**Note on Data Accessibility**: Raw observational datasets are currently restricted due to evolving meteorological data sharing policies. Figures are shared here for documentation purposes, with dataset access potentially available upon request for academic collaboration.

---

## License

This repository is provided under the MIT License. Figures and methodologies may be used for research and educational purposes with appropriate attribution.
"""
