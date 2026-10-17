# LED Blinking 

## Overview
This project demonstrates the basic working of an LED using a microcontroller. The LED is programmed to turn ON and OFF at regular time intervals.

## Components Required
- Arduino Uno
- LED
- 220-ohm resistor
- Breadboard
- Jumper wires
- USB cable

## Circuit Connections
- LED anode (long leg) → Digital Pin 13 through a resistor
- LED cathode (short leg) → GND

## Working Principle
The Arduino is programmed to turn the LED ON for one second and OFF for one second continuously. This demonstrates digital output control and basic embedded programming.

## Arduino Code
const int LED = 13;   
void setup()
{
  pinMode(LED, OUTPUT);
}

void loop()
{
  digitalWrite(LED, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}

## Applications
- Learning basic Arduino programming
- Understanding digital output pins
- Introduction to embedded systems


