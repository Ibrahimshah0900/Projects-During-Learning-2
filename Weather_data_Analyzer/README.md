

# Weather Data Analyzer

**Weather Data Analyzer** is a Python project that reads historical weather data from a CSV file and performs various analyses to find trends such as the hottest day, average temperature, and the number of rainy days. The project also visualizes temperature trends over time using Matplotlib.



## Features

- Load historical weather data from a CSV file.
- Analyze the data to:
  - Find the hottest day and its temperature.
  - Calculate the average temperature.
  - Count the number of rainy days.
- Visualize temperature trends over time using a line graph.

---

## Technologies Used

- **Python**
- **Pandas** (for data handling)
- **Matplotlib** (for visualizations)
- **CSV Module** (for basic CSV operations)

---

## Getting Started

### Prerequisites

Make sure you have Python installed and the following libraries:

- Pandas
- Matplotlib

Install them using:
```bash
pip install pandas matplotlib
```

### Setup

1. Clone this repository or download the code.
2. Ensure the `weather_data_utf8.csv` file is present in the same directory as the script. This file should contain the historical weather data.

---

## Usage

Run the script to analyze the weather data:
```bash
python weather_data_analyzer.py
```

### Outputs

1. **Hottest Day**: Displays the date and temperature of the hottest day.
2. **Average Temperature**: Computes the average temperature across all days.
3. **Rainy Days**: Counts the number of days with rainfall > 0 mm.
4. **Temperature Trends Graph**: Plots a line graph of temperature trends over time.

---

## Example CSV File Format

```csv
Date,Temperature (°C),Humidity (%),Rainfall (mm)
2024-01-01,25,65,0.0
2024-01-02,30,70,5.2
2024-01-03,22,50,0.0
...
```

---

## Project Workflow

1. **Read the CSV File**: Load the data using Pandas.
2. **Analyze the Data**:
   - Identify the hottest day using `idxmax`.
   - Calculate the average temperature using `mean`.
   - Count rainy days by filtering rows where rainfall > 0.
3. **Visualize the Data**: Plot temperature trends using Matplotlib.

---


Add some screenshots of the outputs or graphs to make it more interactive.

