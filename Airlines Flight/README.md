# Flight Data Analysis

This project analyzes airline flight data using Python, Pandas, and Matplotlib. The goal is to explore flight patterns, prices, durations, and other key insights from a dataset of airline flights.

## Table of Contents

Project Overview

Dataset

Features

Installation

Usage

Analysis Highlights

Visualization

License

# Project Overview

The project performs exploratory data analysis (EDA) on an airline flight dataset. It includes:

Cleaning and preparing the dataset

Summarizing flight information by airline and route

Identifying fastest, longest, cheapest, and most expensive flights

Visualizing trends in flight classes, departure, and arrival times

# Dataset

The dataset used is a CSV file (airlines_flights_data.csv) containing flight information with the following columns:

airline – Name of the airline company

source_city – Departure city

destination_city – Arrival city

duration – Duration of the flight (minutes)

price – Price of the flight

class – Flight class (Economy, Business, etc.)

departure_time – Scheduled departure time

arrival_time – Scheduled arrival time


# Features

Data Cleaning: Removes unnecessary columns and handles missing values

Aggregate Analysis: Computes sum, average, min, and max of price and duration

Route Analysis: Identifies most and least crowded routes

Airline Insights: Calculates average flight prices per airline and sorts them

Flight Insights: Finds fastest, longest, cheapest, and most expensive flights

Conditional Analysis: Example: Average price for a specific airline, route, and class

# Installation

Clone the repository:

git clone <repository-url>
cd flight-data-analysis


Install required Python packages:

pip install pandas matplotlib

# Usage

Import the required libraries:

import pandas as pd
from pathlib import Path
import matplotlib.pyplot as plt


Load the dataset:

df_flights_raw = pd.read_csv(Path("airlines_flights_data.csv"))
df_flights = df_flights_raw.copy(deep=False)


Perform analysis:

Summarize flight duration and price by airline
df_flights.groupby("airline").sum(numeric_only=True)

Most crowded routes
df_flights.value_counts(["source_city", "destination_city"]).head(3)

Cheapest flight per airline
df_flights.groupby("airline").min()


Visualize data:

df_flights.value_counts("class").plot(kind="bar", xlabel="Class", ylabel="Counts", title="Flight Classes")
plt.show()

# Analysis Highlights

Total and average flight duration and prices

Most and least crowded routes

Fastest and longest flights

Cheapest and most expensive flights per airline

Average flight price for specific airline, route, and class

# Visualization

The project includes the following visualizations:

Flight Classes – Distribution of Economy, Business, etc.

Departure and Arrival Times – Counts of flights at different times

Example:

plt.figure(figsize=(10,5), tight_layout=True)
plt.subplot(1,2,1)
df_flights.value_counts("departure_time").plot(kind="bar", title="Departure Time")
plt.subplot(1,2,2)
df_flights.value_counts("arrival_time").plot(kind="bar", title="Arrival Time")
plt.show()

