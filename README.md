# Digitalization-Business-Growth-ML
ML project analyzing impact of digitalization on small business growth
# 📊 Digitalization Impact on Small Business Growth (ML Project)

This machine learning project analyzes how digital tools such as UPI payments, online marketplaces, and digital record keeping impact the growth of small businesses.

The objective is to determine whether digital adoption leads to measurable business growth using real survey data and machine learning models.

---

## 📌 Project Objective
To analyze the impact of digitalization on small businesses and predict whether a business will experience growth due to digital tool adoption.

This project uses survey data collected from small businesses across multiple cities and applies machine learning to identify patterns influencing business growth.

---

## 🧾 Dataset Information
The dataset contains survey responses from small businesses including:

- Smartphone usage for business  
- Internet usage for communication  
- UPI/mobile payment adoption  
- Online marketplace usage  
- Digital bookkeeping and records  
- Fear of fraud & transaction issues  
- Location of business (city-wise)

Target Variable:
- **Growth (0 = No Growth, 1 = Growth)** based on sales & reach increase due to digitalization.

---

## 🛠 Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📊 Exploratory Data Analysis (EDA)
EDA was performed to:
- Understand distribution of digital adoption
- Identify features influencing business growth
- Visualize correlations using heatmaps
- Compare growth vs non-growth businesses

Key insight:
Digital payments, online presence, and record management showed strong correlation with business growth.

---

## 🤖 Machine Learning Models Used

### 1️⃣ Logistic Regression
- Accuracy: ~69%
- Used as baseline model
- Shows moderate relationship between digital adoption and growth

### 2️⃣ Random Forest (Best Model)
- Accuracy: ~84.6%
- Better prediction performance
- Captures complex patterns in data

Random Forest performed better than Logistic Regression for predicting business growth.

---

### 🔮 Sample Prediction

The trained Random Forest model was tested on a sample business with digital adoption features.

Prediction:
Business will likely see GROWTH due to digitalization 📈

Probability:
Growth: 62%  
No Growth: 38%

This demonstrates how the model can be used to predict business growth based on digital tool adoption.

## 📁 Project Structure

Digitalization-Business-Growth-ML/
│
├── jharkhand.ipynb        # Main ML notebook
├── jharkhand.xlsx         # Survey dataset
├── requirements.txt       # Libraries used
└── README.md              # Project documentation


---

## 🚀 Future Improvements
- Combine all other eastern states dataset (Jharkhand, Odisha, West Bengal)
- Try advanced models (XGBoost, SVM)
- Deploy as web app using Streamlit
- Add feature importance visualization

---

## 👩‍💻 Team Contributions

**Megha Muskan**

* Data collection (Chakradharpur region)
* Data preprocessing and cleaning
* Feature engineering and encoding
* Exploratory Data Analysis (EDA)
* Machine Learning model building and evaluation
* GitHub repository creation and documentation

**Anshuman**

* Data collection (Jamshedpur region)

**Arpita**

* Data collection (Ranchi region)

---

## 👩‍💻 Author
**Megha Muskan**  
B.Tech CSE | Data Analytics & ML Enthusiast

