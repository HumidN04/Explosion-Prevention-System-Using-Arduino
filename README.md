Objective:
To design a safety system using Arduino that monitors hazardous conditions, such as gas leaks, overheating, or flame detection, and triggers alarms or preventive actions to avoid explosions in industrial or domestic environments.

Materials Required:
Arduino Uno
MQ-2 Gas Sensor (for detecting combustible gases like methane or LPG)
Flame Sensor
Temperature Sensor (e.g., LM35)
Buzzer (for alarm)
LEDs (Red for danger, Green for safe)
Relay Module (to control external devices like ventilation or shutdown systems)
16x2 LCD Display (optional, to show real-time data)
Connecting Wires
Power Supply (5V)


System Overview:
This system uses an Arduino microcontroller to continuously monitor the environment for any dangerous gas leaks, excessive heat, or flame. If any of these are detected, the system triggers a buzzer and flashes LEDs to warn of potential explosions. It can also activate a relay to shut down equipment or activate ventilation systems.

Working Principle:
Gas Detection: The MQ-2 sensor detects gases such as methane, propane, and butane. When the gas level crosses a predefined threshold, the system sounds an alarm.
Flame Detection: The flame sensor detects infrared light emitted by a fire. When a flame is detected, it triggers the buzzer and LED warning signals.
Overheating Detection: The temperature sensor monitors ambient temperature, and if it exceeds a safe limit, the system triggers the alarm and can cut off power using a relay.
Preventive Measures: The system can be programmed to activate relays to either shut down machinery or activate ventilation fans to prevent dangerous conditions from escalating.


Circuit Diagram:
Connect the MQ-2 sensor to the analog input of the Arduino.
Connect the flame sensor to a digital input pin.
Connect the temperature sensor to another analog pin.
Connect the buzzer, LEDs, and relay module to digital pins.


Key Features:
Real-time Monitoring: The system continuously checks for gas, flame, and temperature conditions.
Early Warning System: Alarms and LEDs provide immediate visual and audible warnings in case of danger.
Preventive Action: Relays can be used to shut down machinery or activate ventilation, preventing hazardous situations from escalating.
Modular Design: Additional sensors can be easily integrated to cover a wider range of hazardous conditions.


Testing:
Simulate gas leaks using a gas lighter near the MQ-2 sensor and observe if the alarm triggers.
Introduce a small flame near the flame sensor to check its response.
Increase ambient temperature artificially (e.g., using a heat source) to test overheating detection.


Conclusion:
This explosion prevention system using Arduino is a cost-effective and scalable solution for monitoring hazardous conditions in industrial or domestic settings. By combining gas, flame, and temperature sensors, the system can detect multiple potential threats and take preventive action to avoid explosions.
