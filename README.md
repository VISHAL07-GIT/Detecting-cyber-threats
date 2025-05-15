# 🚨 Detecting Cyber Threats Through Anomaly Detection in Network Traffic

This project focuses on identifying anomalies in network traffic data using exploratory data analysis (EDA) and statistical techniques. It is part of an academic submission for a data analytics course (Phase 3).

---

## 📌 Problem Statement

With increasing cybersecurity threats, monitoring and analyzing network traffic for irregular patterns is crucial. This project aims to identify suspicious or potentially malicious behavior in network data using data-driven techniques.

---

## 📁 Project Structure

Detecting-cyber-threats/
├── data/ # Raw and cleaned datasets
├── notebooks/ # Colab notebook for analysis
│ └── main.ipynb
├── report/ # Phase 3 report and documentation
├── images/ # Graphs, charts, and flowcharts
└── README.md # Project summary

yaml
Copy
Edit

---

## 📊 Dataset Description

- **Filename**: `Midterm_53_group.csv`
- **Type**: Structured
- **Fields**: Includes `Time`, `Source`, `Destination`, `Protocol`, `Length`, `No.`
- **Size**: ~400,000 rows
- **Source**: Provided by instructor

---

## 🔍 Key Features Analyzed

- Source IP frequency (Top 15)
- Packet arrival distribution over time
- Boxplot and histogram of time values
- Correlation heatmap of numerical columns
- Pairplot for visual multivariate analysis

---

## 📈 Techniques Used

- Data cleaning (missing values, type checks)
- Descriptive statistics
- Visualization using Seaborn and Matplotlib
- Outlier detection (boxplots)
- Correlation and trend analysis

---

## 🧠 Insights

- Some IPs contribute disproportionately to network traffic.
- Certain time windows experience spikes—possible signs of DoS or brute force activity.
- Strong linear relationship between `Time` and `No.` fields.
- Packet lengths appear uniformly distributed and uncorrelated with time or number.

---

## ✅ Tools and Technologies

- **Python** (pandas, numpy, matplotlib, seaborn, scipy)
- **Google Colab**
- **GitHub** (for version control)
- *(Optional: Power BI or Tableau for future dashboards)*

---

## 📌 How to Run

1. Clone this repository:

   git clone https://github.com/VISHAL07-GIT/Detecting-cyber-threats.git
Open the Colab notebook:
Google Colab Notebook

Upload the dataset (Midterm_53_group.csv) when prompted.

Run each cell step by step for EDA and results.

👨‍💻 Team Members
Name	Role
Vishal S	Data Collection & Preprocessing
Vasudevan P	Exploratory Data Analysis
Kanniappan M	Statistical Analysis & Insights
Punithavel S	Documentation & Report Preparation

📌 Future Scope
Integrate real-time packet stream analysis

Implement machine learning anomaly detection (e.g., Isolation Forest)

Visual dashboard for SOC teams using Power BI or Dash

Expand to include sentiment analysis for user behavior logs

