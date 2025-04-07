# Social Media & Mental Health — Data Preprocessing

This notebook focuses on preprocessing a mental health dataset related to social media usage. It is the first step in preparing the data for further exploration and machine learning tasks.

## File: `SMMH.ipynb`

### Key Steps:
- **Import Libraries**: Essential Python packages such as NumPy, Pandas, Seaborn, Matplotlib, and Scikit-learn are used.
- **Data Loading**: Reads `smmh.csv` (Social Media and Mental Health) from Google Drive.
- **Basic Data Inspection**:
  - Dataset shape, column overview
  - Missing value checks
  - Unique values per column
- **Cleaning**:
  - Removal of unnecessary columns (like timestamps)
  - Correction of inconsistent column names
- **Data Transformation**:
  - Categorical value standardization (e.g., converting various forms of gender input to a consistent format)
  - Handling "other" responses
- **Train-Test Split**: Dataset is split into training and testing sets for future modeling.

### Dataset Info:
- **Source**: Custom survey dataset uploaded to Google Drive
- **Format**: CSV (`smmh.csv`)
- **Purpose**: To understand and model the relationship between social media usage and mental health indicators.

##  Next Steps
- Run EDA (Exploratory Data Analysis) in `Notebook_2_EDA.ipynb`
- Perform Encoding and Feature Engineering
- Build Machine Learning Models

---


