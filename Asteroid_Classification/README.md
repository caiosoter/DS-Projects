
![](https://images.rawpixel.com/image_800/cHJpdmF0ZS9zdGF0aWMvaW1hZ2VzL3dlYnNpdGUvMjAyMy0wNC93azEwMjc4MDUxMS1pbWFnZS5qcGc.jpg)

# Asteroid Hazard Classification
The objective of this project is to employ various types of asteroid information to classify them as either hazardous or non-hazardous. The data, obtained from Kaggle, is meticulously curated by the Jet Propulsion Laboratory (JPL) of the California Institute of Technology, an esteemed institution operating under the auspices of NASA. The collected data will be utilized to train and apply machine learning algorithms specifically designed for classification purposes.

# Dictionary (Columns)
- SPK-ID: Object primary SPK-ID.
- Object ID: Object internal database ID.
- Object fullname: Object full name/designation.
- pdes: Object primary designation.
- name: Object IAU name.
- class: Orbit Class.
- NEO: Near-Earth Object (NEO) flag.
- PHA: Potentially Hazardous Asteroid (PHA) flag. (Target)
- H: Absolute magnitude parameter.
- Diameter: object diameter from equivalent sphere (km).
- Albedo: Geometric albedo.
- Diameter_sigma: 1-sigma uncertainty in object diameter (km).
- Orbit_id: Orbit solution ID.
- Epoch: Epoch of osculation in modified Julian day form.
- Equinox: Equinox of reference frame.
- e: Eccentricity.
- a: Semi-major axis (au).
- q: perihelion distance (au).
- i: inclination; angle with respect to x-y ecliptic plane.
- om: Longitude of the ascending node (deg).
- w: Argument of perihelium (deg).
- ma: Mean Anomaly (deg).
- ad: Aphelion distance (au).
- n: Mean Motion (deg/au).
- tp: Time of perihelion passage (TDB).
- tp_cal: Time of perihelion passage (TDB). 
- moid: Earth Minimum Orbit Intersection Distance (au).
- moid_ld: Earth Minimum Orbit Intersection Distance (ld).
- sigma_e: Eccentricity (1 - sigma uncertainty).
- sigma_a: Semi-major axis (1 - sigma uncertainty) (au).
- sigma_q: Perihelion distance (1 - sigma uncertainty) (au).
- sigma_i: Inclination (1 - sigma uncertainty) (au).
- sigma_om: Long. of the asc. node (1 - sigma uncertainty) (deg). 
- sigma_w: Argument of perihelion (1 - sigma uncertainty) (deg).
- sigma_ma: Mean anomaly (1 - sigma uncertainty) (deg).
- sigma_ad: Aphelion distance (1 - sigma uncertainty) (au).
- sigma_n: Mean motion (1 - sigma uncertainty) (deg/d).
- sigma_tp: Time of peri. passage (1 - sigma uncertainty) (au).
- sigma_per: Sideral orbital period (1 - sigma uncertainty) (d).

# References
- [Asteroid-dataset](https://www.kaggle.com/datasets/sakhawat18/asteroid-dataset)
- https://git-lfs.com/
- https://towardsdatascience.com/data-cleaning-with-python-using-pandas-library-c6f4a68ea8eb
- https://www.oxfordreference.com/display/10.1093/oi/authority.20110810105606956;jsessionid=A2FBB8776E86C44F3E3A1144DABF8ACD#:~:text=The%20date%20and%20time%20at,its%20closest%20to%20the%20Sun.
