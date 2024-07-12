# Innovators
# Power Manager Telemetry
# Project Overview
Power Manager Telemetry is a project aimed at monitoring and optimizing power consumption in modern computing environments, especially in the context of 5G and edge computing deployments. This project focuses on collecting telemetry data from various system components, simulating load using Docker, and analyzing the data to provide insights into system power utilization.
# Table of Contents
## Project Overview
## Features
## Technologies Used
## Installation
## Usage
## Contributing
## Team Members and Contributions
## Architecture Diagram
## Conclusion
## License
# Features
Collection of telemetry data from CPU, memory, NIC, and TDP.
Load simulation using Docker to generate controlled CPU loads.
Analysis of telemetry data to calculate key metrics and generate insightful reports.
Detailed project documentation and user guides.
# Technologies Used
## Programming Languages:
Python (with libraries such as psutil, json, threading, subprocess)
## Containerization:
Docker (for creating and managing containers)
## Data Analysis:
JSON (for structured data storage)
## Operating Systems:
Linux (preferred for telemetry data collection and Docker operations)
Windows (supported with necessary adjustments)
## Documentation:
Markdown (for project documentation)
# Installation
## Prerequisites
Python 3.8 or higher
Docker Desktop
Git
## Steps
1. Clone the repository:
```sh
git clone https://github.com/yourusername/power_manager_telemetry.git
cd power_manager_telemetry
```
## Install Python dependencies:
```sh
pip install psutil
```
## Build the Docker image:
```sh
docker build -t load_simulator .
```
# Usage
## Running Telemetry Data Collection
1. Run the telemetry data collection script:
```sh
python telemetry_data.py
```
2. Run the measure system power utilization script:
```sh
python measure_system_power_utilization.py
```
The telemetry data will be logged into a CSV file.

## Running Load Simulation
3. Run the Docker container to simulate load:
``sh
docker build -t load_simulator .
```
# Generating Reports
## Run the report generation script:
```sh
python generate_report.py
```
The report will be generated in report.txt.

# Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes.
4. Commit your changes (git commit -m 'Add new feature').
5. Push to the branch (git push origin feature-branch).
6. Create a new Pull Request.
   
# Team Members and Contributions
## Y. Deekshitha
Project planning, data analysis algorithms, report generation script.
## V. Mahesh Babu
Telemetry data collection script, multi-threading implementation, system architecture.
## Vidyashree K J 
Dockerfile creation, load simulation script, Docker environment management.
##  B. Mohith
Project documentation, user guides, frontend interface for scripts.
## T. Jayavardhan Reddy
Testing, bug fixing, validation of telemetry data and reports.
