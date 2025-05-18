

# 🏦 AtliQo Bank – Credit Card Launch Strategy

This project simulates a real-world business scenario where **AtliQo Bank**, a fictional bank, aims to launch its first **credit card product**. The objective is to analyze customer credit profiles and transaction behavior to identify a target group, and then evaluate the performance of the new credit card through **A/B testing**.

---

## 🔍 Project Objective

1. **Understand customer behavior** through transaction and profile data.
2. **Identify a suitable target group** for the credit card launch.
3. **Conduct an A/B test** to evaluate the card's effectiveness.

---

## 📁 Dataset Overview

* **Customer Profile Data**: 1,000 records with features like age, occupation, annual income, credit history, etc.
* **Transaction Data**: 500,000 transaction records, including amount, date, and type.

---

## 🛠️ Key Steps

### 1. Data Cleaning

* Handled missing values
* Detected and treated outliers

### 2. Exploratory Data Analysis (EDA)

* Spending patterns across age groups and occupations
* Credit behavior segmentation
* Data visualizations using **Matplotlib** and **Seaborn**

### 3. Target Group Selection

* Divided customers into three age segments:

  * 18–25
  * 26–48
  * 49–65
* Identified **18–25** as the ideal target group based on high engagement and spending potential

### 4. A/B Testing

* Created **control group** and **test group** of 40 customers each from the 18–25 segment
* Tracked transactions over a 2-month period
* Evaluated performance based on spending behavior
* **Result**: The new credit card showed better performance in the test group ✅

---

## 📊 Tools & Technologies

* **Python**
* **Pandas, NumPy**
* **Seaborn, Matplotlib**
* **Scipy.stats** for A/B testing
* **Jupyter Notebook**

---

## 📌 Key Takeaways

* Data-driven strategies can effectively shape product launches.
* Younger customers (18–25) showed the highest credit card engagement.
* A/B testing confirmed the success of the new credit card before a full rollout.

---
