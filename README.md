# Power Electronics Circuit Simulations with Simscape Power Systems

This repository contains a collection of basic power electronic circuit simulations developed using **Simscape Power Systems** in **MATLAB/Simulink**. These models are intended for educational and experimental purposes, helping users understand the fundamental behavior of common power electronic converters and rectifiers.

## 📂 Repository Contents

The following circuits are included in this repository:

### 1. Single Diode Bridge Rectifier

* **Description**: A basic rectifier using a single diode to convert AC to pulsating DC.
* **Application**: Used in low-power DC power supplies.

### 2. Three Diode Bridge Rectifier

* **Description**: Three-diode configuration typically used for 3-phase half-wave rectification.
* **Application**: Industrial power supplies requiring simple rectification.

### 3. Single Phase Full Converter

* **Description**: A controlled rectifier using four thyristors (SCRs) to provide fully controlled output DC voltage from an AC source.
* **Application**: DC motor drives, battery charging.

### 4. Three Phase Full Converter

* **Description**: A fully controlled three-phase bridge converter using six SCRs.
* **Application**: High power DC loads, HVDC transmission.

### 5. AC Voltage Regulator

* **Description**: Uses thyristors to regulate the RMS value of the output AC voltage.
* **Application**: Fan speed control, light dimmers, heating control.

### 6. Buck-Boost Converter

* **Description**: A DC-DC converter capable of stepping up or stepping down the input voltage.
* **Application**: Battery-operated devices, renewable energy systems.

## 🛠 Requirements

* MATLAB R2023a or later (recommended)
* Simulink
* Simscape
* Simscape Electrical (formerly SimPowerSystems)

## 🚀 Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/EssaRAE/Power-Electronic-Simulations.git
   cd Power-Electronic-Simulations
   ```

2. Open MATLAB and navigate to the project directory.

3. Open the Simulink model of the circuit you want to simulate:

   ```matlab
   open('filename.slx')
   ```

4. Run the simulation and analyze the waveforms using scopes.

## 📚 Learning Outcomes

* Understand the operation of different power electronic converters.
* Visualize current and voltage waveforms under various load conditions.
* Explore the impact of firing angles and switching strategies in controlled rectifiers and converters.

## 📄 License

This project is licensed under the MIT License
## 👌 Acknowledgements

* MATLAB Simulink Documentation
* Simscape Power Systems User Community

---

Feel free to contribute by adding new circuits, improving existing ones, or submitting suggestions!
