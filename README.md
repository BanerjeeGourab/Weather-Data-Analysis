
# 🌦️ Weather Data Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing weather data using Python and its popular data analysis libraries: **Pandas, NumPy, and Matplotlib**. The objective is to explore weather patterns, calculate descriptive statistics, identify extreme weather observations, and visualize trends to gain meaningful insights from weather data.

## 🎯 Project Objectives

- Load and inspect weather data using Pandas.
- Identify and handle missing values in the dataset.
- Perform data cleaning and preprocessing.
- Calculate statistical measures using NumPy.
- Analyze monthly weather patterns using Pandas.
- Create visualizations to understand weather trends.
- Identify days with unusually high temperatures and precipitation.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming and data analysis |
| Pandas | Data manipulation and cleaning |
| NumPy | Statistical calculations |
| Matplotlib | Data visualization |
| Google Colab | Cloud-based notebook environment |

## 📂 Dataset Information

The project uses a CSV dataset named `weather_data_analysis.csv`.

| Column | Description |
|---|---|
| `Date` | Date of the weather observation |
| `Temperature_C` | Temperature in degrees Celsius |
| `Humidity_Percent` | Relative humidity percentage |
| `Precipitation_mm` | Precipitation measured in millimeters |


## 🔍 Project Workflow

### 1. Data Loading and Inspection
- Load the CSV file using Pandas.
- Preview the dataset.
- Inspect column names and data types.
- Check for missing values.

### 2. Data Cleaning and Preprocessing
- Handle missing numeric values using column means.
- Convert the `Date` column into a datetime format.
- Prepare the data for further analysis.

### 3. Exploratory Data Analysis (EDA)
- Explore temperature, humidity, and precipitation.
- Group weather observations by month.
- Calculate monthly average weather measurements.
- Identify observations that exceed selected weather thresholds.

### 4. Statistical Analysis Using NumPy
Calculate the following statistical measures for temperature, humidity, and precipitation:

- Mean
- Median
- Standard deviation

### 5. Data Visualization Using Matplotlib

The notebook generates the following visualizations:

- 📈 **Line Chart:** Monthly average temperature
- 📊 **Bar Chart:** Monthly average precipitation
- 📉 **Histogram:** Distribution of temperature observations

### 6. Extreme Weather Observation Analysis

Identify days meeting the following conditions:

- Temperature above **35°C**
- Precipitation above **25 mm**

These are project-defined thresholds for exploration, not official meteorological classifications.

## 📊 Key Outputs

The analysis produces:

- Descriptive statistics for weather measurements.
- A monthly summary of weather data.
- Visualizations of temperature trends and precipitation.
- A histogram showing temperature distribution.
- Tables of observations exceeding the selected thresholds.

## 💻 How to Run the Project

### Option 1: Google Colab

1. Open the notebook in Google Colab.
2. Upload `weather_data_analysis.csv` to your Colab session.
3. Verify that the dataset contains the expected column names.
4. Run all notebook cells in sequence.

The notebook reads the dataset from:

```python
data = pd.read_csv("/content/weather_data_analysis.csv")
```

### Option 2: Run Locally

**Step 1:** Install Python 3.

**Step 2:** Install the required libraries.

```bash
pip install pandas numpy matplotlib jupyter
```

**Step 3:** Place the notebook and CSV dataset in your project directory.

**Step 4:** Open the notebook using Jupyter Notebook or JupyterLab.

**Step 5:** Update the dataset path if necessary and run all cells.

## 🧠 Skills Demonstrated

- Python Programming
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Pandas Data Manipulation
- NumPy Statistical Analysis
- Matplotlib Data Visualization
- Date and Time Data Handling
- Data Interpretation and Analytical Thinking

## ⚠️ Limitations and Future Improvements

- Investigate alternative methods for handling missing values.
- Validate weather measurements and identify invalid records.
- Analyze monthly trends separately for each year when multiple years are available.
- Explore relationships between temperature, humidity, and precipitation.
- Add further visualizations and document findings from the actual dataset.
- Include the dataset source and relevant charts in the repository.

## 👨‍💻 Author

**Gourab Banerjee**

Aspiring Data Analyst | Python | Pandas | NumPy | Data Visualization

---

⭐ If you find this project useful, feel free to explore the notebook and its analysis.
