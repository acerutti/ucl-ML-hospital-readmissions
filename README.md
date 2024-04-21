# ucl-ML-hospital-readmissions
ML Models to predict hospital readmissions with 30 days post-discharge

This repository hosts materials for an ML project aimed at predicting and reducing premature hospital readmissions. It uses data from 130 U.S. hospitals (1999-2008) from the UC Irvine Machine Learning Repository to predict 30-day readmission rates for diabetic patients. For the full report, see the report folder.

# Diabetes has an enormous impact on the US Healthcare system
In 2020, the U.S. recorded 7.86 million hospital discharges related to diabetes (CDC, 2023), a significant factor in patient morbidity and healthcare costs. Diabetic patients represented 22% of hospital inpatient days, with inpatient care comprising half of the $174 billion spent on diabetes (ADA, 2008). Readmissions within 30 days are a key healthcare quality measure (Axon and Williams, 2011), with diabetes-related readmission rates varying between 7.7% to 20% (Jiang et al., 2005; Robbins and Webb, 2006). Studies indicate up to 55% of readmissions may be preventable (Ashton et al., 1995; Oddone et al., 1996). *For the references see report*

# How to use: 
- `Diabetes_Final_Notebook` contains the complete project. To access it, simply clone the repository and run it on your local machine. 
- `NN3_analysis` contains the analysis for the Random Search MLP model (NN4)
- `data_diabetes_130us_hospitals_1999_2008` contains all dataset used, source: https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008
- `diabetis_clean.csv` has the dataset after cleaning. 
