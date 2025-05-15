#  LabVIEW Automatic Faucet System

This project is a LabVIEW simulation of an automatic faucet system, developed as part of my electrical engineering studies. It mimics how a real-world sensor-based tap operates using virtual controls and logic.

##  Project Description

The system simulates an automatic water faucet that turns on when a "hand" is detected under the sensor and turns off after a configurable time delay. Since there is no physical sensor or hardware involved, the simulation uses a **toggle button** on the front panel to represent the presence or absence of a hand.

##  Key Features

- **Start/Stop Simulation**: Use a front panel button to simulate a hand under the faucet.
- **Configurable Timer**: Set how long the water should run after activation.
- **Visual Feedback**: The state of the faucet (on/off) is shown clearly through indicators on the panel.
- **Basic Control Logic**: Implements timing, state changes, and reset behavior.

##  Skills Demonstrated

- LabVIEW programming
- State machine logic and timing control
- Front panel design and user interaction
- Simulation of sensor-based automation

##  How to Run

1. Open the `.vi` file in **LabVIEW 2020** or later.
2. Set the desired timeout value.
3. Use the **"Hand Inserted"** toggle button on the front panel to simulate sensor input.
4. Observe how the faucet turns on/off based on your input and the timer.

##  Included Files

- Main `.vi` file for the faucet simulation
- Front panel with controls and indicators
- Block diagram implementing the logic

##  Author

**Akiva Spitz**  
Electrical Engineering Graduate  
akivaspitz@gmail.com
