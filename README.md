# Low_Voltage_Sensor_Comparator

Overview
- Designed and built an analog undervoltage detection circuit that activates an LED when the supply voltage drops below a defined threshold (~8V). The system uses a Zener reference, resistor divider, and TLC3702 comparator to detect low-supply conditions.
- Measured trip point: 7.3–7.4V (close to theoretical 8.0V).

Design Summary
- 4.3V Zener diode used as stable voltage reference
- 50 kΩ potentiometer configured as voltage divider to set trip threshold
- TLC3702 comparator compares scaled VDD to reference
- LED indicator driven by comparator output
- Circuit validated through staged testing and measurement

Key Concepts
- Voltage divider modeling
- Comparator threshold analysis
- Zener voltage regulation
- Hardware prototyping and debugging
- Analysis of real-world component tolerances

Results
- The comparator transitioned at ~7.3–7.4V.
- Deviation from theoretical 8.0V attributed to Zener tolerance, resistor variation, and comparator offset voltage.

Files
Low_Voltage_Sensor_Report.pdf – Full IEEE technical report
Circuit schematics and experimental data

Author: Harshitha Thimmapuram
Computer Engineering, Cal Poly SLO
