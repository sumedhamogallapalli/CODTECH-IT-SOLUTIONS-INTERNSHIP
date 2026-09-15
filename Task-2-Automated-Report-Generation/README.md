# CODTECH IT SOLUTIONS — Task 1: Weather Analytics Dashboard 🌦️

A Python-based weather analytics application developed as part of my **CODTECH IT SOLUTIONS Internship**.

The project retrieves real-time weather forecast data from the **OpenWeatherMap API** and generates a comprehensive visualization dashboard to analyze temperature, humidity, wind speed, and atmospheric conditions.

---

## 📌 Project Overview

The objective of this project is to build a Python-based tool that collects weather forecast data for a selected city and transforms the data into meaningful visual insights.

The application retrieves a **5-day / 3-hour weather forecast** and generates four analytical visualizations covering:

- 🌡️ Temperature trends
- 💧 Humidity levels
- 💨 Wind speed
- ☁️ Atmospheric conditions

The project also exports the collected weather data to a CSV file for further analysis.

---

## 🎯 Objectives

- Fetch weather forecast data using a public API.
- Process and organize weather data using Pandas.
- Analyze temperature, humidity, wind, and weather conditions.
- Generate a visual weather analytics dashboard.
- Export raw weather data to a CSV file.
- Implement error handling for reliable execution.

---

## 🛠️ Technology Stack

### Programming Language

- **Python 3.x**

### API

- **OpenWeatherMap API**
- 5-Day / 3-Hour Forecast

### Libraries

- **Requests** — Handles HTTP requests and retrieves weather data from the API.
- **Pandas** — Used for data manipulation, cleaning, and CSV export.
- **Matplotlib** — Used for creating analytical plots and dashboard layout.
- **Seaborn** — Used for statistical visualization and styling.

---

## ✨ Key Features

- 🌦️ Real-time weather forecast data retrieval
- 📊 Four analytical weather charts
- 🌡️ Temperature trend analysis
- 💧 Humidity analysis
- 💨 Wind speed analysis
- ☁️ Atmospheric condition analysis
- 📁 Weather data export to CSV
- 🛡️ Error handling for API and data-related issues
- 📈 High-resolution dashboard output

---

## 📦 Key Deliverables

### 1. Python Script

An object-oriented Python application that retrieves, processes, and analyzes weather data with appropriate error handling.

### 2. Weather Analytics Dashboard

A high-resolution PNG dashboard containing four analytical charts.

### 3. Weather Data Export

A CSV file containing the collected weather forecast data for further analysis.

---

## 📊 Dashboard Insights — Nellore City

The generated dashboard was analyzed using weather data for **Nellore**.

### 🌡️ Temperature Trends

The temperature reached approximately **41°C** at its peak, while nighttime temperatures dropped to around **25°C**, showing a clear variation throughout the day.

### ☁️ Atmospheric Conditions

The weather conditions were predominantly stable, with approximately:

- **62.5% Clear skies**
- **37.5% Cloud cover**

### 💧 Humidity

Humidity levels showed significant variation:

- Maximum: approximately **85%**
- Minimum: approximately **15%**

Higher humidity levels were observed during early morning hours, while lower levels occurred during peak heat periods.

### 💨 Wind Dynamics

Wind speeds remained moderate, with peak gusts reaching approximately **9 m/s**.

---

## 🔄 Project Workflow

```text
OpenWeatherMap API
        ↓
Weather Forecast Data
        ↓
Python Requests
        ↓
Data Processing using Pandas
        ↓
Weather Data Analysis
        ↓
Matplotlib + Seaborn
        ↓
Weather Analytics Dashboard
        ↓
CSV Data Export
