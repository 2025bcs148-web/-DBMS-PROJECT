# -DBMS-PROJECT
Fleet Database Management System (Oil & Gas Sector)

Overview

The Fleet Database Management System (FDBMS) is designed to manage and monitor vehicles used in the oil and gas industry. It ensures efficient tracking of fuel distribution, vehicle maintenance, driver management, and logistics operations.
This system helps companies improve operational efficiency, reduce fuel losses, and enhance safety compliance

Objectives

To manage fleet vehicles and their operations
To track fuel transportation and delivery
To monitor vehicle maintenance and servicing
To manage driver records and assignments
To improve safety and accountability

 System Features

Fleet Management
Vehicle registration and tracking
Vehicle type, capacity, and status
Assignment of vehicles to routes

 Fuel Logistics
Fuel loading and delivery tracking
Monitoring fuel quantities transported
Recording delivery locations

 Driver Management
Driver personal details
License and certification tracking
Driver assignment to vehicles
Maintenance Management
Service scheduling
Repair records
Maintenance history tracking
 Route & Trip Management
Trip creation and monitoring
Route planning
Distance and fuel usage tracking
 Database Design
Main Entities:
Vehicle (VehicleID, PlateNumber, Type, Capacity, Status)
Driver (DriverID, Name, LicenseNumber, Contact)
Trip (TripID, VehicleID, DriverID, StartLocation, EndLocation, FuelLoaded, FuelDelivered)
Maintenance (MaintenanceID, VehicleID, ServiceDate, Description, Cost)
FuelStation (StationID, Name, Location)

Relationships:
One Driver → many Trips
One Vehicle → many Trips
One Vehicle → many Maintenance Records
One Fuel Station → many Trips

ER Diagram
The system is structured using an Entity-Relationship (ER) model showing:
Entities (Vehicle, Driver, Trip, Maintenance, FuelStation)
Primary Keys & Foreign Keys
Relationships between entitie

How It Works

1. Vehicles and drivers are registered in the system
2. Trips are created and assigned to drivers and vehicles
3. Fuel loads and deliveries are recorded
4. Maintenance schedules are tracked
5. Reports are generated for monitoring and decision-making

 Benefits
Improved fleet efficiency
Reduced operational costs
Better fuel accountability
Enhanced safety compliance
Accurate reporting and data management

[NTAMBI SHARIF]
Fleet Database Management System Project
Oil & Gas Sector
