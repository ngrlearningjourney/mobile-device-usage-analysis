# 📱 User Behavior on Device Usage – Data Analysis Portfolio

Welcome to my Data Analysis Portfolio!  
This project explores how users interact with their mobile devices, focusing on screen time, app installations, battery drain, and more. The goal is to uncover user behavior patterns and provide actionable insights that could help improve user experience, battery efficiency, and device design.

---

## 📂 Dataset Overview

The dataset was sourced from **[Kaggle](https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fvalakhorasani%2Fmobile-device-usage-and-user-behavior-dataset)** and includes user-level information about:

- Device models
- Operating systems
- Age groups (Youth, Adult)
- Daily screen time
- Number of installed applications
- Battery drain levels
- Mobile data usage
- Gender

Dataset Source :  https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fvalakhorasani%2Fmobile-device-usage-and-user-behavior-dataset

---

## 🔧 Steps in Data Analysis

1. **Data Gathering**  
   The dataset was obtained from [Kaggle](https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fvalakhorasani%2Fmobile-device-usage-and-user-behavior-dataset), formatted as a CSV file.

2. **Data Wrangling**  
   - Checked for and handled **missing values**, **duplicates**, **misspellings**, and **inconsistent formats**  
   - Identified and addressed **outliers**

3. **Exploratory Data Analysis (EDA)**  
   - Explored distributions, trends, and relationships using visualizations and descriptive statistics

4. **Key Questions Answered**
   - 📱 **Device Models & Age Groups**: How much time do different age groups spend on mobile apps using various device models, and how many apps are installed?
   - ⚡ **Screen Time & Battery Drain**: Is there a correlation between screen time and battery drain?
   - 📊 **Gender Analysis**: How much time do males and females spend on mobile apps, and how many apps do they install?
   - 📲 **App Installation & Battery Drain**: Does having more installed apps affect battery consumption?
   - 🖥️ **Operating Systems**: Which OS (Android or iOS) is most commonly used?
   - 🌐 **Gender & Data Usage**: Is mobile data usage influenced by gender?
  
**For a detailed analysis, process, and insight, you can view the notebook here : [User Behavior Analysis📄](https://github.com/ngrlearningjourney/mobile-device-usage-analysis/blob/main/user_behavior_analysis.ipynb)**

---

## 📈 Key Insights

- **Device and OS Usage**
  - The most popular devices are **Xiaomi Mi 11** and **iPhone 12**.
  - **Android** is the dominant operating system (554 users), compared to **iOS** (146 users).

- **Screen Time and App Usage**
  - **Adults with OnePlus 9** spend the least time on mobile apps (30 mins/day).
  - **Youths with iPhone 12 or Galaxy S21** also have lower screen time (32 mins/day).
  - **Females** have a higher **minimum** screen time, but **males** have a much higher **maximum** (up to 9 hours).

- **App Installation Behavior**
  - **Samsung Galaxy S21** youth users have the highest **minimum** number of installed apps (≥19).
  - **Google Pixel 5** users (youth & adult) have identical app counts.

- **Battery Drain Correlation**
  - A **very strong correlation** between **screen time** and **battery drain** (r = **0.949**).
  - An even stronger correlation between the **number of installed apps** and **battery drain** (r = **0.962**).

- **Data Usage by Gender**
  - **Gender has almost no effect** on mobile data usage (r = **0.013**), showing neutral behavior across genders.

---

### 📊 Tools Used

* Python

  * `pandas`, `numpy` – for data manipulation and analysis
  * `matplotlib`, `seaborn` – for data visualization
  * `scipy.stats` – for statistical analysis (e.g., Spearman & point-biserial correlation)
* Jupyter Notebook
* Kaggle (data source)
