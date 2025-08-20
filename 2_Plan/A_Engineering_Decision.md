# Engineering Decision Plan: Compromise Solution

We will implement a balanced approach for the railway level crossing logic, integrating elements of both the high-tech and the primitive proposals. We will use the physical design of the gates to limit entry to the crossing but not block users from exiting the crossing. A gate obstruction sensor will avoid collision with vehicles and pedestrians which will enable us to use a robust gate mechanism that does not need to have a breakaway feature (as proposed in the primitive solution).

## Objectives

- Ensure safety for vehicles and pedestrians.
- Achieve high reliability and fail-safe operation.
- Maintain reasonable implementation and maintenance costs.
- Allow for future scalability and upgrades.

## Compromise Solution Suitability

- **Simplicity:** By relying on proven mechanical barriers and straightforward electronic controls, the system remains easy to understand, operate, and maintain. 

- **Safety:** Mechanical barriers provide a clear physical safeguard, while electronic enhancements enable timely and accurate operation. The use of redundant detection methods ensures that the system responds appropriately to approaching trains, minimising the likelihood of accidents.

- **Reliability:** Integrating both mechanical and electronic elements allows the system to function effectively even if one component fails. Redundant detection and manual override capabilities ensure that the crossing remains safe under a wide range of conditions.


## Features to be Implemented
1. **Gate Obstruction Detection**
    - Delay closing the gate if a vehicle or pedestrian is obstructing it.
    - Sound an alarm to alert the user to exit the crossing. 
2. **Manual Override and Fail-Safe Modes**
    - Include manual controls for emergency operation.
    - Default to a safe state (gates down, signals active) on system failure.
3. **Remote Monitoring**
    - Integrate basic telemetry for remote status checks and maintenance alerts.

