Its a sonar type device which approximate the position of object in a 2d space.
It consist of 8 ultrasonic array elements. Uses beamforming technique to scan any obstructions(Object). A single receiver receives the reflected waves and sends it as analog signal to esp32.
Here I have documented the scamatic of the circuit with all correct pin configurations.
Here are some information to be taken care of -
Pin 4 to pin 17 are GPIO pin 4 to GPIO pin 17 (not to be confused for other labled pins on different esp boards)
The ultrasonic receiver is to be connected between GPIO pin 34 and Ground.
STANDBY, EN pins in the circuit is to be connected to GPIO pin 33.
