# 🍽️ Zomato Bengaluru — Deep Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat&logo=pandas)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat)

> A comprehensive, end-to-end Exploratory Data Analysis of **51,000+ restaurants** listed on Zomato across Bengaluru — uncovering patterns in cuisine preferences, pricing, ratings, location density, and delivery behaviour.

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Business Questions](#-business-questions)
- [Dataset](#-dataset)
- [Repository Structure](#-repository-structure)
- [Tech Stack](#-tech-stack)
- [Key Insights](#-key-insights)
- [Getting Started](#-getting-started)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🔍 Project Overview

Bengaluru is India's IT capital — a city where a significant portion of the working population relies on restaurants for daily meals. With Zomato being the dominant food discovery and delivery platform, this dataset offers a rich lens into the city's food culture.

This project goes beyond surface-level analysis. It performs a **deep, multi-layered EDA** aimed at answering real business questions — from understanding which neighborhoods are food hotspots to uncovering what drives high ratings.

**Target audience:** Data Scientists, Analysts, and Food-Tech enthusiasts looking for a structured EDA reference on a messy, real-world dataset.

---

## ❓ Business Questions

This analysis is structured around the following core questions:

1. **Location** — Which localities in Bengaluru have the highest restaurant density?
2. **Cuisines** — What are the most popular cuisine types across different neighborhoods?
3. **Ratings** — What factors (price, cuisine, online ordering) correlate most with high ratings?
4. **Cost** — How does the approximate cost for two people vary across location and cuisine?
5. **Online Ordering & Table Booking** — How do delivery options affect votes and ratings?
6. **Restaurant Types** — What types of establishments (Casual Dining, Café, QSR) dominate Bengaluru?
7. **Competition** — Which cuisines and localities are most saturated?

---

## 📦 Dataset

| Property | Details |
|---|---|
| **Source** | [Kaggle — Zomato Bangalore Restaurants](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants) |
| **Records** | ~51,000 restaurants |
| **File** | `input_data/zomato.csv` (stored via Git LFS) |
| **Size** | ~500 MB |

### Key Columns

| Column | Description |
|---|---|
| `name` | Restaurant name |
| `location` | Neighbourhood in Bengaluru |
| `rate` | Aggregate rating out of 5 |
| `votes` | Total number of user votes |
| `approx_cost(for two people)` | Approximate cost for two diners |
| `online_order` | Whether online ordering is available |
| `book_table` | Whether table booking is available |
| `cuisines` | Cuisine types served |
| `listed_in(type)` | Restaurant category (Buffet, Café, etc.) |
| `listed_in(city)` | Area of the city |

> **Note:** The dataset file is tracked with **Git LFS** due to its size. Ensure you have [Git LFS installed](https://git-lfs.com/) before cloning.

---

## 📁 Repository Structure

```
Zomato-Bengaluru-EDA/
│
├── input_data/
│   └── zomato.csv              # Raw dataset (Git LFS tracked)
│
├── notebooks/
│   └── zomato_eda.ipynb        # Main EDA notebook
│
├── .gitattributes              # Git LFS configuration
└── README.md
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Python 3.10+** | Core language |
| **Pandas** | Data loading, cleaning, manipulation |
| **NumPy** | Numerical operations |
| **Matplotlib** | Static visualisations |
| **Seaborn** | Statistical plots |
| **Plotly** | Interactive visualisations |
| **Jupyter Notebook** | Analysis environment |

---

## 💡 Key Insights

> *(To be updated as analysis progresses)*

- 📍 **BTM, Koramangala, and Indiranagar** are the top 3 highest-density restaurant neighborhoods
- 🍕 **North Indian and Chinese** cuisines dominate across the city
- ⭐ Restaurants offering **online ordering** tend to accumulate significantly more votes
- 💰 Higher price range does **not** consistently correlate with higher ratings
- 🏪 **Quick Bites** is the most common restaurant type listed on the platform

---

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- Git with [Git LFS](https://git-lfs.com/) installed

### Installation

```bash
# 1. Clone the repository (Git LFS required for the dataset)
git lfs install
git clone https://github.com/Shivang20303/Zomato-Bengaluru-EDA.git
cd Zomato-Bengaluru-EDA

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn plotly jupyter

# 3. Launch the notebook
jupyter notebook notebooks/
```

---

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome. Feel free to open an issue or submit a pull request.

---
