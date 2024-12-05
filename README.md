# Rice Production Prediction Assignment  

This repository contains the implementation of a machine learning pipeline for predicting rice production using exploratory data analysis (EDA) and preprocessing techniques. The methodology and dataset used in this assignment are inspired by the research paper:  

**Title**: [An Automated Rice Production Forecasting System](https://ieeexplore.ieee.org/document/10714323/references#algorithms)  
**Journal**: W-category journal  

---

## Dataset  
The dataset includes the following features:  
- **Harvested Area**  
- **Production**  
- **Rainfall**  
- **Humidity**  
- **Temperature**  
- **Province**  

The dataset comprises **204 entries** and **7 columns**, representing rice production trends across different regions.  

---

## Methodology  

### 1. Exploratory Data Analysis (EDA)  
- Conducted descriptive statistical analysis (mean, median, min, max).  
- Visualized trends and patterns in rice production over time.  
- Analyzed the impact of rainfall, humidity, and temperature on production.  

### 2. Preprocessing  
- **One-Hot Encoding**: Encoded the categorical feature `Province`.  
- **Normalization**: Applied Min-Max scaling to numerical features for standardization.  
- **Pipeline**: Used `ColumnTransformer` and `Sklearn Pipelines` for efficient and modular preprocessing.  

### 3. Modeling  
- **Random Forest Regressor**: Trained and tested the model on the preprocessed data.  
- Evaluated model performance using:  
  - Regression metrics: **Mean Squared Error (MSE)** and **R² Score**.  
  - Binary classification metrics: **Confusion Matrix** and **Accuracy** by thresholding continuous predictions.  

---

## Results  
- **Random Forest Model Performance**:  
  - **MSE**: *Calculated value*  
  - **R² Score**: *Calculated value*  
- **Binary Classification Accuracy**: *Accuracy score*  
------

## References  
- [Research Paper Link](https://ieeexplore.ieee.org/document/10714323/references#algorithms)  
- **Data Source**: [https://ieee-dataport.org/documents/datatanamanpadiindonesia2018-2023](https://ieee-dataport.org/documents/datatanamanpadiindonesia2018-2023)  
