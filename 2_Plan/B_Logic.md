# Railway Level Crossing Logic Sequence

1. **Distant Train Presence Sensor Triggered**
    - When an approaching train is detected, begin the crossing sequence.

2. **Activate Warning Signals**
    - Turn on warning lights and crossing bells to alert vehicles and pedestrians.

3. **Gate Proximity Detection**
    - If a pedestrian or vehicle is obstructing the gate, the gate closing will be delayed.
    - Sound an alarm to alert the user that they must leave the crossing.

4. **Close Gates**
    - Once the gate proximity sensors show that the gates are clear, close the gates.

5. **Near Train Presence Sensor Triggered**
    - The train is now in the crossing.

6. **Near Train Presence Sensor Open**
    - The near presence sensor is no longer detecting the train. We will wait and continue monitoring the presence sensor, compensating for false negatives or noisy data. If the train has not been detected within the safety time, we can be sure the train is no longer present and then progress to end the crossing sequence.

7. **Deactivate Warning Signals**
    - Turn off warning lights and alarms.

8. **Raise Barriers**
    - Raise the barriers to allow vehicles and pedestrians to cross.

9. **Return to Idle State**
     - Resume monitoring for the next approaching train.
