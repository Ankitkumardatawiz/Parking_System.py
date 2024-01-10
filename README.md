# Parking Management System using Python

Welcome to the Parking Management System repository. This system is designed to manage parking spaces, vehicles, and transactions using Python with a CSV-based database approach.

## Overview

The Parking Management System is a command-line-based application that allows efficient management of parking spaces, vehicles, and transactions within a parking lot.

## Features

### Vehicle Management
- **Add Vehicle:** Register new vehicles with details such as name, type, owner, and number.
- **Remove Vehicle:** Remove vehicles from the parking lot records.
- **View Vehicle Data:** Display details of all registered vehicles.

### Transaction Management
- **Calculate Parking Fee:** Calculate fees based on parking duration or vehicle type.
- **Generate Bill:** Create bills for vehicles based on parking duration and fees.
- **Generate Transaction Records:** Log transactions for vehicles entering and leaving the parking lot.

### Parking Space Management
- **Allocate Parking:** Assign available parking slots to incoming vehicles.
- **Remove Parking Space:** Remove a parking space from the available list.
- **View Parking Space:** Display details of available and occupied parking spaces.
- **View Left Space:** Show the number of available parking spaces left.

## Project Structure

The project structure includes the following files:

- **main.py:** The main execution file to run the parking management system.
- **vehicle_management.py:** Contains classes and methods related to vehicle management.
- **transaction_management.py:** Manages transactions, billing, and fee calculations.
- **parking_space_management.py:** Handles parking space-related functionalities.
- **database.csv:** CSV file acting as a database to store vehicle and transaction information.
- **README.md:** This file, providing an overview of the project.

## Usage

### Running the System
To start the Parking Management System, execute the `main.py` file in your Python environment.

python main.py
