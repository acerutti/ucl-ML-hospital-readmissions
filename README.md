# ucl-ML-hospital-readmissions
ML Models to predict hospital readmissions with 30 days post-discharge

As of 2020, diabetes was associated with 7.86 million hospital discharges in the United States (Center for Diseases Control and Prevention, 2023). The disease significantly increases the likelihood of morbidity and mortality among hospitalised patients. Furthermore, hospitalisation with diabetes escalates healthcare costs. A survey found that 22% of all hospital inpatient days were spent by people with diabetes and that hospital inpatient care accounted for half of the 174 billion USD total U.S. medical expenditures for this disease (American Diabetes Association, 2008). Thirty-day hospital readmissions are a relevant indicator of healthcare quality and are often used as a target when reducing costs (Axon and Williams, 2011). The rate of readmission among patients with diabetes is substantial, literature suggests that it ranges from a low of 7.7% to 20% (Jiang *et al.*, 2005; Robbins and Webb, 2006). Studies show that up to 55% of hospital readmissions may be due to inappropriate inpatient care or poor discharge planning, and therefore preventable (Ashton *et al.*, 1995; Oddone *et al.*, 1996).

This project endeavours to develop ML models predicting and potentially reduce premature hospital readmissions. The research utilises data from the UC Irvine Machine Learning Repository, representing clinical care at 130 U.S. hospitals between 1999 and 2008, to forecast the probability of diabetic patients being readmitted within 30 days post-discharge. The report can be found in the report folder here on GitHub. 

# How to use: 
- `Diabetes_Final_Notebook` contains the end to end project, simply clone the repository and run it on you local machine. 
- `NN3_analysis` contains the analysis for the Random Search MLP model (NN4)
- `data_diabetes_130us_hospitals_1999_2008` contains all dataset used
- `diabetis_clean.csv` has the dataset after cleaning. 