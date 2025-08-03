# Smartphone_Data_Science_Project

This repository contains my complete coding test for a **Smartphones Dataset Project**, sourced from Kaggle. The project is designed to practice end-to-end data science tasks — from loading and exploring data to building predictive models and analyzing key features.

---

## Dataset

The dataset used is the **Smartphones Cleaned Dataset** by `chaudharisanika` on Kaggle. It includes detailed specifications of smartphones such as:

- Price  
- Brand and model  
- RAM and internal memory  
- Battery capacity  
- Processor and operating system  
- SIM type and other features  

---

## Project Sections & Summary

### Section 1: Exploratory Data Analysis (EDA)
- Loaded and reviewed the dataset structure and sample rows  
- Identified unique brands, checked for missing values, and calculated basic statistics  
- Analyzed average RAM and phone count per brand  
- Examined numeric feature correlations  

---

### Section 2: Visualization & Plotting
- Created histograms, bar charts, scatter plots, and boxplots  
- Visualized brand-wise price distribution and RAM-price relationship  
- Generated a correlation heatmap and KDE plot of price  
- Used pairplots for multivariate numeric trends  
- Improved plot readability and saved visualizations  

---

### Section 3: Regression & Price Prediction
- Preprocessed the data (handled missing values, encoded categorical features)  
- Defined features (`X`) and target (`y`) for price prediction  
- Trained a **Linear Regression** model and evaluated performance (MSE, R²)  
- Introduced a new feature: `price_per_gb`  
- Applied **StandardScaler** for normalization  
- Trained a **Decision Tree Regressor** for comparison  

---

### Section 4: Feature Importance & Trend Analysis
- Visualized top contributing features from the decision tree  
- Selected key predictors using `SelectKBest`  
- Filtered and sorted phones by RAM and battery  
- Grouped data by brand to compute average stats  
- Counted dual SIM devices and visualized additional trends  

---

### Section 5: Train-Test Split & Feature Scaling
- Explained why we split data and the importance of `random_state` for reproducibility  
- Covered overfitting risks when evaluating on training data  
- Applied **StandardScaler** to ensure fair feature contribution  
- Highlighted the impact of unequal scales (e.g., RAM vs Battery) on model performance  

---

## Tools & Libraries Used

- Python (pandas, matplotlib, seaborn, scikit-learn)
- Jupyter Notebook
- Kaggle API (`kaggle`, `python-dotenv`)

---

## Repository Structure
SMARTPHONE_DATA_SCIENCE_PROJECT/

┣ 📁 smartphone_env/ # Virtual environment (ignored by .gitignore)

┣ 📁 smartphone-dataset/ # Folder containing the raw dataset

┃ ┗ 📄 Smartphones_cleaned_dataset.csv

┣ 📄 .env # Environment variables (e.g., Kaggle API key)

┣ 📄 .gitignore # Files/folders to ignore in version control

┣ 📄 pricekde.png # Saved KDE plot of price distribution

┣ 📄 README.md # Project overview and documentation

┣ 📄 smartphone.ipynb # Main Jupyter Notebook with all analysis

┣ 📄 smartphones-dataset.zip # Downloaded raw ZIP from Kaggle

---

## Project Status

This project is complete and covers all required steps from EDA to regression and feature analysis.

## Acknowledgments

- Dataset by [chaudharisanika on Kaggle](https://www.kaggle.com/datasets/chaudharisanika/smartphones-dataset)

## Contact

For feedback or collaboration:(mailto:lucyjoanwere2@gmail.com)

