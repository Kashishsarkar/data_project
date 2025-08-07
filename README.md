#  SmartRide Insights: Divvy Bike Usage Analysis

A data analysis project exploring ride patterns and user behaviors from the Divvy bike-sharing dataset. This Python-based tool automates data cleaning, feature extraction, visualization, and summary reporting to uncover key insights.

---

##  Dataset

**Source:** \[Divvy Trip Data (June 2025)] — included in the repo as `202506-divvy-tripdata.csv`
Due to file size, the dataset and output Excel file are not uploaded. Please request or download separately.
---

##  Objectives

* Analyze ride duration patterns by day, hour, and user type
* Compare behaviors between member and casual riders
* Generate visual and statistical summaries automatically
* Export cleaned data and insights for reporting

---

## ⚙️ Features

 **Data Cleaning**

* Converts timestamps
* Calculates ride duration
* Removes invalid (negative) rides

**Feature Engineering**

* Extracts day of week and hour of ride

 **Visualizations**

* Average ride length by day
* Rides by hour of the day
* Member vs Casual comparison

 **Automated Output**

* Summary text report (`summary_report.txt`)
* Cleaned dataset (`cleaned_divvy_tripdata.xlsx`)

---

##  Example Insights

* Peak usage occurs around **5 PM** on **Saturdays**
* **Casual riders** take **30% longer rides** than members
* **Wednesday** has the shortest average ride duration

---

##  How to Run

1. Clone this repo:

```bash
git clone https://github.com/Kashishsarkar/data_project.git
```

2. Install requirements:

```bash
pip install pandas matplotlib seaborn openpyxl
```

3. Run the script:

```bash
python data_project.py
```

4. Outputs will be saved in your current directory.

---

##  Files

| File                          | Description                |
| ----------------------------- | -------------------------- |
| `202506-divvy-tripdata.csv`   | Original dataset           |
| `data_project.py`             | Core analysis script       |
| `cleaned_divvy_tripdata.xlsx` | Exported cleaned data      |
| `summary_report.txt`          | Key insights from analysis |

---

##  Author

**Kashish Sarkar**
📧 [kashishsrkr82@gmail.com](mailto:kashishsrkr82@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/kashish-sarkar-778a41265/)
💻 [GitHub](https://github.com/Kashishsarkar)

---

##  Future Add-ons

* Correlation heatmaps
* Ride duration prediction (ML)
* Dashboard or GUI in local version

---

>  *“Turning messy Excel data into clean, visual insight — one ride at a time.”*

