# Global Weather Analytics Dashboard

## Project Overview
This project features a web scraper and an interactive dashboard to monitor and compare current weather conditions across major global cities. 

## Data Source
Weather data is dynamically scraped from [TimeAndDate Weather](https://www.timeanddate.com/weather/).

## Dashboard Features
* **Cross-City Filtering:** A dropdown menu allows users to select and compare specific cities.
* **KPI Cards:** Displays Average Temperature, Maximum Temperature, Average Humidity, and Maximum Wind Speed.
* **Visualizations:** 
  * Bar chart comparing temperatures across selected cities.
  * Scatter plot detailing Humidity levels, with bubble sizes representing Wind Speed.

## Instructions to Run the Project

### 1. Prerequisites
Ensure Python is installed along with the required libraries:
`pip install requests beautifulsoup4 pandas dash plotly`

### 2. Fetch the Data
Run the web scraper to pull the latest weather metrics and generate the `weather_data.csv` file:
`python scraper.py`

### 3. Launch the Dashboard
Start the Dash server:
`python app.py`

Open the local server link provided in the terminal (usually `http://127.0.0.1:8050/`) in your browser to view the dashboard.
