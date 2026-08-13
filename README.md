# Healthcare-Data-Analysis---Data-cleaning-and-Exploratory-data-analysis
This project performs exploratory data analysis (EDA) on patient healthcare records to uncover patterns and insights related to patient demographics, diagnoses, blood pressure, cholesterol levels, and lifestyle factors. The analysis demonstrates various pandas operations including data cleaning, transformation, grouping, aggregation, and merging.

**Key Objectives:**
- Clean and preprocess healthcare data
- Analyze patient demographics and diagnoses distribution
- Investigate relationships between health indicators (BP, cholesterol, diabetes, smoking)
- Create meaningful features and categorizations
- Demonstrate data merging capabilities with lab results
- Data Visualization

##  Dataset

The dataset contains **120 patient records** with the following features:

| Column | Type | Description |
|--------|------|-------------|
| PatientID | int64 | Unique patient identifier |
| Age | int64 | Patient age in years |
| Gender | object | Male (M) or Female (F) |
| Diagnosis | object | Primary diagnosis |
| BloodPressure | int64 | Systolic blood pressure (mmHg) |
| Cholesterol | int64 | Cholesterol level (mg/dL) |
| Diabetes | object | Yes/No indicator |
| Smoker | object | Yes/No indicator |

**Diagnosis Categories:**
- Healthy
- Hypertension
- Obesity
- Asthma
- Diabetes
- Arthritis
- Heart Disease

## ✨ Features

### Data Processing
- ✅ Data loading and initial exploration
- ✅ Handling missing values (imputation)
- ✅ Column renaming and type conversion
- ✅ Feature engineering (BMI, Risk Flags, Age Groups)
- ✅ Data filtering and selection

### Analysis Capabilities
- ✅ Grouping and aggregation
- ✅ Pivot tables for cross-tabulation
- ✅ Multi-condition filtering
- ✅ Data sorting and ranking
- ✅ Statistical summaries
