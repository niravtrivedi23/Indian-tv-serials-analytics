# 📊 📡TV Serial Broadcast Analytics – India (1889–2025)

A comprehensive data analytics project combining the power of Python (with Machine Learning) and Power BI to uncover patterns and insights from over a century of Indian television serials.  
This project explores content longevity, genre dominance, network reach, and regional distribution through advanced modeling, clustering, and interactive visual storytelling.

---

## 🎯 Project Objectives

This project is structured around two key analytical domains:

### 🔹 Python (Advanced EDA & Machine Learning)

- Perform in-depth data profiling, feature engineering, and statistical exploration  
- Apply K-Means clustering to segment serials based on performance and longevity  
- Develop a Random Forest model to predict content genres based on historical data  
- Uncover hidden patterns using machine learning to support media strategy and planning  

### 🔹 Power BI (Interactive Dashboard & Data Storytelling)

- Design a dynamic dashboard to visualize trends in serial launches, genres, and network activity  
- Highlight key KPIs including top languages, longest-running serials, and regional distribution  
- Enable filter-based exploration to assist decision-makers in content production and analysis  

---

## 📊 Dataset Overview

| Aspect       | Detail                                                                 |
| ------------ | ---------------------------------------------------------------------- |
| 📁 Source    | [Kaggle – Indian TV Serials Dataset](https://www.kaggle.com/)         |
| 📆 Coverage  | 1889 to 2025 (136 years of content history)                            |
| 📄 Volume    | 350+ unique serials across 8+ structured attributes                    |
| 🧹 Data Quality | Cleaned and standardized manually for ML and BI readiness          |

**Core attributes**: Serial Name, Genre, Network, Episodes, Duration, Start & End Year, Language, State

---

## 🐍 Python Analysis – Unsupervised Clustering & Feature Engineering

An end-to-end analytical pipeline focused on understanding broadcast patterns in Indian TV serials, including robust data preprocessing, transformation, and unsupervised learning.

### 📦 Libraries & Tools Utilized

- **Pandas** – Data loading, wrangling, and transformation  
- **NumPy** – Numerical operations and array handling  
- **Matplotlib & Seaborn** – Visualization of trends, distributions, and correlations  
- **Scikit-learn** for:  
  - `preprocessing` – Feature scaling and label encoding  
  - `cluster` – K-Means clustering  
  - `metrics` – Model evaluation  
  - `model_selection` – (optional future expansion)  

### 🔍 Key Analytical Steps

#### 1️⃣ Data Cleaning & Preparation

- Handled missing values and inconsistent text formats  
- Converted date columns and calculated serial runtime  
- Standardized fields (Genre, Network, Language)  

#### 2️⃣ Feature Engineering

- Derived new features like:  
  - `Years` = End Year – Start Year  
  - `Launch_Month` = Month of initial airing  
  - `Decade` = Historical categorization  
- Encoded categorical columns using label encoding  

#### 3️⃣ Exploratory Data Analysis (EDA)

- Explored volume by genre, network, and language  
- Investigated regional/state-wise distribution  
- Identified seasonal trends and feature correlations  

#### 4️⃣ Feature Scaling

- Normalized numerical fields: Episodes, Years, Start Year using `StandardScaler`  

---

## 🤖 Machine Learning – K-Means Clustering (Unsupervised)

- **Optimal Clusters Identified**: k = 4 (using Elbow Method)  
- **Input Features**: Episodes, Years, Start Year  

### Cluster Categories:

- Cluster 0: Legacy Long-Running Serials  
- Cluster 1: High-Performer Modern Serials  
- Cluster 2: Average Duration Serials  
- Cluster 3: Short-Run Serials  

#### 📄 [Click to See Python Analysis](https://github.com/niravtrivedi23/Indian-tv-serials-analytics/blob/main/TV%20Serial%20Python%20Analysis.pdf)
---

## 📈 Power BI Dashboard – Visual Overview

 🔗 [View Power BI File (.pbix)](https://github.com/niravtrivedi23/Indian-tv-serials-analytics/blob/main/Indian%20TV%20Dashboard.pbix)  
An interactive dashboard created in Power BI to summarize serial trends, genres, durations, networks, and state-level production data.

### 💡 Dashboard Sections

| Section                   | Description                                                                |
| ------------------------- | -------------------------------------------------------------------------- |
| 📅 Monthly Launch Trends  | Highlights seasonal serial debuts across the year                          |
| 🧠 KPI Cards              | Shows top language, genre, and dominant network                             |
| 📺 Network-wise Count     | Serial output by leading networks like DD National and Sun TV              |
| 🕒 Longest Running Serials| Highlights serials with maximum duration and episode count                 |
| 🌍 State-Wise Distribution| Maps regional spread of content creation                                    |
| 🎭 Genre Dominance        | Shows share of genres (Soap, Thriller, Sitcom, Mythological, etc.)         |

---

## 📌 Key Insights

| Metric                 | Insight                                                     |
| ---------------------- | ----------------------------------------------------------- |
| 🏆 Longest Running     | Krishi Darshan – 57 years, over 16,780 episodes             |
| 📺 Top Network         | Sun TV – 42 serials produced                                |
| 🌐 Leading Language    | Tamil – 78 serials                                           |
| 🎭 Most Common Genre   | Soap Opera – ~75% of all serials                            |
| 📅 Peak Launch Month   | August – 35+ serial debuts historically                     |
| 🧪 Clusters Identified | 4 segments – Legacy, Popular, Short-Run, Modern Serials     |

---

## 🖼️ Dashboard Preview

![TV Serial Dashboard](https://github.com/niravtrivedi23/Indian-tv-serials-analytics/blob/main/TV%20Serial%20Analysis%20Dashboard.png)

---

## 📁 Files Included

| File Name                          | Description                                                      |
| ---------------------------------- | ---------------------------------------------------------------- |
| `tv_serial_analysis.py`            | Python script for data cleaning, EDA, ML modeling                |
| `TV Serial Python Analysis.pdf`    | Clean, formatted summary of Python insights                      |
| `TV Serial Broadcast.pbix`         | Power BI Dashboard file                                          |
| `TV Serial Analysis Dashboard.png` | Snapshot image of dashboard for GitHub preview                   |

⚠️ Dataset is not publicly included due to licensing. Source: [Kaggle](https://www.kaggle.com/)

---

## 🛠 Tools & Technologies Used

| Tool / Library      | Purpose                                                                 |
| ------------------- | ----------------------------------------------------------------------- |
| Python              | Data wrangling, feature engineering, machine learning                   |
| Pandas, NumPy       | Data processing and numerical operations                                |
| Matplotlib, Seaborn | Statistical and exploratory visualizations                              |
| Scikit-learn        | Clustering (KMeans), preprocessing, metrics                             |
| Power BI            | Dashboard development and storytelling                                  |
| Excel               | Manual data inspection and restructuring                                |

---

## ✅ Project Conclusion

This project effectively delivers both technical rigor and business clarity:

### Python (EDA + Clustering)

- Cleaned and profiled Indian TV serial data across 136 years  
- Segmented content using clustering to identify longevity and popularity patterns  
- Applied ML models for potential genre classification (~86% accuracy – optional extension)

### Power BI (Strategic Visualization)

- Dashboard brings actionable clarity to regional content, network reach, and serial performance  
- Filter-based interactivity helps stakeholders plan content pipelines efficiently  

**Combined**, Python and Power BI create an end-to-end analytics framework for media intelligence — transforming raw data into insights that support content planning, programming, and business growth.

---

## 📬 Get in Touch

| Platform    | Link                                                                                       |
| ----------- | ------------------------------------------------------------------------------------------ |
| 📧 Email    | [niravtrivedi069@gmail.com](mailto:niravtrivedi069@gmail.com)                              |
| 🔗 LinkedIn | [linkedin.com/in/trivedi-nirav-a1760424b](https://linkedin.com/in/trivedi-nirav-a1760424b) |
| 💻 GitHub   | [github.com/niravtrivedi23](https://github.com/niravtrivedi23)                             |

---

## 🎬 Final Thought

> *"Television serials tell stories to entertain. This project tells the story of the industry behind them — one dataset, one cluster, and one insight at a time."*
