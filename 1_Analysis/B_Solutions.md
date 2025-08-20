# Potential Solutions
## Case study
The RAXS trial at Callaghans Lane, NSW, is a $1.2 million initiative deploying modular, solar-powered level crossing technology for regional and remote areas.[^1] Using wireless train detection, RAXS activates lights, bells, and warning signs, converting passive crossings into active safety zones. Key features worth replicating in our venture include the modular scalable design, renewable energy use, and multi-sensory alerts. The collaborative funding model unites state, federal, and industry partners to enable rapid deployment and innovation. Adopting these strategies can maximise safety and efficiency in future rail crossing projects.

## Proposal #1: Primitive Option
To make the active rail crossing as affordable as possible and an accessible alternative to passive crossings, an extremely simple design could be implemented. Utilising a smart layout for the crossing would minimise the need for complex logic or sensors. 
- **Two lanes, two gates**: With two lanes of traffic across the railway crossing, the gates only need to stop incoming vehicles and pedestrians from entering the crossing. The gates will not block users from exiting the crossing. As such, no significant logic will be needed to ensure a vehicle does not get trapped by the gates. 
- **Breakaway gates**: The physical mechanism of the gate will be designed to "fail gracefully" if it collides with a vehicle while closing. A simple connection will allow the beam to fall off if it closes on a vehicle, ensuring no damage to vehicle or the gate-closing mechanism. This is similar to gates used in many parking garages. This eliminates the need for any gate proximity sensors. 
- **Sequenced warnings**: First the lights will flash, then the bells will chime, warning that the gates will imminently close and providing users time to finish passing through the crossing. The gate can then slowly close, minimising the chance of striking a vehicle. 
#### Logic
1. A train triggers the distant sensor, starting the crossing sequence. 
2. Warning lights turn on.
3. Warning bells chime. 
4. After a time delay, the gates slowly close. 
5. As the train passes through the crossing, the close train presence sensor is triggered. 
6. When the close train presence sensor no longer detects a train, it is presumed that the train has passed. 
7. The bell ceases.
8. The lights turn off. 
9. After a short delay, the gates open. The crossing sequence is concluded. 

## Proposal #2: High-tech Safety
To further enhance safety and reliability, a high-tech solution can be implemented using advanced sensing, communication, and automation technologies.

- **Multi-sensor detection**: Integrate radar, LIDAR, and thermal cameras to detect trains, vehicles, and pedestrians in and around the crossing. This redundancy ensures accurate detection even in adverse weather or low-visibility conditions.
- **Obstacle detection and alerting**: Sensors continuously monitor the crossing for stalled vehicles or pedestrians. If an obstruction is detected after the warning sequence has started, the system can delay gate closure, issue targeted audio/visual alerts, and notify rail operators in real time.
- **Connected infrastructure**: Employ vehicle-to-infrastructure (V2I) communication to warn approaching vehicles via in-car alerts or navigation apps, reducing driver reaction time.
- **Remote monitoring and diagnostics**: The crossing system is connected to a central control center, enabling remote health monitoring, predictive maintenance, and rapid response to faults or incidents.
- **Battery backup and solar power**: Ensure uninterrupted operation during power outages, with solar panels and battery storage for sustainability and resilience.

#### Logic
1. Distant train detection triggers the crossing sequence.
2. Warning lights and bells activate; V2I alerts are sent to nearby vehicles.
3. Sensors scan for obstacles on the crossing. If detected, gates remain open and alerts escalate.
4. If clear, gates close in a controlled sequence.
5. As the train approaches, sensors continue to monitor for late entries or obstructions, pausing the sequence if necessary.
6. After the train passes and sensors confirm the crossing is clear, gates open and alerts cease.
7. System logs all events and reports status to the control center for oversight and maintenance.


[^1]: New South Wales Government, "Trial goes live: Minns Labor Government delivering first-of-its-kind tech to improve regional rail safety and save lives," Released by: Minister for Regional Transport and Roads, 13-Aug-2025. [Online]. Available: https://www.nsw.gov.au/ministerial-releases/trial-goes-live-minns-labor-government-delivering-first-of-its-kind-tech-to-improve-regional-rail-safety-and-save-lives. [Accessed: 20-Aug-2025].