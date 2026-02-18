Renewable Energy Microgrid for Rural Advancement
 Project Overview
The Renewable Energy Microgrid project is a mini project developed under the Innovation & Design Thinking Laboratory at CMR Institute of Technology, Bangalore, affiliated to Visvesvaraya Technological University.
This project presents the design and development of a solar-based decentralized microgrid system aimed at providing reliable, affordable, and sustainable electricity to rural and semi-urban communities experiencing frequent power outages and unstable voltage supply.
The system integrates:
Solar energy generation
Battery storage
Grid backup
Intelligent Arduino-based control system
Problem Statement
Many rural communities face:
Frequent power cuts
Voltage fluctuations
Dependence on kerosene lamps and diesel generators
High operational costs
Limited access to reliable backup systems
There is a need for a low-cost, scalable, and community-friendly renewable energy solution that ensures uninterrupted electricity for essential needs.
 Objectives
Design a small-scale renewable energy microgrid.
Ensure uninterrupted power supply for essential loads.
Reduce dependence on fossil fuels.
Provide a scalable and modular energy solution.
Promote sustainable rural development.
 System Architecture
The microgrid system consists of:
6V Solar Panel – Primary renewable energy source
18650 Li-ion Battery (3.7V) – Energy storage
TP4056 Charging Module – Battery charging & protection
DC-DC Buck Converter – Voltage regulation
Arduino Uno R3 – Central controller
5V Relay Module (Active LOW) – Source switching
Grid Adapter (5V) – Backup power source
LED Indicators – Source & load status indication
Working Principle
The system operates in three modes:
Solar Mode (Manual)
Grid Mode (Manual)
Automatic Mode
Automatic Mode Logic:
If grid is available → Load powered by grid
If grid fails → Automatically switches to solar/battery
Relay ensures safe and uninterrupted switching
The Arduino continuously monitors source availability and controls relay switching accordingly.
Arduino Implementation
The microgrid control logic is implemented using Arduino Uno R3 with:
Digital input pins for grid detection & manual switches
Relay control for source switching
LED indicators for power source status
Serial monitoring for debugging
Key Features:
Automatic switching without interruption
Manual override functionality
Safe startup default mode
Simple and reliable logic
Results & Testing
User Testing Participants:
8 Villagers
2 Farmers
1 Government School Teacher
1 Local Stakeholder
Observed Outcomes:
Improved power reliability
Successful automatic source switching
Reduced kerosene usage
Safe battery voltage operation
User Feedback:
“Lighting at night has become more reliable.”
“Children can study comfortably in the evening.”
“System is simple and suitable for village use.”
Advantages
Environment-friendly renewable energy
Reduced dependency on fossil fuels
Cost-effective in long term
Modular and scalable
Easy to operate and maintain
Suitable for off-grid and rural areas
 Future Scope
Integration of wind energy (Hybrid microgrid)
IoT-based real-time monitoring dashboard
AI-based energy forecasting
Expansion to agricultural and small industrial loads
Community-managed microgrid models
Technologies Used
Renewable Energy Systems (Solar PV)
Embedded Systems
Arduino Programming
Power Electronics
Battery Management Systems
Project Structure (Suggested GitHub Folder Structure)
Copy code

Renewable-Microgrid/
│
├── README.md
├── Arduino_Code/
│   └── microgrid_controller.ino
├── Circuit_Diagram/
├── Images/
├── Report/
│   └── Mini_Project_Report.pdf
└── Documentation/
Authors
Sia Sunil
Sindhu M
Sneha L
Mini Project – First Semester
Department of Basic Sciences
CMR Institute of Technology
Bangalore, India
