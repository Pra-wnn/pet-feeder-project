# pet-feeder-project


# Automated Pet Feeder – Logic Design

## Overview
This project designs the logic for a **low-cost automated pet feeder** for cats and dogs. The system dispenses food at scheduled times, monitors if the food is eaten, and alerts staff if there is an issue. The design focuses on **simple, modular logic** that can later be implemented with affordable hardware.



## Features
- Scheduled feeding for cats and dogs.
- Monitoring food consumption using weight sensors.
- Alerts for issues (not eaten ).
- LED indicators:  
  - **Green** = Success  
  - **Red** = Fault  



## Scope
- **Includes:** Feeding cats and dogs, scheduled dispensing, monitoring, alerts.
- **Excludes:** Water dispensing, mobile app, advanced AI features.



## Logic Summary
1. Check if feeding time matches schedule.
2. Dispense food  until target weight is reached.
4. Monitor if food is eaten within 10 minutes.



## Hardware (Future Implementation)
- **Controller:** Arduino or Raspberry Pi.
- **Components:** Servo motor, load cell + HX711, IR sensor, RTC module, LEDs, buzzer.


## Test Scenarios
- Normal feed → Dispense correct amount, LED Green.
- Pet does not eat → Alert after 10 min, LED Red.
