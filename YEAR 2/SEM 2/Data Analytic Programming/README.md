# 📊 Data Analytic Programming

**SECP3233 — Data Analytic Programming | Semester II 2024/2025**  
Faculty of Computing, Universiti Teknologi Malaysia

---

## 👤 Student

| | |
|---|---|
| **Name** | Afif Shaqir Irfan bin Arqam |
| **Matric No.** | A23CS0204 |
| **Year / Semester** | Year 2 · Semester 2 |

---

## 📌 Assignments

### ✅ Assignment 1 — Python Fundamentals: Ride-Sharing Data Analysis

**Dataset:** QuickRide — a fictional ride-sharing platform  
**Dataset Fields:** `ride_id`, `driver_name`, `rider_name`, `city`, `distance`, `duration`, `fare`

**Skills Covered:**

- File I/O — reading and writing CSV and text files
- Data structures — lists, tuples, dictionaries
- Functions and lambda expressions
- Sorting and slicing

**Tasks Completed:**

| No. | Task | Marks |
|-----|------|-------|
| Q1 | Save ride data to `ride.csv` using File I/O | 3 |
| Q2 | Read and parse `ride.csv` using `csv.DictReader` | 8 |
| Q3 | Compute average fare by city | 10 |
| Q4 | Summarize driver info (rides, distance, fare) | 10 |
| Q5 | Analyse peak ride slice between given indices | 10 |
| Q6 | Use lambda to find top 3 drivers by total fare | 7 |
| Q7 | Compute average duration by city and sort with lambda | 10 |
| Q8 | Write driver summary to `driver_summary.txt` | 10 |

---

### ✅ Assignment 3 — Pandas & Matplotlib: Rainfall Data Analysis

**Dataset:** Monthly rainfall measurements from weather stations across regions  
**Dataset Fields:** `Region`, `Year`, `Month`, `Station`, `Rainfall_mm`, `RainyDays`, `MaxTemp_C`, `MinTemp_C`, `UrbanRural`

**Skills Covered:**

- Pandas — `groupby`, `agg`, missing value handling, summary statistics
- Matplotlib — bar charts, grouped bar charts, line plots, boxplots, scatter plots
- Seaborn & NumPy

**Parts Completed:**

**Part 1 — Data Exploration (15 marks)**
- Loaded `Rainfall.csv` into a Pandas DataFrame
- Displayed first 5 rows and handled missing values
- Generated summary statistics for all numeric columns

**Part 2 — Grouping & Aggregation (30 marks)**
- Per station: total rainfall, average rainy days, avg max/min temperature
- Per Region & UrbanRural: average rainfall, max temp, rainy days
- Per Month & Region: total, mean, min, max rainfall
- Identified region and month with highest recorded rainfall
- Per Year & UrbanRural: average, min, max rainfall
- Per Region: average monthly temperature range (MaxTemp − MinTemp)

**Part 3 — Data Visualisation (40 marks)**
- **Bar Chart** — Total rainfall by region, coloured by Urban/Rural
- **Grouped Bar Chart** — Average monthly rainfall per station
- **Line Plot** — Rainfall trend over months for selected stations, with peak month highlighted
- **Boxplot** — Rainfall distribution by region and Urban/Rural with custom colours
- **Scatter Plot** — Rainfall vs maximum temperature, coloured by region

---

## 🛠️ Tools & Libraries

`Python` · `Pandas` · `Matplotlib` · `Seaborn` · `NumPy` · `csv` · `File I/O`

---

## 💭 Reflection

Data Analytic Programming was the course where Python stopped feeling like something I was learning and started feeling like something I actually used. Assignment 1 built my understanding of how Python's core structures — lists, dictionaries, functions, and file I/O — work together in a real workflow. Writing functions to process a ride-sharing dataset, then sorting and writing the results to a file, made the language feel practical rather than theoretical.

Assignment 3 pushed that further with Pandas and Matplotlib. Working with a multi-column rainfall dataset across regions, stations, years, and urban/rural categories taught me how `groupby` and `agg` can answer complex questions in just a few lines. The visualisation part was equally valuable — learning which chart type fits which question (bar for comparisons, line for trends, box for distributions, scatter for relationships) is a skill I now apply instinctively.

Overall this subject gave me the analytical Python foundation that directly supported everything I did in the HPDP and SECP3843 courses later on.

---

## 📂 Folder Contents

```
📁 Data Analytic Programming/
├── 📄 README.md
├── 📓 Assignment1_SECP3233.ipynb     ← Ride-sharing data analysis
├── 📓 Assignment3_SECP3233.ipynb     ← Rainfall data analysis
└── 📁 datasets/
    ├── ride.csv
    ├── driver_summary.txt
    └── Rainfall.csv
```

---

<div align="center">

**Afif Shaqir Irfan bin Arqam** · A23CS0204  
[🌐 E-Portfolio](https://afifshaqir.github.io/afifshaqir.github.ios/) · [🐙 GitHub](https://github.com/afifshaqir)

</div>

