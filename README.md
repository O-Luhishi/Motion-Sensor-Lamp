# Motion-Sensor-Lamp
Written by By Oluhishi [http://zonosnetworks.com]

## Overview

A simple lamp to be able to flicker on after someone or something had gone past it. To do this you have to set up and connect a Passive Infrared (PIR) Sensor and a Relay Module to a microcontroller. For this to work, I installed a Low Voltage Transformer (LVT) to connect to the Arduino to be powered by electricity from the mains after being set at a lower voltage.

## Components
1) Having a Microcontroller of any choice - I used Arduino Uno for size 
2) PIR sensor module
3) Relay Module 
4) Lightbulb
5) Some sort of enclosure to keep it in


## Usage

The default of this program is set to pin 4 and pin 8 on the Arduino Uno. However to change this, set ``` irmotionPin ``` & ``` relayPin ``` to the pins connected for the PIR Sensor and Relay Module respectively.

#### Default

Connect PIR Sensor to pin 4

Connect Relay Module to pin 8





