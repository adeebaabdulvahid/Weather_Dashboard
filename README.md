# 🌦️ Weather Report Dashboard – Power BI

## 📌 Project Overview

This project is an interactive **Weather Report Dashboard** created using **Microsoft Power BI**.

The dashboard presents weather information in a clear and interactive format, including current weather conditions, temperature, humidity, wind, visibility, UV index, rainfall, location information, and forecast details.

The project also includes data transformation, data modeling, DAX measures, custom visuals, weather icons, and dashboard formatting.

---

## 🛠️ Tools & Technologies

* Microsoft Power BI
* Power Query
* DAX
* Data Modeling
* Data Visualization
* Weather Data
* GitHub

---

## 📂 Data Tables

The Power BI report contains multiple tables used for analysis and visualization:

* **CURRENT** – Contains current weather information.
* **FORECAST_DAY** – Contains daily weather forecast information.
* **Locations** – Contains location-related information.
* **Measure** – Contains the DAX measures created for the dashboard.

---

## 🔄 Data Preparation

The data was prepared and transformed using **Power Query**.

The main data preparation steps included:

* Loading the weather dataset into Power BI.
* Reviewing the available tables and columns.
* Checking and correcting data types.
* Preparing location and weather-related fields.
* Organizing the data for dashboard visualization.
* Creating calculated measures using DAX.
* Preparing date and weather fields for displaying current and forecast information.

---

## 📊 DAX Measures

Several DAX measures were created to make the dashboard dynamic.

One of the measures used to display the latest update date is:

```DAX
Last_Updated_Date_Curr =
MAX('CURRENT'[current.last_updated])
```

The measure is used to dynamically display when the weather information was last updated.

---

## 📈 Dashboard Visualizations

The dashboard contains multiple visuals to present weather information in an easy-to-understand format.

### Current Weather

The dashboard displays information such as:

* 🌡️ Temperature
* 💧 Humidity
* 💨 Wind
* 👁️ Visibility
* ☀️ UV Index
* 🌧️ Rainfall
* 📍 Location
* 🕒 Last Updated Date

### Forecast

Forecast information is presented using visual elements that make it easier to understand upcoming weather conditions.

### Weather Icons

Custom weather-related icons were incorporated into the dashboard to improve visual presentation and make the information easier to identify.

Icons were used for information such as:

* Location
* Humidity
* Visibility
* UV Index
* Wind
* Temperature
* Rain

---

## 🎨 Dashboard Design

The dashboard was designed with a clean and user-friendly layout.

Design work included:

* Cards for important weather values
* Dynamic date display
* Weather icons
* Shapes and text elements
* Consistent spacing and alignment
* Background formatting
* Interactive Power BI visuals
* Organized sections for current weather and forecast information

---

## 🔍 Key Features

* Interactive weather dashboard
* Current weather information
* Forecast information
* Dynamic last-updated date
* Weather icons
* DAX-based calculations
* Power Query data transformation
* Structured data model
* User-friendly dashboard layout

---

## 📁 Project Files

The main project file is:

```text
weather report.pbix
```

---

## 🚀 How to Use

1. Download the `.pbix` file.
2. Open it using **Microsoft Power BI Desktop**.
3. Refresh the data if required.
4. Use the available visuals and report interactions to explore the weather information.

---

## 📚 Skills Demonstrated

This project demonstrates practical knowledge of:

* Power BI
* Power Query
* DAX
* Data Cleaning
* Data Transformation
* Data Modeling
* Data Visualization
* Dashboard Design
* Interactive Reporting

---

## 👩‍💻 Author

**Adeeba Abdul Vahid**

B.Tech Computer Science Engineering Student

---

⭐ If you find this project useful, feel free to explore the dashboard and its implementation.
