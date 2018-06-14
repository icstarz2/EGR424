# EGR424
Design of Microcontroller Applicaitons

-- -----------------------------------
Project Statement

Use the Timer peripherals to implement a stepper motor driver with linear ramp-up/ramp-down of stepping speed. An integrated dual H-bridge driver such as the L293 or SN754410 may be used with a low-current stepper motor. The linear acceleration profile must be interrupt-driven such that the change in step speed is synchronous with the steps themselves. 
There must be no surprises in motion, including: 

• Handling reversal of direction by smoothly decelerating to a stop then accelerating in the opposite direction 
• Handling changes of speed rather than just starting from a standstill 

-- -----------------------------------


