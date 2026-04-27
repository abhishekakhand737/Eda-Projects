# 📊 EDA Project

> A collection of Exploratory Data Analysis (EDA) projects using Python to extract insights from real-world datasets.

---

## 📌 Repository Info

* 👤 **Username:** abhishekakhand737
* 📁 **Repository:** Eda-Projects

---

## 📂 Projects Included

### 🪔 Diwali Sales Analysis

A complete Exploratory Data Analysis project on Diwali sales dataset to understand customer behavior & sales trends.

---

## 🎯 Objectives

* Understand customer purchasing patterns
* Analyze demographic impact (Age, Gender, State)
* Identify top-performing product categories
* Generate business insights from data

---

## 🛠️ Tech Stack

* Python 
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🔍 Analysis Workflow

### 🔹 Data Cleaning

* Removed null values
* Handled missing data
* Dropped unnecessary columns

---

### 🔹 Exploratory Data Analysis (EDA)

* Gender-wise analysis
* Age group analysis
* State-wise sales distribution
* Product category insights

---

## 📊 Sample Code

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

df = pd.read_csv('Diwali Sales Data.csv', encoding='unicode_escape')

sns.set(rc={'figure.figsize':(15,5)})

sales_state = df.groupby(['State'], as_index=False)['Orders'].sum().sort_values(by='Orders', ascending=False).head(10)

sns.barplot(data=sales_state, x='State', y='Orders')
plt.show()
```

---

## 📈 Key Insights

* 🟢 Female customers contribute more to total sales
* 🟢 Age group 26–35 shows highest purchasing activity
* 🟢 Top states: Uttar Pradesh, Maharashtra, Karnataka
* 🟢 High demand in Food, Clothing, Electronics categories

---

## ▶️ How to Run

```bash
git clone https://github.com/abhishekakhand737/Eda-Projects.git
cd Eda-Projects
pip install -r requirements.txt
jupyter notebook
```

---

## 📁 Project Structure

```bash
Eda-Projects/
│── 01_Diwali_Sales_Eda.ipynb
│── Diwali Sales Data.csv
│── README.md
```

---

## 🚀 Future Improvements

* Add more EDA projects
* Build interactive dashboards (Plotly / Power BI)
* Add Machine Learning models

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and improve.

---

## 👨‍💻 Author

**Abhishek Akhand**

---

Different types of Eda Project in Data Analysis.
