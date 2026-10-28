# Airbnb Global Performance Dashboard

An end-to-end Power BI dashboard project analyzing global Airbnb listings and performance metrics.

---

## 📊 Overview

This project explores global Airbnb performance with a focus on analytical thinking:
- **Data Modeling & DAX Measures**: Advanced calculated metrics and relational modeling.
- **Pareto Analysis**: Identifying key drivers of revenue and listing distribution.
- **Seasonality & Pricing Trends**: Analyzing seasonal booking patterns and price fluctuations.
- **Trust & Quality Insights**: Host verification, review scores, and guest satisfaction drivers.

---

## 📁 Repository Structure

```text
├── Airbnb Data/
│   ├── Listings.csv                      # Main listings dataset (Git LFS)
│   ├── Listings_data_dictionary.csv      # Metadata / column descriptions
│   ├── Reviews.csv                       # Historical reviews dataset (Git LFS)
│   └── Reviews_data_dictionary.csv       # Reviews metadata
├── AirBnb Logos/                         # Visual assets, branding icons & color palette
│   ├── air bnb logo.png
│   ├── Airbnb.pdf
│   ├── Color Palette.png
│   ├── Dotted Line rectangle.png
│   ├── Magnifying glass.png
│   ├── SHIELD.PNG
│   └── Star.webp
├── Airbnb Global Performance Dashboard.pbix  # Interactive Power BI Dashboard (Git LFS)
├── .gitattributes                        # Git LFS configuration
└── README.md
```

---

## 📥 Dataset Source

Dataset sourced from [Maven Analytics Data Playground - Airbnb Listings & Reviews](https://mavenanalytics.io/data-playground/airbnb-listings-reviews).

---

## 🛠️ Requirements & Git LFS Note

This repository uses **[Git LFS (Large File Storage)](https://git-lfs.com)** for the large `.pbix` and `.csv` files (>100MB).

To clone this repository and download the large files:
```bash
git lfs install
git clone <REPOSITORY_URL>
```
To view the report, open `Airbnb Global Performance Dashboard.pbix` in [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
