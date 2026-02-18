#  Renewable Energy Microgrid

A small-scale **solar-based renewable energy microgrid** designed to provide **reliable, affordable, and sustainable electricity** for rural and semi-urban communities with unreliable grid access.

---

##  Project Overview

Many rural areas face frequent power cuts, voltage fluctuations, and dependence on fossil-fuel-based backups like diesel generators and kerosene lamps.  
This project addresses those challenges by developing a **decentralized microgrid prototype** that integrates:

-  Solar energy
-  Battery storage
-  Grid backup
- Intelligent control using Arduino

The system ensures **uninterrupted power supply** for essential needs such as lighting, phone charging, water pumping, and medicine storage.

---

##  Objectives

- Provide **continuous and reliable power** in areas with unstable grid supply  
- Reduce dependence on **fossil fuels**
- Promote **renewable energy adoption**
- Design a **low-cost, scalable, and community-friendly** solution
- Enable **automatic and manual power source switching**

---

## System Architecture

**Power Sources**
- Solar Panel (Primary)
- Li-ion Battery (Storage)
- Grid Supply (Backup)

**Control & Switching**
- Arduino Uno R3
- Relay-based source switching
- Manual override using 3-prong switch
- LED indicators for source status

---

##  Hardware Components

| Component | Description |
|---------|-------------|
| Arduino Uno R3 | Main controller for logic and switching |
| 6V Solar Panel | Renewable energy source |
| 18650 Li-ion Battery (3.7V) | Energy storage |
| TP4056 Module | Battery charging & protection |
| DC-DC Buck Converter | Regulated 5V output |
| 5V Relay Module | Automatic source switching |
| 3-Prong Switch | Manual mode selection |
| LEDs & Resistors | Status and load indication |
| Breadboard & Jumper Wires | Prototype assembly |

---

##  Working Principle

1. **Automatic Mode**
   - If grid power is available → load powered by grid
   - If grid fails → system switches to solar/battery automatically

2. **Manual Mode**
   - User can manually select **Solar** or **Grid**
   - LEDs indicate the active power source

3. **Battery Management**
   - Solar panel charges the battery via TP4056
   - Buck converter ensures safe voltage levels

---

##  Software Logic

- Developed using **Arduino IDE**
- Relay control based on:
  - Grid availability
  - Manual switch input
- Priority-based switching ensures safety and reliability

---

## Results & Observations

-  Successful automatic switching with **zero interruption**
-  Stable voltage maintained during operation
-  Reduced reliance on kerosene lamps
-  Positive feedback from villagers, farmers, and teachers

**User Feedback Highlights**
- “Lighting at night has become more reliable.”
- “Phone charging and small electrical needs are now easier.”
- “Children can study comfortably in the evening.”

---

## Future Enhancements

- Integration of **wind or hybrid renewable sources**
- **IoT-based monitoring dashboard**
- Use of **recycled batteries** to reduce cost and e-waste
- Expansion for **agricultural and small industrial loads**
- Community-driven microgrid management models

---

##  Team Members

- **Sia Sunil**  
- **Sindhu M**  
- **Sneha L**

**Guide:** Mr. Shreyas P  
Department of Basic Sciences, CMR Institute of Technology

---

## References

- Ackermann et al., *Distributed Generation*, Electric Power Systems Research  
- Muhammad H. Rashid, *Power Electronics Handbook*  
- NREL – Microgrids  
- U.S. Department of Energy – Solar PV Basics

---

## License

This project is developed for academic and educational purposes.  
Feel free to fork, learn, and improve! 


