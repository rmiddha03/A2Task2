# A2Task2
# Wikipedia Pageviews Comparison App

A simple Python application that fetches and compares the daily pageviews of two Wikipedia articles over a specified date range using the Wikimedia Pageviews API. The app displays the data in a Pandas DataFrame and visualizes it with a line chart.

## Overview

This application:
- **Prompts the user** for two Wikipedia article titles or URLs and a date range.
- **Fetches daily pageviews** for each article using the Wikimedia Pageviews API.
- **Merges the data** and creates a line chart for visual comparison.
- **Handles errors** like invalid article titles or date ranges.

## Features

- **User Inputs:** Accepts Wikipedia article titles/URLs and a date range.
- **Data Fetching:** Retrieves daily pageview data via the Wikimedia Pageviews API.
- **Data Visualization:** Plots a line chart with Matplotlib.
- **Data Display:** Outputs the combined data in a Pandas DataFrame.

## Requirements

- Python 3.x
- `requests`
- `pandas`
- `matplotlib`

Install the required packages with:

```bash
pip install requests pandas matplotlib

