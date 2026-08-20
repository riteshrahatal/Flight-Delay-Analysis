# ✈️ Flight Delay Analysis – US Domestic Flights (2024)

## 📌 Project Overview

This project analyzes the **2024 US domestic flight performance dataset** to identify patterns, trends, and key factors contributing to flight delays.

The dataset contains detailed operational information including scheduled and actual departure/arrival times, delay duration, taxi times, cancellations, diversions, flight distance, and different delay causes.

The data covers airline operations across **airlines, airports, routes, and time periods** throughout 2024.

---

## 📊 Dataset Information

| Feature | Details |
|---|---|
| Dataset | 2024 US Domestic Flight Performance |
| Rows | 7+ Million |
| Columns | 35 |
| Country | United States |
| Year | 2024 |
| Source | Bureau of Transportation Statistics (BTS) |
| Data Platform | BTS TranStats |

### 📂 Data Source

The dataset is sourced from the **Bureau of Transportation Statistics (BTS) TranStats** monthly US flight records and combined into a single dataset covering the full year of 2024.

**Source:** [BTS TranStats](https://www.transtats.bts.gov/)

---

## ✈️ Dataset Features

The dataset contains information related to:

- **Flight Information** – Airline, flight number, origin, destination, and route
- **Scheduled Times** – Scheduled departure and arrival times
- **Actual Times** – Actual departure and arrival times
- **Departure Delays** – Delay duration and delay indicators
- **Arrival Delays** – Arrival delay duration and delay indicators
- **Taxi Times** – Taxi-out and taxi-in duration
- **Cancellations** – Flight cancellation information and reasons
- **Diversions** – Information about diverted flights
- **Distance** – Flight distance
- **Delay Causes** – Carrier, weather, NAS, security, and late aircraft delays

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze flight delay trends throughout 2024
- Compare delay performance across airlines
- Identify airports with the highest delay rates
- Analyze delays based on time of day
- Identify seasonal patterns in flight delays
- Understand the major causes of flight delays
- Identify unreliable and high-risk routes
- Analyze cancellation and diversion patterns
- Evaluate operational efficiency across airlines and airports
- Generate actionable insights for airlines, airports, and passengers

---

## 🔍 Key Areas of Analysis

### 🛫 Airline Performance

- Compare total flights operated by each airline
- Calculate airline-wise delay rates
- Identify airlines with the highest average delays
- Compare cancellation and diversion rates
- Evaluate overall airline operational performance

### 🏢 Airport Analysis

- Identify airports with the highest number of delays
- Compare departure and arrival delay rates
- Analyze airport-level operational performance
- Identify airports with consistently high delays

### 🕐 Time-Based Analysis

- Analyze delays by hour of the day
- Identify peak delay periods
- Compare weekday and weekend delay patterns
- Analyze monthly flight delay trends

### 🌦️ Delay Cause Analysis

The project analyzes the contribution of different delay causes:

- **Carrier Delay**
- **Weather Delay**
- **NAS Delay**
- **Security Delay**
- **Late Aircraft Delay**

This helps identify the major factors responsible for flight delays.

### 🛣️ Route Analysis

- Identify routes with the highest delay rates
- Find frequently delayed origin-destination pairs
- Analyze route reliability
- Identify high-risk routes based on delay frequency and duration

### ❌ Cancellation & Diversion Analysis

- Analyze cancellation trends
- Identify major cancellation reasons
- Compare cancellation rates across airlines
- Analyze flight diversion patterns

---

## 📈 Key Questions

This analysis aims to answer questions such as:

1. Which airlines have the highest delay rates?
2. Which airports experience the most delays?
3. What time of day has the highest probability of delays?
4. Which months have the worst delay patterns?
5. What are the major causes of flight delays?
6. Which routes are the least reliable?
7. Which airlines have the highest cancellation rates?
8. How frequently are flights diverted?
9. What factors contribute most to operational delays?
10. How can airlines and airports improve operational efficiency?

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📁 Project Structure

```text
Flight-Delay-Analysis/
│
├── flight_delay_2024.csv
├── Flight_Delay_Analysis.ipynb
├── README.md
└── images/
    └── visualizations/
