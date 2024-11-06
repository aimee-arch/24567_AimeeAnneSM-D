# Gishushu  traffic lights
Specification (Narration) of Gishushu Traffic Lights
The specification details how the traffic lights operate over time and in different conditions:

System Overview
The Gishushu Traffic Light Control System (TCS) is designed to manage traffic flow at a busy intersection. The system operates in a cyclic manner, with three main states—Green, Yellow, and Red. These states control the movement of traffic in one direction at a time to prevent collisions and optimize traffic flow.

State Descriptions
Green State:

Purpose: Allows vehicles to move through the intersection in the active direction.
Duration: Remains in the Green state for a preset time (e.g., 30 seconds).
Transition Condition: After the Green state duration completes, the system transitions to the Yellow state to prepare for a halt.
Yellow State:

Purpose: Alerts drivers that the light will soon turn red and they should prepare to stop.
Duration: Remains in the Yellow state for a brief period (e.g., 10 seconds).
Transition Condition: After the Yellow state duration completes, the system transitions to the Red state, stopping traffic.
Red State:

Purpose: Stops traffic in the current direction to allow cross-traffic or pedestrians to move.
Duration: Remains in the Red state for a preset time (e.g., 20 seconds).
Transition Condition: After the Red state duration completes, the system transitions back to the Green state to allow the next traffic flow cycle.
Additional Considerations
Emergency Override: If an emergency vehicle is detected (e.g., through a sensor or manual control), the system can temporarily override the cycle, allowing an immediate switch to Green in the needed direction.
Pedestrian Signals: Optional signals can be integrated to allow pedestrian crossing during Red states.
Timing Example
The Green state lasts for 30 seconds, allowing traffic to pass.
The Yellow state then activates for 10 seconds, warning vehicles to prepare to stop.
Finally, the Red state activates for 20 seconds, stopping traffic and potentially allowing cross-traffic or pedestrian movement.
This cycle repeats continuously to manage the flow of traffic effectively.
