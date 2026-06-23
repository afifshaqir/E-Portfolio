# ⚡ High Performance Data Processing

**Semester II 2025/2026 | Universiti Teknologi Malaysia**  
Faculty of Computing

---

## 👤 Student

| | |
|---|---|
| **Name** | Afif Shaqir Irfan bin Arqam |
| **Matric No.** | A23CS0204 |

---

## 📌 Project 1 — Carousell Malaysia Data Pipeline & HPC Benchmarking

### Overview

Carousell Malaysia is a large dynamic marketplace platform with hundreds of thousands of public listings across categories like electronics, fashion, beauty, and cameras. This project builds a complete end-to-end data pipeline — from web crawling to high-performance processing — and benchmarks four different processing tools on the same dataset.

**200,000+ raw records** were collected and processed through a three-stage pipeline.

---

## 🏗️ System Architecture

The system is designed as a **five-layer architecture**:

| Layer | Component |
|-------|-----------|
| Network & Presentation | Carousell Malaysia (data source) |
| Application | Multithreaded web crawler (Selenium + BeautifulSoup4) |
| Storage & Integration | Pandas-based data cleaning pipeline |
| Processing & Computation | Benchmarking: Pandas, Multiprocessing, Polars, PySpark |
| Results | Performance dashboards, charts, analytical reports |

---

## 🔄 Pipeline Stages

### Stage 1 — Data Collection

Built a **multithreaded web crawler** to handle Carousell's JavaScript-rendered dynamic pages:

- **Selenium WebDriver** + **undetected ChromeDriver** to bypass bot detection
- **ThreadPoolExecutor** runs multiple Chrome sessions concurrently
- **BeautifulSoup4** + **lxml** parse rendered HTML to extract structured listing data
- Round-robin URL distribution across 200 category/subcategory URLs
- Threading locks prevent race conditions on shared resources
- Records saved progressively to `raw_data.csv` to prevent data loss

**Data fields collected:** product title, price, location, category, seller info, timestamps

### Stage 2 — Data Cleaning & Processing

Pandas-based cleaning pipeline applied to `raw_data.csv`:

- Duplicate removal
- Price normalization (text strings → numeric)
- Missing value handling
- Text standardization
- Timestamp parsing (relative times → actual dates)
- Output saved as `cleaned_data.csv`

### Stage 3 — Optimization & Benchmarking

Four processing frameworks benchmarked **head-to-head** on identical tasks:

| Tool | Type |
|------|------|
| **Pandas** | Single-threaded DataFrame processing |
| **Python Multiprocessing** | Parallel CPU processing |
| **Polars** | High-performance Rust-backed DataFrame |
| **PySpark** | Distributed big data processing |

**Operations benchmarked:**
- Category Summary
- Find Popular Listings
- Top 10 per Category
- Keyword Search
- Add Seller Stats

**Metrics tracked:**
- Execution time
- Records processed per second
- Peak memory usage
- CPU utilisation

---

## 🛠️ Tools & Technologies

`Python` · `Selenium WebDriver` · `BeautifulSoup4` · `Pandas` · `Polars` · `PySpark` · `Python Multiprocessing` · `ThreadPoolExecutor` · `lxml`

---

## 💭 Reflection

This project was the most technically challenging thing I built this semester. Web crawling a JavaScript-rendered site like Carousell required solving problems I had not encountered before — bot detection, dynamic scrolling, concurrent sessions, and race conditions in shared memory. Getting the crawler to collect over 200,000 records reliably was a major milestone.

The benchmarking stage was equally eye-opening. Comparing Pandas, Multiprocessing, Polars, and PySpark on the same operations with hard numbers — execution time, memory, CPU — made the differences between tools concrete rather than theoretical. It changed how I think about tool selection: the right choice depends on data size, hardware, and the specific operation, not just reputation. This project gave me a realistic appreciation of what "high performance" actually means in practice.

---

## 📂 Folder Contents

```
📁 High Performance Data Processing/
├── 📄 README.md
├── 📄 Project_1_HPDP.pdf          ← Full project report
├── 📁 crawler/                     ← Web crawling scripts
├── 📁 cleaning/                    ← Data cleaning pipeline
├── 📁 benchmarking/                ← Benchmarking code & results
└── 📁 data/
    ├── raw_data.csv
    └── cleaned_data.csv
```

---

<div align="center">

**Afif Shaqir Irfan bin Arqam** · A23CS0204  
[🌐 E-Portfolio](https://afifshaqir.github.io/afifshaqir.github.ios/) · [🐙 GitHub](https://github.com/afifshaqir)

</div>

