# Airplane Crash Analysis Project Plan

This document outlines a 5-week timeline for completing the airplane crash analysis project. Each week is organized with specific tasks and deliverables to keep the project on track.

---

## Week 1: Data Collection & Preprocessing

**Goals**
- Collect and organize data from FAA, NTSB, ASRS, and weather sources.

- ASRS - https://asrs.arc.nasa.gov/search/database.html

- Clean and preprocess each dataset for integration.

**Tasks**
- **Data Collection**: Locate, download, and store data in `data/raw`.
- **Data Cleaning**: Write scripts in `scripts/data_cleaning.py` to handle missing values, format inconsistencies, and duplicates.
- **Data Integration**: Start combining datasets based on shared fields (e.g., date, location).

**Deliverables**
- Cleaned data files saved in `data/processed`.
- Initial data integration script for merging datasets.

---

## Week 2: Complete Data Integration and Start EDA

**Goals**
- Finalize data integration across all sources.
- Begin exploratory data analysis (EDA) to understand initial patterns and trends.

**Tasks**
- **Complete Data Integration**: Finalize merging of all datasets and resolve integration issues.
- **Start EDA**: Use `notebooks/03_eda.ipynb` to analyze statistics (e.g., IFR vs. VFR crash rates).
- **Visualizations**: Generate initial plots to show trends in crash rates over time, location distributions, etc.

**Deliverables**
- Fully integrated dataset ready for analysis.
- EDA notebook with initial visualizations saved in `outputs/figures`.

---

## Week 3: Feature Engineering & Selection

**Goals**
- Engineer meaningful features for crash prediction and select key features.

**Tasks**
- **Feature Engineering**: Write `scripts/feature_engineering.py` to create features based on weather, pilot info, and aircraft data.
- **Feature Selection**: Use statistical methods or correlation analysis to identify important features.
- **Data Preparation**: Split the dataset into training and testing sets, applying normalization if necessary.

**Deliverables**
- Feature engineering script with created features.
- Split dataset, ready for model training.

---

## Week 4: Model Development & Evaluation

**Goals**
- Develop and evaluate machine learning models to predict crash causes and patterns.

**Tasks**
- **Model Selection**: Choose appropriate models (e.g., Decision Trees, Logistic Regression, Random Forest) and document choices in `notebooks/04_model_training.ipynb`.
- **Model Training**: Train models on the training set and evaluate performance on test data.
- **Parameter Tuning**: Optimize model parameters to improve accuracy.

**Deliverables**
- Trained models saved in `models/`.
- Model performance metrics and documentation in the model training notebook.

---

## Week 5: Final Analysis, Visualization, and Documentation

**Goals**
- Conduct final analysis, create visuals, and prepare project for submission.

**Tasks**
- **Final Analysis and Visualization**: Summarize model results and create final visuals.
- **Final Report & Presentation**: Compile insights into a report and STEM-ready presentation.
- **Documentation**: Complete `README.md`, add comments to code, and finalize project structure.

**Deliverables**
- Final report and presentation/poster in `outputs/reports`.
- Completed and polished `README.md` with clear instructions.
- Project fully ready for submission.

---

### Progress Tracking

Each week, check off completed tasks and add any additional notes to keep track of challenges and accomplishments. This project plan will be updated as milestones are reached.

---

