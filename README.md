# Fleet-Management-System

A Java OOPs based console application for managing a fleet of different vehicles such as cars, trucks, buses, airplanes, and cargo ships.  
This project was developed as part of the Advanced Programming (AP-1) Assignment.

---

## Features

- Add and remove vehicles dynamically
- Start journeys for all vehicles with distance input
- Refuel all fuel-based vehicles
- Perform maintenance on vehicles that require it
- Generate reports summarizing fleet details
- Save and load fleet data to and from CSV files
- Search vehicles by type
- Handle errors with custom exceptions

---

## Class Structure

Vehicle Hierarchy:
- Vehicle (abstract)
  - LandVehicle → Car, Truck, Bus
  - AirVehicle → Airplane
  - WaterVehicle → CargoShip (sail-powered or fuel-powered)

Interfaces:
- FuelConsumable
- CargoCarrier
- PassengerCarrier
- Maintainable

Manager:
- FleetManager → Manages list of vehicles, reports, and persistence

Access docs/README.txt for compilation and running instructions.
