Robotic Hand with Flex Sensor Readings and Wireless Communication: 
This project involves designing and constructing a robotic hand that can be controlled wirelessly using flex sensors and nRF24L01 transceivers. 
The system is programmed and controlled using an Arduino UNO microcontroller.


Hardware Requirements
The following components are required to build the robotic hand:

|| 1x Arduino UNO R3
|| 2x NRF24L01+ transceivers
|| 2x NRF24L01+ adapters
|| 5x flex sensors
|| 5x MG90S servos
|| 5x steel springs
|| 1x pair of gloves
|| 3-in-1 jumper wires
|| Breadboard
|| Foam board
|| Nylon strings
|| Glue gun
|| Cable ties
|| Arduino compatible SCM & DIY kits


Libraries
To enable wireless communication between the transmitter and receiver, the RF24 library is required.


Implementation
The robotic hand is designed to mimic the movements of a human hand based on the readings from flex sensors. Five flex sensors are used to detect the 
bending of fingers, and five MG90S servos are used for actuation. The servos are attached to the fingers of the glove, and steel springs are used to provide 
resistance and bring the fingers back to their initial positions.

To enable wireless communication between the transmitter and receiver, two nRF24L01+ transceivers and adapters are used. The transmitter is connected 
to the flex sensors and sends the sensor readings to the receiver. The receiver is connected to the servos and receives the sensor readings to control the 
movement of the robotic hand.

The system is programmed and controlled using an Arduino UNO microcontroller. The RF24 library is used to establish wireless communication and the servo library 
is used to control the movement of the servos based on the sensor readings.
