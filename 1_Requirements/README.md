# Wiper Control System

# Introduction
In cars, a wiper control system replaces the standard wiper blade with an electrical component. In this setup, the ignition button (on the motor) will be controlled by a single switch in the ACC position. Switch on the wiper system with a second press, then vary the wiper speed with a third press, and finally turn off the motor with a fourth press. All of this was done with the help of LEDs and a simulation tool.A wiper is a vital component that removes rainfall or any other liquid from the windscreen of a vehicle. 

The previous method required manual wiper activation, and raising the wiper was a tough task. As a result, this system is being presented as a solution to these problems. The project's goals are to supply wiping systems for older automobiles, improve the system by using actuators and pull switches (using the same switch for various functions by stepwise switching), and manage engine and wiper speed with a single switch. 

This System regulates the wiper's operation speed in response to the amount of rain. This Wiper Speed Control System is utilised in all sorts of automobiles, and its primary function is to remove rain air drops from the vehicle's front screen.

# Software Required
 - STM32 IDE

# Component
- STM32F407VG MICROCONTROLLER BOARD

# Features
- ON The Motor(Ignition Position)
- OFF the Motor
- Power ON Wipers
- Speed Controll of wipers

# SWOT Analysis
![168051944-525000fb-171d-4984-ab8e-7b1a4ec9c0d5](https://user-images.githubusercontent.com/102871721/168345071-df9ab350-3fa7-4f8c-b24e-289e3c4cff19.png)

 # 4W & H (WHO,WHAT,WHEN,WHERE,HOW)
 
 - WHO - A wiper speed control system for an automotive wiper controls the operational speed of a wiper in accordance with rain conditions.
 - WHAT - High reliability.
 - WHEN - When it rains, the wiper control system is used.
 - WHERE - In general, car wipers are controlled by the stalk on the right side of the steering wheel.
 - HOW - You can adjust the speed of the car wiper system according to the rainfall.

 # High level Requirements
|ID	|Description|
|----|---------|
|HLR-1|	User shall be able to ON the motor|
|HLR-2|	User shall be able to ON the wipers and controll the speed of wipers|
|HLR-3|	User shall be able to OFF the wiper|
|HLR-4|	User shall be able to OFF the motor|

# Low level Requirements

|   ID	   |Description|
|--------|---------|
|LLR-1|When user presses the switch for first time for two seconds, The Red LED is ON|
|LLR-2|	When user presses the button twice, Blue, Green and Orange LEDs come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz|
|LLR-3|When user presses the button fourth time The LED glow pattern stops|
|LLR-4|	Again pressing the button for two seconds The Red LED is OFF|
