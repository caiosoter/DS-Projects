![](https://greenheart.org/wp-content/uploads/light-1030988_1920-650x433.jpg)
# Appliance Energy Prediction:
The Dataset (experimental) was created to study appliances consumption in a low energy building. Furthermore, the dataset was build with energy data points collected every 10 minutes and the humidity and temperature data were averaged for 10 minutes periods. The dataset is at 10 minutes for roughly 4.5 mounts. To conclude, it is important to say that this project is in the scope of Supervised Regression problems and the dataset can be found in the first link in the references.

# Dictionary (Columns):
  - date: Date(Year-Month-Day) and time(Hour:Minutes:Seconds) of the measurements.
  - Appliances: Energy used (Wh).
  - lights: Energy use in light fixtures (Wh).
  - T1: Temperature in kitchen area (°C).
  - RH_1: Humidity in kitchen area (%).
  - T2: Temperature in living room area (°C).
  - TH_2: Humidity in living room area (%).
  - T3: Temperature in laundry area (°C).
  - RH_3: Humidity in laundry area (%).
  - T4: Temperature in office room (°C).
  - RH_4: Humidity in office room (%). 
  - T5: Temperature in bathroom (°C).
  - RH_5: Humidity in bathroom (%).
  - T6: Temperature outside the building, measured from the north side (°C).
  - RH_6: Humidity outside the building, measured from the north side (%).
  - T7: Temperature in ironing room (°C).
  - RH_7: Humidity in ironing room (%).
  - T8: Temperature in teenager room 2 (°C)
  - RH_8: Humidity in teenager room 2 (%).
  - T9: Temperature in parents room (°C).
  - RH_9: Humidity in parents room (%).
  - T_out: Temperature outside, measured from Chievres weather station (°C).
  - Pressure: Measured from Chievres weather station (mm Hg).
  - RH_out: Humidity outside, measured from Chievres weather station (%).
  - Wind speed: Measured from Chievres weather station (m/s).
  - Visibility: Measured from Chievres weather station (km).
  - Tdewpoint: Measured from Chievres weather station (Â°C)
  - rv1: Random variable 1 (nondimensional).
  - rv2: Random variable 2 (nondimensional).
  

# References:
- https://www.kaggle.com/datasets/loveall/appliances-energy-prediction
- https://towardsdatascience.com/a-practical-introduction-to-the-shapiro-wilk-test-for-normality-5675e52cee8f
- https://towardsdatascience.com/6-ways-to-test-for-a-normal-distribution-which-one-to-use-9dcf47d8fa93
- https://towardsdatascience.com/bayesian-optimization-concept-explained-in-layman-terms-1d2bcdeaf12f
- https://xgboost.readthedocs.io/en/stable/parameter.html
- https://towardsdatascience.com/an-interactive-guide-to-hypothesis-testing-in-python-979f4d62d85
- https://rhydhamgupta.medium.com/p-value-explained-clearly-regression-pdf-discrete-45c30b5dc813
