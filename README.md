# Linear and Nonlinear Modeling Framework
# Research Title: Nonlinear Modeling of Selenium Biomarker Dynamics in Keshan Disease: Insights from Human and Rat Studies

### 1. Overview
This code repository contains statistical analysis scripts for linear and nonlinear modeling of selenium nutritional indicators. The analyses encompass:
- Linear and nonlinear modeling of human data
- Multimodel comparison of animal experimental data

### 2. Runtime Environment
- **R Version**: 4.5.0
- **Key R Packages and Versions**:
  - readxl (1.4.5)
  - mgcv (1.9-3)
  - rms (8.0-0)
  - gam (1.22-5)
  - stats (4.5.0)
  - rcompanion (2.5.0)
  - ggsci (3.2.0)
  - dplyr (1.1.4)
  - ggplot2 (3.5.2)

### 3. File Structure
- `01_Human_Analysis.R`: Human Data Modeling
- `02_Animal_Experiment_Analysis.R`: Animal Experiment Data Modeling
- `data/` (Not included in submission): Store raw data files

### 4. Data Description
- Human Data: `Population.xlsx`，Contains variables: hair selenium, serum selenium, selenoprotein P, age, sex, region, province
- Animal Experiment Data: `Rats.xlsx`，Contains variables: Whole-blood Se, Erythrocyte Se, Plasma Se, Serum Se, Whole-blood GSH-Px, Plasma GSH-Px, Serum GSH-Px, Plasma SELENOP, Serum SELENOP, Dorsal hair Se, Ventral hair Se, group, point, weight
- *Note: Raw data are available from the corresponding author upon reasonable request.*

### 5. Operating steps
1. Set the current code folder as the working directory
2. Run `01_Human_Analysis.R`
3. Run `02_Animal_Experiment_Analysis.R`
4. Review the generated analysis results and console output

### 6. Output result
- Console: Model Summary, AIC/BIC, RMSE/MAE, R²
- Plot: Fitted curve (saved as PDF)

### 7. Contact
For any inquiries, please contact: [2021020175@hrbmu.edu.cn]
Code last updated: [11 August 2025]
