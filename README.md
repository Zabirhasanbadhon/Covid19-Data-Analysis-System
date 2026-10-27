# 🦠 COVID-19 Data Analysis

A modern, interactive desktop application built with **Python, Tkinter, Pandas, and Matplotlib** for analyzing and visualizing COVID-19 data.

The application features a beautiful cream-white interface, a dark sidebar, shadow-effect buttons, statistical cards, data tables, country search, sorting and filtering, and graphical visualizations.

---

## 📌 Project Overview

The COVID-19 Data Analysis Dashboard makes it easier to explore COVID-19 statistics through a user-friendly graphical interface.

Instead of manually analyzing data using Python scripts, users can load a CSV dataset and interact with the information through a desktop dashboard.

The application can analyze confirmed cases, deaths, recoveries, and country-level statistics.

### 🎯 Project Objectives

- Analyze COVID-19 data using Python.
- Display important statistics in a dashboard.
- Search and explore country-level data.
- Identify regions with the highest confirmed cases.
- Find regions with the lowest reported deaths.
- Sort and filter COVID-19 records.
- Visualize statistics using charts and graphs.
- Export analysis results to CSV files.
- Provide a modern and user-friendly graphical interface.

---

## ✨ Features

### 1. Modern Graphical User Interface
- Cream-white background.
- Elegant green accent colors.
- Dark sidebar navigation.
- White statistical cards.
- Button shadow effects.
- Interactive hover effects.
- Clean and organized dashboard layout.

### 2. COVID-19 Statistics Dashboard

Displays four important statistics:

- **Confirmed Cases:** Total confirmed cases in the loaded dataset.
- **Total Deaths:** Total reported deaths.
- **Recovered Cases:** Total reported recoveries.
- **Regions:** Number of unique countries or regions.

### 3. CSV Dataset Loading

Users can select a CSV dataset from their computer.

The application reads the file and prepares the data for analysis.

### 4. Dataset Explorer

- View COVID-19 records in a table.
- Search across dataset columns.
- Browse records using scrollbars.
- View different data fields.

### 5. Country Search

Search for a country or region to calculate its total:

- Confirmed cases.
- Deaths.
- Recoveries.

The application supports countries such as India, Bangladesh, Nepal, and the United States when they are present in the dataset.

### 6. Data Sorting and Filtering

Sort records by:

- Confirmed cases.
- Deaths.
- Recoveries.
- Region name.

Sorting can be performed in ascending or descending order.

Users can also filter records by a minimum number of confirmed cases.

### 7. Visual Analytics

The application provides graphical visualizations for:

- Confirmed cases.
- Deaths.
- Recoveries.
- Comparisons between confirmed cases, deaths, and recoveries.

Charts are displayed inside the application window using Matplotlib.

### 8. Statistical Analysis

The dashboard can identify:

- The top 10 regions by confirmed cases.
- The 10 regions with the lowest total deaths.
- Country-level COVID-19 statistics.

### 9. CSV Export

Users can export analysis results to a CSV file for further analysis, reporting, or use in other applications.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Tkinter | Graphical user interface |
| Pandas | Data processing and analysis |
| Matplotlib | Data visualization |
| ttk | Tables and interface widgets |
| CSV | Dataset input and results export |

---

## 📋 System Requirements

Before running the project, ensure you have:

- Python 3.9 or later.
- Visual Studio Code or another Python editor.
- A COVID-19 dataset in CSV format.
- The required Python libraries installed.

The application is designed primarily for Windows, but Tkinter applications can also run on macOS and Linux when the necessary dependencies are available.

---

## 📦 Installation Guide

### Step 1: Install Python

Download Python from the official website:

https://www.python.org/downloads/

During installation on Windows, enable **Add Python to PATH**.

### Step 2: Create a Project Folder

Create a folder named:

```text
Covid19_Analysis
```

Open this folder in Visual Studio Code.

### Step 3: Create the Python File

Create a file named:

```text
covid_gui.py
```

Paste the complete Python source code for the COVID-19 dashboard into this file and save it.

### Step 4: Install Required Libraries

Open the VS Code terminal and execute:

```bash
pip install pandas matplotlib
```

Tkinter is generally included with standard Windows Python installations.

### Step 5: Prepare the Dataset

Prepare a COVID-19 dataset in CSV format.

The application requires these data fields, or recognizable alternatives:

```text
Region
Confirmed
Deaths
Recovered
```

For example:

| Region | Confirmed | Deaths | Recovered |
|---|---:|---:|---:|
| Bangladesh | 1000 | 20 | 100 |
| India | 5000 | 150 | 2000 |
| Nepal | 500 | 5 | 300 |
| US | 10000 | 300 | 4000 |

**Note:** These numbers are fictional examples provided only to illustrate the required CSV format. They are not actual COVID-19 statistics.

Save your dataset as a `.csv` file.

### Step 6: Run the Application

In the VS Code terminal, execute:

```bash
python Covid19 Data Analysis.py
```

The COVID-19 Data Analysis Dashboard should open in a desktop window.

---

## 📖 How to Use the Application

### 1. Load a Dataset

Click **Load Dataset** or **Load CSV File** and select your COVID-19 CSV file.

The dashboard will read the data and calculate the statistics.

### 2. Explore the Dashboard

View the summary cards and the chart displaying regions with the highest confirmed case totals.

### 3. View Dataset Records

Select **View Dataset** from the sidebar to browse and search the loaded records.

### 4. Search for a Country

Select **Country Search**, enter a country name, and click **Search Country**.

The application displays the total confirmed cases, deaths, and recoveries for that country.

### 5. Sort and Filter Data

Open **Sort & Filter** to select a data column, choose a sorting order, and optionally specify a minimum number of confirmed cases.

Click **Apply** to display the results.

### 6. View Charts

Select **Visual Analytics** to view graphical comparisons of COVID-19 statistics.

Choose the statistic you want to visualize.

### 7. Export Results

Click **Export Results** in the sidebar to save the currently selected analysis results as a CSV file.

---

## 📊 Data Analysis Methods

The project uses several basic data analysis techniques.

### Aggregation

Pandas groups records by region and calculates totals for confirmed cases, deaths, and recoveries.

### Sorting

Records are sorted in ascending or descending order to identify the highest and lowest values.

### Filtering

Records can be filtered using a minimum confirmed-case threshold.

### Visualization

Bar charts are used to compare statistics across countries or regions.

### Missing Data Handling

The application converts invalid or missing values in the main numerical columns to zero and replaces missing region names with `Unknown`.

---

## ⚠️ Limitations

- The application depends on the structure and quality of the supplied CSV dataset.
- Results represent the loaded dataset and may not reflect current COVID-19 statistics.
- Summing multiple historical records for the same country may double-count cases if the dataset contains cumulative statistics from different dates.
- The dataset explorer displays up to 3,000 matching records at a time.
- The country search requires the country name to match a value in the `Region` column.
- The application does not retrieve live COVID-19 statistics from the internet.
- Button shadows are simulated using Tkinter frames rather than native graphical effects.

---

## 👨‍💻 Developer

** ZaBir HaSan**

---


**Built with Python, Pandas, Tkinter, and Matplotlib.**
