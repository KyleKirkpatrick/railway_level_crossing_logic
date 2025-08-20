# Potential Solutions
## Case study
The RAXS trial at Callaghans Lane, NSW, is a $1.2 million initiative deploying modular, solar-powered level crossing technology for regional and remote areas.[^1] Using wireless train detection, RAXS activates lights, bells, and warning signs, converting passive crossings into active safety zones. Key features worth replicating in our venture include the modular, scalable design, renewable energy use, and multi-sensory alerts. The collaborative funding model unites state, federal, and industry partners to enable rapid deployment and innovation. Adopting these strategies can maximize safety and efficiency in future rail crossing projects.

## Proposal #1: Primitive Option
To make the active rail crossing as affordable as possible and an accessible alternative to passive crossings, an extremely simple design could be implemented. Utilising a smart layout for the crossing would minimise the need for complex logic or sensors. 
- **Two lanes, two gates**: With two lanes of traffic across the railway crossing, the gates only need to stop incoming vehicles and pedestrians from entering the crossing. The gates will not block users from exiting the crossing. As such, no significant logic will be needed to ensure a vehicle does not get trapped by the gates. 
- **Breakaway gates**: The physical mechanism of the gate will be designed to "fail gracefully" if it collides with a vehicle while closing. A simple connection will allow the beam to fall off if it closes on a vehicle, ensuring no damage to vehicle or the gate closing mechanism. This is similar to gates used in many parking garages. This eliminates the need for any gate proximity sensors. 
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


[^1]: New South Wales Government, "Trial goes live: Minns Labor Government delivering first-of-its-kind tech to improve regional rail safety and save lives," Released by: Minister for Regional Transport and Roads, 13-Aug-2025. [Online]. Available: https://www.nsw.gov.au/ministerial-releases/trial-goes-live-minns-labor-government-delivering-first-of-its-kind-tech-to-improve-regional-rail-safety-and-save-lives. [Accessed: 20-Aug-2025].