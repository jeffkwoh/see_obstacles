# see_obstacles

See Obstacles is a project that aims to augment visually impaired children's (VIC) ability to detect danger.


The complete system, comprise of:
1. Wearable obstacle detector
2. Smartphone interfacing with the obstacle detector

Features include:
1. Haptic feedback of nearby obstacle (W)
2. Alarming the caregiver of emergency (W)
    * Triggered either manually or automatically 
3. Relaying of current position to caregiver with smartphone (S)
4. Relaying of arrival at destination to the caregiver (S)


## Obstacle Detection

Obstacle detection is achieved through the use of proximity sensors, followed by a full body haptic feedback. This allows for positional data of nearby obstacles to be relayed to the VIC.

## Integration with App's interface

Implicitly, the two devices must have a way to pair with each other.

The wearable requires the following input:
1. Proximity data
2. Accelerometer data (has the child fallen down)
3. Emergency triggered (Child indicating an emergency to parents)
4. Location data 
    - Dead reckoning is not supported at the moment

The wearable is required to give the following outputs:
1. Location data  

The smartphone requires the following input:
1. Location data of the wearable
2. Desired destination for child to arrive
3. Alarms raised by the wearable

