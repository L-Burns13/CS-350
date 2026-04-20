# CS-350
Emerging Sys Arch &amp; Tech 

Overview:

This project is a smart thermostat prototype built using a Raspberry Pi. It reads the current room temperature and compares it to a set temperature. Based on this, the system switches between heating, cooling, or off.

The system uses LEDs to show the state. Red means heating, blue means cooling, and both off means the system is off. Buttons are used to change the state and adjust the set temperature. The LCD displays the time, temperature, and set point. The system also sends data through a serial connection to simulate sending data to a server.



Problem:

The goal of this project was to build a thermostat that can read temperature, respond to user input, and simulate communication with a server.

What I Did Well:

I successfully connected and used multiple components, including the sensor, LEDs, buttons, and display. I also used a state machine to control how the system behaves.

Where I Could Improve:

I could improve by reducing coding errors and planning my code better before starting.




Tools Used:

Raspberry Pi
Python
GPIOZero
Temperature sensor (I2C)
LCD display
UART



Skills Gained:

I learned how to connect hardware and software, use GPIO, read sensor data, and build a state machine.



Maintainability:

I used functions, comments, and a state machine to keep the code organized and easier to understand.



Future Improvements:

This project could be improved by adding WiFi to send data to a real server and allowing remote control.
