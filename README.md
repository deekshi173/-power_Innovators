# Innovators
![logo](https://github.com/user-attachments/assets/956be19e-4190-4ada-bc17-83a3d5d660a5)

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
Python 3.8 or higher: You can download Python from the official Python website.
Docker Desktop: Docker is required for running the load simulation. You can download Docker from the official Docker website.
Git: Git is used for version control and cloning the repository. You can download Git from the official Git website.
## Steps
1. Clone the repository:
```sh
git clone https://github.com/deekshi173/Innovators.git
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

# Process flow:
![Procces flow](https://github.com/user-attachments/assets/df4df581-2bcb-48eb-b634-5e02719cfef9)

# Architecture Diagram
![Power manager architecture](https://github.com/user-attachments/assets/5e9c536b-a9e6-4507-bd66-d04610766a18)

# Result
![report](https://github.com/user-attachments/assets/65e8ea20-a2b5-41a7-9d17-207d59e7cb5d)

# Conclusion
The Power Manager Telemetry project addresses the critical issue of power consumption in modern computing environments. By collecting detailed telemetry data, simulating loads, and analyzing the data, this project provides valuable insights into system power utilization. The project aligns with sustainability goals and offers a scalable framework for ongoing research and development.

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# File Structure
power_manager_telemetry/

├── measure_system_power_utilization.py

├── load_simulator.py

├── generate_report.py

├── Dockerfile

├── telemetry_data.py

├── README.md

├── LICENSE

├── .gitignore

├── src/
