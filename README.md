# Traffic Data Analysis Project

## Overview

This project focuses on **analyzing traffic accident data** to extract meaningful insights and patterns. The analysis includes exploring accident trends, identifying high-risk locations, and visualizing the relationship between environmental and traffic-related factors.

The purpose of this project is to **demonstrate data cleaning, preprocessing, visualization, and exploratory data analysis (EDA) skills**.

> ⚠️ Note: The full dataset (\~2.9 GB) is **not included** due to GitHub size restrictions. A **sample dataset** with 5,000 rows is included for demonstration.

---

## Repository Structure

```
SCT_DS_4/
│
├── notebook/                     # Jupyter notebooks containing the analysis
│   ├── traffic_analysis.ipynb
│
├── data/                         
│   └── accidents_sample.csv      # Sample dataset (~1.9 MB)
│
├── result/                       # Optional folder for processed outputs
│
├── images/                       # Folder for plot images
│   ├── accident_trend.png
│   ├── accident_heatmap.png
│   └── severity_distribution.png
│
├── .gitignore                    
├── README.md                     
└── requirements.txt              
```

---

## Dataset

Includes accident records with key features such as:

* `Accident_ID`, `Date`, `Time`, `Location`, `Weather_Conditions`, `Road_Type`, `Severity`, `Vehicles_Involved`

> The **sample dataset** (`accidents_sample.csv`) contains 5,000 rows for analysis replication.

---

## Key Features

1. **Data Cleaning & Preprocessing**

   * Handle missing values & duplicates
   * Convert categorical features to numerical
   * Normalize numeric data

2. **Exploratory Data Analysis (EDA)**

   * Visualize accident trends over time
   * Identify hotspots using location data
   * Analyze frequency by road type and weather

3. **Visual Insights**

<img width="792" height="557" alt="Screenshot 2025-09-09 115231" src="https://github.com/user-attachments/assets/22142425-a9b3-4b45-bad7-7576c9d6118e" />
<img width="1142" height="717" alt="Screenshot 2025-09-09 115303" src="https://github.com/user-attachments/assets/490f38e6-4754-4a6a-9989-84ad21c935d6" />
<img width="1187" height="646" alt="Screenshot 2025-09-09 115925" src="https://github.com/user-attachments/assets/46490726-bcf5-4654-b04f-bc5282fde98a" />
<img width="1545" height="755" alt="Screenshot 2025-09-09 115411" src="https://github.com/user-attachments/assets/7cb4f65a-e697-4594-9be3-2f2b0ceab6ca" />
<img width="1158" height="644" alt="Screenshot 2025-09-09 115956" src="https://github.com/user-attachments/assets/b49ccc11-5088-4c78-9b88-6cc0e5f85597" />
<img width="1229" height="669" alt="Screenshot 2025-09-09 115940" src="https://github.com/user-attachments/assets/9c07f748-ae98-4747-821b-4bcd1706bebe" />
<img width="1128" height="642" alt="Screenshot 2025-09-09 120426" src="https://github.com/user-attachments/assets/c241ba18-aef2-481d-b556-ee47280e3f41" />
<img width="1540" height="720" alt="Screenshot 2025-09-09 120500" src="https://github.com/user-attachments/assets/a1e3bf74-85e8-4746-8499-965aecf054f9" />
<img width="926" height="726" alt="Screenshot 2025-09-09 120926" src="https://github.com/user-attachments/assets/fc98ccfd-07fe-4411-a9b4-332843c36843" />


---

## How to Run the Project

1. **Clone the repository**

```bash
git clone https://github.com/Jiya-2201/SCT_DS_4.git
cd SCT_DS_4
```

2. **Install dependencies**

```bash
pip install pandas matplotlib seaborn jupyter
```

3. **Open the notebook**

```bash
jupyter notebook
```

* Run `notebook/traffic_analysis.ipynb`
* Plots will automatically save to `images/` folder if `plt.savefig()` is used.

4. **Use the sample dataset**

* Notebook points to `data/accidents_sample.csv`.
* Replace with the full dataset if available.

---

## Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization (Matplotlib, Seaborn)
* Python Programming
* Git and GitHub Version Control

---

## Notes

* Large files are ignored in `.gitignore`.
* Future work: Add **machine learning models** to predict accident severity or risk hotspots.
