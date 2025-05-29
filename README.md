## 🛳️ Titanic Survival Prediction

Titanic Survival Prediction is a data analysis and machine learning project that explores passenger survival on the Titanic. It demonstrates end-to-end steps—from data loading and cleaning, through exploratory analysis and feature engineering, to training and evaluating classification models.

## 🌐 Live Preview

🔗 [Colab](https://colab.research.google.com/drive/1S9nvX6CFdgQrI1mBa5GFJSQTqQ8424_3#scrollTo=DGrlsviSeRA3)

## 📁 Project Structure

data/

train.csv – Training dataset (891 rows, 12 columns)

test.csv  – Test dataset (418 rows, 11 columns)

notebooks/

titanic_analysis.ipynb – Jupyter/Colab notebook covering ETL, EDA, feature engineering, and modeling

outputs/

figures/ – Generated plots (bar charts, violin plots, heatmaps)

models/  – (Optional) Serialized model files

requirements.txt – Python package dependencies

README.md        – Project overview and instructions (you are here)


## 🎯 Features & Highlights

## 🔍 Exploratory Data Analysis

Survival rates overall and by key features: Pclass, Sex, Embarked, Family size, Age, Fare

Violin plots and heatmaps to visualize distributions and correlations

##🛠️ Feature Engineering

Title extraction from passenger names

Encoding of categorical variables (Sex, Embarked, Title)

Imputation of missing Age values with randomized estimates

Binning of Age and Fare into discrete categories

Creation of family-related features: Family size and Alone flag

## 🤖 Model Training & Evaluation

Logistic Regression (∼80% train accuracy)

K-Nearest Neighbors (K=3, ∼84% train accuracy)

## 🛠️ Built With

Python 3.x

pandas

NumPy

matplotlib

seaborn

scikit-learn

## 🔎 Key Learnings

- Handling missing data and categorical encoding  
- Designing robust feature engineering pipelines  
- Visualizing data distributions and feature correlations  
- Applying and comparing classification algorithms  

---


## 👨‍💻 Author

**Pranjal Mishra**  
Student @ Northeastern University  
[GitHub](https://github.com/pranjalmishra) • [LinkedIn](https://www.linkedin.com/in/pranjalmishra)

---

📄 License
This project is for educational and portfolio purposes only. No commercial use intended.
---
