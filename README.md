# dongwon.ai.elec-effi
An AI-powered targeted inspection system that uses power flow analysis and real-time plant data to detect abnormal electrical equipment conditions and recommend high-risk areas for maintenance.
# KOEN GridPulse AX

## Introduction
This project is an AI-based power plant equipment management system that uses power flow analysis and real-time plant measurement data to detect abnormal electrical equipment conditions early and recommend high-risk areas for targeted inspection.

## Key Features
- Predicts normal voltage, current, active power, reactive power, and power loss in the plant’s internal power system using power flow analysis
- Compares real-time SCADA/DCS/protective relay data with calculated reference values to detect abnormal patterns
- Estimates possible causes of equipment abnormalities, such as insulation degradation, poor contact, foreign object contact, bird nests, and insulator contamination
- Automatically recommends high-risk areas for targeted inspection using workers, drones, or thermal imaging cameras
- Continuously improves the AI model by reflecting inspection results and maintenance history

## How to Use
1. Input power system data from the power plant.
   - Bus information
   - Line impedance
   - Transformer data
   - Load and generator output
   - Real-time voltage, current, and power data

2. Run power flow analysis to calculate the normal power flow.

3. Compare the calculated results with real-time measurement data.

4. Let the AI analyze abnormal deviations and identify high-risk areas.

5. Perform targeted inspection on the selected areas using workers or drones.

## License
MIT License
