# 🚦 Road Accident Data Analysis & Visualization

A data visualization project that analyzes road accident data using **Python**, **Seaborn**, **Plotly**, and **Folium** to uncover meaningful patterns, trends, and high-risk factors associated with road accidents.

---

## 📌 Project Overview

Road accidents are a major public safety concern. This project focuses on exploring and visualizing road accident data to:
- Understand accident trends over time
- Analyze the impact of weather, lighting, and road conditions
- Identify high-risk zones using geo-spatial maps
- Present insights through **interactive and visually appealing graphs**

The project is suitable for **academic submission, GitHub portfolio, viva exams, and resumes**.

---

## 📁 Dataset Description

The **Road Accident Dataset** contains detailed records of road traffic accidents, including:
- Accident date and time
- Accident severity
- Weather and light conditions
- Road surface conditions
- Speed limits
- Number of vehicles and casualties
- Accident location (latitude & longitude)

The dataset supports **exploratory data analysis (EDA)** and **visual storytelling**.

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:
- Cleaned column names (lowercase & underscore format)
- Converted date columns to datetime format
- Handled missing values:
  - Categorical → filled with `"Unknown"`
  - Numerical → filled with median values
- Removed duplicate records
- Created new features (year, month, weekday)

---

## 📊 Visualizations Used

### 🔹 Seaborn (Statistical Visualization)
- Accident severity distribution
- Accidents by day of week
- Speed limit vs accident frequency
- Casualties distribution

### 🔹 Plotly (Interactive Visualization)
- Year-wise accident trends
- Accidents by weather conditions
- Accidents by light conditions
- Urban vs rural accident comparison

### 🔹 Folium (Geo-Spatial Visualization)
- Accident location map
- Accident density heatmap

---

## 🛠️ Technologies & Libraries

- **Python**
- **Pandas** – Data handling & preprocessing
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Static visualizations
- **Plotly** – Interactive charts
- **Folium** – Map-based visualizations

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
pip install -r requirements.txt