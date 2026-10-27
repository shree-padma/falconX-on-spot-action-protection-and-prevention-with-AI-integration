# FALCONX Technical Design

## Proposed Architecture

```text
Optical / Thermal Sensors
          |
          v
   Image Processing
          |
          v
    AI Classification
          |
          v
 GPS Location + Event Data
          |
          v
 Wireless Communication
          |
          v
 Forest Officer Dashboard
```

## Components
1. Sensors: collect visual or thermal observations.
2. AI module: classifies potential threats.
3. GPS: associates observations with locations.
4. Communication: transmits alerts when connectivity is available.
5. Dashboard: displays alerts for human review.

## Current Implementation
The HTML dashboard simulates example alerts in a browser. The sensor, AI, GPS, and communication blocks are proposed components and are not yet integrated.

## Safety
Alerts must be verified by authorized personnel before action is taken. Drone operation must follow applicable laws and permissions.
