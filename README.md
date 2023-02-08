# isaac_rover_physical_2.0

## Table of content
[Old repository](#old-repository)<br/>
[Joystick control](#Joystick-control)<br/>
[Documentation](#documentation)<br/>



P7 - Rover
## Old repository
https://github.com/abmoRobotics/isaac_rover_physical


## Joystick control
The joystick used is the Logitech F710.
1. By default the robot is driven in automatic mode. Click Y to enable the joystick and set the manual mode.
2. Select the maximum speed by using the cross.
3. To drive the robot in any direction move the left stick and graduate the current speed using LT.
Note: The cross can be clicked at any time to change the maximum speed.
4. To make the robot rotate on itself click A. Use LT to turn clockwise and RT to turn anticlockwise. Do not move the left stick.
5. To disable turning mode click B.
6. To enable automatic robot drive click X.
7. Prees LB to power off the motors.

## Terminal commands
Use the docker to build the entire images of ros and the dependencies, run:
```bash
docker exec -it distracted_ride bash
```

## Documentation 
The motors has some minor things that could be fixed: 
Motor controllers: [link](https://en.nanotec.com/products/1768-c5-e-2-09-motor-controller-drive-for-canopen-or-usb)
