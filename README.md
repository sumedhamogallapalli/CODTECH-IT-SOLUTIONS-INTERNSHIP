# CODTECH IT SOLUTIONS - INTERNSHIP TASK 1
## Weather Analytics Dashboard 🌦️

### **Project Overview**
This project was developed as part of the CODTECH IT SOLUTIONS Internship. The goal was to build a Python-based tool that fetches real-time weather data from a public API and creates a comprehensive visualization dashboard.

The application retrieves a 5-day / 3-hour forecast for a specific city and generates four distinct visual reports to analyze trends in temperature, humidity, wind speed, and atmospheric conditions.

---

### **Technology Stack**
*   **Language:** Python 3.x
*   **API:** [OpenWeatherMap API](https://openweathermap.org/) (5-Day / 3-Hour Forecast)
*   **Libraries:**
    *   `Requests`: For handling HTTP requests to the API.
    *   `Pandas`: For data manipulation and cleaning.
    *   `Matplotlib`: For core plotting and dashboard layout.
    *   `Seaborn`: For high-level statistical visualization and styling.

---

### **Key Deliverables**
1.  **Python Script:** An OOP-based robust script with error handling.
2.  **Weather Dashboard:** A high-resolution PNG image containing 4 analytical charts.
3.  **Data Export:** A CSV file containing the raw weather data for further analysis.

---

### **Dashboard Insights (Nellore City Analysis)**
Based on the generated dashboard for **Nellore**, the following observations were made:
*   **Temperature Trends:** The city experiences significant heat, with peak temperatures reaching approximately **41°C**. There is a clear diurnal cycle with night temperatures dropping to around 25°C.
*   **Atmospheric Conditions:** The weather is predominantly stable, with **62.5% Clear skies** and 37.5% Cloud cover.
*   **Humidity Saturation:** Humidity levels show high volatility, peaking near **85%** during early morning hours and dropping as low as **15%** during peak heat hours.
*   **Wind Dynamics:** Wind speeds are moderate, with peak gusts reaching approximately **9 m/s**.

---

### **How to Run**
1. Clone this repository.
2. Install dependencies:  
   `pip install requests pandas matplotlib seaborn`
3. Replace the `API_KEY` variable in the script with your OpenWeatherMap API key.
4. Run the script:  
   `python task1_weather.py`

---

**Intern Information:**
*   **Name:** M.Sumedha
*   **ID:** CTIS8362
*   **Domain:** Python Programming
*   **Batch:** 15 April 2026 - 10 June 2026
