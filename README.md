# 📊 Digitalization Impact on Small Business Growth (ML Project)

This machine learning project analyzes how digital tools such as **UPI payments, online marketplaces, digital communication, and digital record keeping** impact the growth of small businesses.

Using survey data collected from local businesses, machine learning models are trained to predict whether **digital adoption leads to measurable business growth**.

---

# 📌 Project Overview

Small businesses are increasingly adopting digital tools to improve efficiency, attract customers, and manage operations.

This project explores whether **digital adoption contributes to business growth** by analyzing survey responses from small businesses across multiple cities.

Machine learning models are used to identify patterns and predict the likelihood of business growth.

---

# 🎯 Project Objective

The main objectives of this project are:

- Analyze how digital tools affect small business operations
- Identify which digital factors influence business growth
- Build machine learning models to predict business growth
- Compare multiple models to find the best performing one

---

# 🧾 Dataset Information

The dataset contains **survey responses from 193 small businesses**.

Features include:

- Smartphone usage for business  
- Internet usage for communication  
- UPI / mobile payment adoption  
- Online marketplace usage  
- Digital bookkeeping and records  
- Customer engagement through digital messaging  
- Fear of fraud and transaction challenges  
- Business location (city-wise)

### Target Variable
**Growth**

- `0` → No Growth  
- `1` → Business experienced growth due to digitalization

The target variable was created based on **sales and customer reach improvement scores**.

---

# 📊 Exploratory Data Analysis (EDA)

EDA was performed to understand the relationship between digital adoption and business performance.

Key steps included:

- Growth distribution analysis
- Correlation heatmap visualization
- Identifying features most associated with business growth

### Key Insight

Digital payments, online presence, and digital record management show strong positive relationships with business growth.

---

# 🤖 Machine Learning Models Used

Several classification models were tested:

### 1️⃣ Logistic Regression
- Accuracy: **~69%**
- Used as a baseline model

### 2️⃣ Random Forest
- Accuracy: **~84.6%**
- Captures complex relationships in data

### 3️⃣ Bagging Classifier
- Improves stability by combining multiple models

### 4️⃣ Gradient Boosting
- Sequential learning to improve predictions

### 5️⃣ Voting Classifier
- Combines predictions from multiple models

---

# 🏆 Best Performing Model

**Random Forest / Bagging Classifier** achieved the highest accuracy (~85–87%), indicating strong predictive capability for identifying business growth patterns.

---

# 🔮 Sample Prediction

A trained model was tested on a sample business with digital adoption features.

Prediction Result:

📈 **Business likely to experience growth due to digitalization**

Prediction Probability:

- Growth → **62%**
- No Growth → **38%**

This demonstrates how machine learning can help estimate **business outcomes based on digital adoption behavior**.

---

# 📁 Project Structure

```
Digitalization-Business-Growth-ML/
│
├── jharkhand.ipynb        # Main ML notebook
├── jharkhand.xlsx         # Survey dataset
├── requirements.txt       # Required libraries
└── README.md              # Project documentation
```

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 🚀 Future Improvements

- Combine datasets from multiple eastern states
- Try advanced models (XGBoost, SVM)
- Add feature importance analysis
- Deploy project using **Streamlit**

---

# 👩‍💻 Team Contributions

### Megha Muskan
- Data collection (Chakradharpur region)
- Data preprocessing and cleaning
- Feature engineering
- Exploratory Data Analysis
- Machine learning modeling
- Model evaluation
- GitHub repository creation

### Anshuman
- Data collection (Jamshedpur region)

### Arpita
- Data collection (Ranchi region)

---

# 👩‍💻 Author

**Megha Muskan**  
B.Tech CSE  
Data Analytics & Machine Learning Enthusiast
