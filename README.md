# Dataset Build Code for Shell Eco-marathon Asia Pacific & Middle East 2025

This repository contains the dataset and code used for the Data Telemetry Awards submission for the Shell Eco-marathon Asia Pacific & Middle East 2025. The project focuses on building a robust dataset for telemetry data analysis, which is crucial for optimizing vehicle performance and energy efficiency.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

The goal of this project is to develop a comprehensive dataset that captures telemetry data from vehicles participating in the Shell Eco-marathon. This data is used to analyze and improve vehicle performance, energy efficiency, and overall sustainability. The dataset includes various parameters such as speed, acceleration, fuel consumption, and environmental conditions.

## Dataset Description

The dataset is built using data collected from multiple sensors installed on the vehicle. The data is then processed and cleaned to ensure accuracy and reliability. The dataset includes the following key features:

- **Timestamp**: The time at which the data was recorded.
- **Speed**: The speed of the vehicle in km/h.
- **Acceleration**: The acceleration of the vehicle in m/s².
- **Fuel Consumption**: The rate of fuel consumption in liters per 100 km.
- **Engine RPM**: The engine revolutions per minute.
- **Temperature**: The ambient temperature in °C.
- **Humidity**: The ambient humidity in percentage.
- **GPS Coordinates**: The geographical location of the vehicle.

## Repository Structure
data-telemetry-2025
**data**
- raw: Raw data collected from sensors.
- processed: Cleaned and processed data.
**scripts**
- data_cleaning.py: Script for cleaning the raw data.
- data_analysis.py: Script for analyzing the processed data.
**README.md**: The main documentation file (this file).
- requirements.txt: List of Python dependencies.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/bataviateamunj/data-telemetry-2025.git
   cd data-telemetry-2025

1. Install Required Dependencies:

pip install -r requirements.txt
