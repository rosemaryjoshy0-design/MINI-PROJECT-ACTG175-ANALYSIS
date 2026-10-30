# MINI-PROJECT-ACTG175-ANALYSIS
# ACTG 175: Antiretroviral Efficacy & Clinical Endpoint Analysiss
# Overview
This project delivers a biostatistical and pharmacotherapeutic evaluation of the AIDS Clinical Trials Group (ACTG 175) dataset. The study evaluates the comparative efficacy of nucleoside reverse transcriptase inhibitor (NRTI) monotherapy versus dual-combination regimens in HIV-1 infected individuals. The project was executed in two phases: data pre-processing and aggregation in Microsoft Excel, followed by interactive visual analytics and dashboard design in Power BI Desktop.  

Zidovudine (ZDV) monotherapy demonstrated the highest clinical failure rate (34.2%) alongside a net 20-week biomarker decline (biomarker shift: -15.7 cells/mm^3).
Combination Superiority: Dual-combination therapy {ZDV+ddI} achieved superior immune reconstitution (biomarker shift: +62.5cells/mm^3) and substantially reduced disease progression (23.1%).

# Implementation
# Excel Pre-Processing: 
Data Cleaning & Transformation: Removed duplicates, imputed and audited null values, and standardized numeric indicators into clear clinical factors. 
Engineered Calculated Columns:Treatment arm: Mapped arm indices to pharmacological regimens (ZDV, ddI, ZDV + ddI, ZDV + Zal).
Biomarker shift: Computed biomarker delta (cd420 - cd40).   
Baseline_Immune_Tier: Stratified baseline CD4 into Severe (<200), Moderate (200-350), and Mild (>350) tiers.   
Antiretroviral_Experience: Categorized prior ART exposure into No, Short-Term, and Long-Term.

# Power BI Dashboard
Custom measures including [Total Patients], [Clinical Failure Rate], [Mean CD4 Gain], and [Mean Follow-up Days].
Interactive Filtering using slicers allowing multi-factorial cross-filtering by Treatment Arm, Prior ART Status, Immune Risk Tier, and Gender.
Visual Analytical using cards and charts.
