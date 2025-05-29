# ACE1-cloud-ML-analysis

Machine Learning-based analysis of aerosol-cloud interaction using ACE-1 campaign data.

---

## 📌 Project Description

This project explores the relationship between cloud microphysical properties (e.g., Nc, Nd, droplet diameter) and aerosol characteristics using data collected during the **ACE-1 (Aerosol Characterization Experiment)** field campaign.

Cloud droplet spectra are grouped based on **NDF thresholds** (e.g., low octile, high half, etc.) to distinguish **bimodal** and **unimodal** characteristics. The grouped data are then analyzed with machine learning methods to identify patterns and predictive relationships.

---

## 🎯 Objectives

- Classify cloud spectra into bimodal/unimodal using NDF-based logic
- Plot Nc/Nd against diameter for different CCN environments
- Apply ML techniques to classify and cluster spectral behaviors
- Investigate links to altitude, wind speed, NCCN, and other meteorological parameters

---

## 📁 Repository Structure

├── data/ # Raw and preprocessed ACE-1 data
├── notebooks/ # Jupyter notebooks with exploratory analysis
├── scripts/ # Python scripts for reusable code
├── figures/ # Visual outputs of spectra
├── models/ # Trained ML models (optional)
├── requirements.txt # Required Python packages
└── README.md # Project overview (this file)

---

## Credits

This project is part of a PhD research conducted by **Fatma Emin** at the University of Nevada, Reno.  
Data source: ACE-1 field campaign.  
Advisor: **Dr. Jim Hudson**

---

## License

This project is licensed under the MIT License.
