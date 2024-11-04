# Australia Wildfire Dashboard

### Overview

The Australia Wildfire Dashboard is an interactive web application built with Python, Dash, and Plotly. It provides a visualization of wildfire data across various regions in Australia, allowing users to explore monthly trends in wildfire area and pixel counts for vegetation fires. The dashboard is designed to help users analyze wildfire patterns over time, enhancing understanding and awareness of wildfire impacts across Australian regions.

### Features

- **Select Region**: Choose a specific region to analyze wildfire data.
- **Select Year**: Filter data for a specific year to visualize trends.
- **Monthly Average Estimated Fire Area (Pie Chart)**: Displays the average fire area per month for the selected year and region.
- **Monthly Average Count of Pixels for Vegetation Fires (Bar Chart)**: Shows the average count of pixels indicating presumed vegetation fires per month for the selected year and region.

### Project Structure

The application is organized with a clean layout, featuring a dropdown menu for year selection and radio buttons for region selection. Graphical outputs (pie and bar charts) are displayed side by side for an effective comparison.

---

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Components](#components)
4. [Data Requirements](#data-requirements)
5. [Callback Function](#callback-function)
6. [Contributing](#contributing)
7. [License](#license)

---

## Installation

To get started, clone the repository and install the required libraries.

```bash
git clone https://github.com/your-username/australia-wildfire-dashboard.git
cd australia-wildfire-dashboard

## Prerequisites
Ensure you have Python 3.8 or higher installed, then install the following libraries:
          pip install setuptools packaging pandas dash httpx==0.20 plotly

