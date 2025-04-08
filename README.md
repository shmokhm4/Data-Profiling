# 🏨 Riyadh Hotels Data Profiling

This repository contains a data profiling and visualization notebook that explores a dataset of hotel listings in Riyadh, Saudi Arabia. The goal is to perform an exploratory data analysis (EDA), identify missing or duplicated values, and visualize key insights about hotel prices, ratings, and more.

> 🔗 **Original Notebook**: [View on Google Colab](https://colab.research.google.com/drive/1L1azr0Mkoytzr2E45uVNbiaPBuVgly4z?usp=sharing)

---

## 📊 About the Dataset

This dataset provides detailed information on hotels located in Riyadh — a major hub for business, tourism, and religious travelers. It was sourced from leading travel platforms such as Booking.com, Hotels.com, Expedia, Agoda.com, and Trip.com. The dataset reflects hotel bookings for the upcoming **two months**, offering a short-term perspective on the market.

**Dataset Author**: Mohammed Alsubaie  
**Last Updated**: 4 months ago

### 🧾 Metadata Overview

| Column       | Description |
|--------------|-------------|
| `hotel_id`   | Unique identifier for each hotel |
| `hotel_name` | Hotel name (includes branding or location) |
| `SOURCE`     | Booking platform where the data was sourced |
| `price`      | Final price paid by customers (includes fees) |
| `base_price` | Base price before taxes or charges |
| `checkIn`    | Check-in date |
| `checkOut`   | Check-out date |
| `count`      | Number of reviews |
| `rating`     | Customer rating (e.g., stars) |
| `Info`       | Additional hotel information (e.g., amenities) |
| `latitude`   | Hotel's geographic latitude |
| `longitude`  | Hotel's geographic longitude |

---

## 🚀 What’s Included

- **Data Loading & Exploration**
  - Reading from `.csv` and `.xlsx` files
  - Summary statistics, data types, missing values, and unique counts
- **Data Cleaning**
  - Missing value analysis
  - Duplicate row identification
- **Visualization**
  - Null vs. Non-null values
  - Data type distributions
  - Hotel counts by platform
  - Average prices by rating
- **Interactive Visualizations (Plotly)**
  - Scatter plots: Rating vs. Price
  - Box plots: Price by Source
  - Line chart: Price trends over check-in dates
  - Pie chart: Distribution of hotel ratings
  - Bar chart: Average prices by rating

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- Google Colab
- Data sources: Excel files

