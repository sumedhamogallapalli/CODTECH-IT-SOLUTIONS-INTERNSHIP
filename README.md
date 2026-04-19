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

# **Task 2: Automated Report Generation 📊**

### **Project Overview**
The objective of this task was to develop a Python script that automates the process of data analysis and generates a formal, formatted PDF report. This simulates a real-world business scenario where raw data needs to be converted into an executive summary for decision-making.

### **Key Features**
*   **Automated Data Processing:** Reads raw sales data from a CSV file using `Pandas`.
*   **Statistical Analysis:** Automatically calculates Total Revenue, Average Sales, and identifies Top-performing products.
*   **Professional PDF Layout:** Built using the `FPDF` library, featuring:
    *   A corporate header and footer with page numbering.
    *   Cleanly formatted data tables.
    *   A "Smart Layout" system that prevents orphaned headings and manages page breaks.
*   **Integrated Visualization:** Embeds high-resolution charts generated via `Matplotlib` directly into the PDF.

### **Tech Stack**
*   **Pandas:** Data manipulation and analysis.
*   **Matplotlib:** Scientific data visualization.
*   **FPDF:** PDF document generation and formatting.

### **Insights from Sample Report**
*   The generated report analyzes 6 product categories.
*   **Mobiles** were identified as the highest revenue generator ($72,000).
*   Total sales revenue across all categories amounted to **$186,500**.

---

**Intern Information:**
*   **Name:** M.Sumedha
*   **ID:** CTIS8362
*   **Domain:** Python Programming
*   **Batch:** 15 April 2026 - 10 June 2026
