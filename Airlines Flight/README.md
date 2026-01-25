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

Note: The dataset should be placed in the path /Users/ershadali/Desktop/DataSets/airlines_flights_data.csv or update the script with your path.

# Features

Data Cleaning: Removes unnecessary columns and handles missing values

Aggregate Analysis: Computes sum, average, min, and max of price and duration

Route Analysis: Identifies most and least crowded routes

Airline Insights: Calculates average flight prices per airline and sorts them

Flight Insights: Finds fastest, longest, cheapest, and most expensive flights

Conditional Analysis: Example: Average price for a specific airline, route, and class
