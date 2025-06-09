# Task-5 Titanic Exploratory Data Analysis(EDA)

# Objective
Perform Exploratory Data Analysis (EDA) on the Titanic dataset using Python to identify key survival trends and visualize feature relationships.

# Repository Structure
 
Titanic-EDA-Project/
├── data/                        # Titanic dataset
│   └── titanic.csv              
│
├── notebooks/                   # Jupyter Notebook
│   └── TITANIC_EDA.ipynb        
│
├── reports/                     # PDF reports
│   ├── Titanic_EDA_Report.pdf   
│   └── Summary of Findings.pdf  
│
├── eda_screenshots/             # Optional: Exported plot images
│   └── survival_by_gender.png   
│
└── README.md                    # Main documentation

# Dataset
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- Contains details of passengers aboard the Titanic — used to explore survival patterns.

# Tools Used
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Platform**: Jupyter Notebook


# EDA Workflow

- ✔ Data loading & structure inspection (`.info()`, `.describe()`, `.value_counts()`)
- ✔ Missing value analysis (`.isnull().sum()`)
- ✔ Visualizations:
  - `sns.pairplot()` to analyze feature relationships
  - `sns.heatmap()` to view correlations
  - Countplots for categorical comparisons
  - Boxplots, histograms, scatter plots
- ✔ Observations written under each plot
- ✔ Final findings summarized
  
# Key Insights

- **Survival Rate**: ~38% overall
- **Gender**: Females had significantly higher survival rates
- **Class**: 1st Class passengers had best survival outcomes
- **Fare**: Higher ticket fares linked to survival
- **Missing Data**: Age (177), Cabin (687), Embarked (2)

# Reports

- 📄 **Titanic_EDA_Report.pdf**: Full report with visuals and trends
- 📄 **Summary of Findings.pdf**: 1-page insight summary


**Name**: SION RANI
**LinkedIn**: www.linkedin.com/in/sionrani


