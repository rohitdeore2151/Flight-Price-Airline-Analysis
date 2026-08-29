# ✈️ Flight Price & Airline Analysis

## 📌 Project Overview

This project analyzes flight ticket prices and identifies the major factors that influence airline ticket pricing. The analysis focuses on airlines, routes, flight duration, number of stops, and departure timing.

## 🎯 Problem Statement

Analyze flight listings to understand how airline, route, departure time, duration, and number of stops influence ticket prices.

## 📊 Dataset

The dataset contains the following information:

* Airline
* Date of Journey
* Source
* Destination
* Route
* Departure Time
* Arrival Time
* Duration
* Total Stops
* Additional Information
* Price

## 🧹 Data Cleaning

The following steps were performed:

* Removed duplicate records
* Checked and handled missing values
* Converted the journey date into datetime format
* Extracted journey day and month
* Extracted departure hour and minute
* Created departure time categories
* Extracted hours and minutes from flight duration
* Converted duration into total minutes
* Converted total stops into numerical values
* Created route names
* Created flight type categories

## 🔧 Feature Engineering

New features created:

* Journey_Day
* Journey_Month
* Departure_Hour
* Departure_Minute
* Departure_Category
* Duration_Hours
* Duration_Minutes
* Duration_Total_Minutes
* Stops_Count
* Route_Name
* Flight_Type

## 📈 Exploratory Data Analysis

The following questions were analyzed:

1. Which airline has the highest average price?
2. Are connecting flights more expensive than non-stop flights?
3. Which routes are the most expensive?
4. Does flight duration affect ticket price?
5. Which departure times have higher ticket prices?

## 🔍 Key Findings

### ✈️ Airline Analysis

Jet Airways Business had the highest average ticket price at approximately ₹58,358.67.

### 🔄 Flight Type Analysis

Connecting flights had an average ticket price of approximately ₹11,020.32, while non-stop flights had an average price of approximately ₹5,018.51.

### 🗺️ Route Analysis

Banglore → New Delhi was the most expensive route, with an average ticket price of approximately ₹12,007.42.

### ⏱️ Duration Analysis

Flight duration had a moderate positive correlation of approximately **0.50** with ticket price.

### 🌅 Departure Time Analysis

Afternoon flights had the highest average ticket price at approximately ₹9,176.26.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🚀 How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open Jupyter Notebook:

```bash
jupyter notebook
```

Run the project notebook:

```text
Flight_Price_Analysis.ipynb
```

## 📁 Project Files

```text
Flight-Price-Airline-Analysis/
│
├── Flight_Price_Analysis.ipynb
├── Flight_Price_Cleaned_Final.csv
├── README.md
└── requirements.txt
```

## 📌 Conclusion

The analysis shows that flight ticket prices are influenced by multiple factors, including airline, route, number of stops, flight duration, and departure timing.
