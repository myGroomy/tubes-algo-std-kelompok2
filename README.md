# Formula 1 Modern Era — Exploratory Data Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-✓-150458?style=flat&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-✓-013243?style=flat&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Seaborn-✓-4E9B9B?style=flat" alt="Seaborn">
  <img src="https://img.shields.io/badge/Matplotlib-✓-11557C?style=flat&logo=matplotlib&logoColor=white" alt="Matplotlib">
  <img src="https://img.shields.io/badge/status-completed-brightgreen" alt="Status">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
</p>

---

## Project Overview

This project was developed as the final assignment for the **Logic & Algorithms** and **Data Structures** courses.

The objective is to perform an **Exploratory Data Analysis (EDA)** on Formula 1 datasets from the modern era to identify trends, patterns, and insights regarding drivers, constructors, races, and championship performance.

The project demonstrates the implementation of algorithmic thinking, data structures, and data analysis techniques using Python.

---

## Objectives

- Understand the characteristics of Formula 1 modern-era datasets
- Apply data preprocessing techniques
- Perform exploratory data analysis (EDA)
- Visualize meaningful insights from racing data
- Implement programming concepts from Logic & Algorithms and Data Structures

---

## Dataset

**Source:** [Formula 1 Modern Era Dataset](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020) (Kaggle)

| File | Description |
|------|-------------|
| `drivers.csv` | Driver information |
| `constructors.csv` | Constructor (team) information |
| `races.csv` | Grand Prix race information |
| `results.csv` | Race results |
| `qualifying.csv` | Qualifying session results |
| `lap_times.csv` | Lap time data |
| `pit_stops.csv` | Pit stop data |
| `circuits.csv` | Circuit information |
| `driver_standings.csv` | Driver championship standings |
| `constructor_standings.csv` | Constructor championship standings |
| `constructor_results.csv` | Constructor race results |
| `sprint_results.csv` | Sprint race results |
| `seasons.csv` | Season information |
| `status.csv` | Race status codes |

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python** | Primary programming language |
| **Google Colab** | Development environment |
| **Pandas** | Data manipulation & analysis |
| **NumPy** | Numerical computing |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical data visualization |

---

## Exploratory Data Analysis

The analysis covers the following aspects:

- **Data Cleaning** — handling missing values, data type conversion
- **Missing Value Analysis** — identifying and treating null values
- **Duplicate Checking** — detecting duplicate records
- **Descriptive Statistics** — summary statistics of numerical features
- **Driver Performance Analysis** — win rates, podium finishes, points distribution
- **Constructor Performance Analysis** — team dominance, constructor standings trends
- **Championship Trends** — championship evolution over seasons
- **Race Win Distribution** — frequency distribution of race winners
- **Pole Position Analysis** — pole position to win conversion rates
- **Circuit Analysis** — track characteristics and race statistics
- **Correlation Analysis** — relationships between variables
- **Data Visualization** — comprehensive charts and plots

---

## Repository Structure

```
├── code/
│   ├── TUBES_OOP_FINAL.ipynb     # Object-Oriented Programming implementation
│   └── TUBES_STD_FINAL.ipynb     # Data Structures implementation
├── dataset/
│   └── raw/
│       ├── circuits.csv
│       ├── constructor_results.csv
│       ├── constructor_standings.csv
│       ├── constructors.csv
│       ├── driver_standings.csv
│       ├── drivers.csv
│       ├── lap_times.csv
│       ├── pit_stops.csv
│       ├── qualifying.csv
│       ├── races.csv
│       ├── results.csv
│       ├── seasons.csv
│       ├── sprint_results.csv
│       └── status.csv
├── README.md
└── CONTRIBUTOR.md.txt
```

---

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or Google Colab

### Installation

```bash
# Clone the repository
git clone https://github.com/myGroomy/tubes-algo-std-kelompok2.git

# Navigate to the project directory
cd tubes-algo-std-kelompok2

# Install required packages
pip install pandas numpy matplotlib seaborn
```

Open the notebooks in `code/` using Google Colab or Jupyter Notebook.

---

## Contributors

- **Taufik Alwan** - [@myGroomy](https://github.com/myGroomy)

---

## License

This project is licensed under the MIT License.
