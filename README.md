# Smart Traffic Light System using PIC16F628A

## Overview
This project is a smart traffic light controller implemented with PIC16F628A microcontroller using Assembly language.

The system controls:
- 4 traffic roads
- Vehicle sensors
- Pedestrian crossing buttons
- Timer0 interrupt system
- State machine traffic sequencing

## Features
- Timer0 interrupt driven timing
- Automatic road sequencing
- Vehicle sensor detection
- Skip empty roads
- Pedestrian crossing mode
- 2-minute pedestrian button lock system
- Internal oscillator usage
- Non-blocking system design

## Hardware
- PIC16F628A
- LEDs
- Push buttons
- Switches
- Resistors

## Pin Configuration

### PORTB Outputs
| Pin | Function |
|---|---|
| RB0 | Road1 Green |
| RB1 | Road1 Red |
| RB2 | Road2 Green |
| RB3 | Road2 Red |
| RB4 | Road3 Green |
| RB5 | Road3 Red |
| RB6 | Road4 Green |
| RB7 | Road4 Red |

### PORTA Inputs
| Pin | Function |
|---|---|
| RA0 | Sensor1 |
| RA1 | Sensor2 |
| RA2 | Sensor3 |
| RA3 | Sensor4 |
| RA4 | Right Pedestrian Button |
| RA5 | Left Pedestrian Button |

## Technologies
- PIC16F628A
- Assembly Language
- MPLAB
- Proteus
- Timer0 Interrupts
- State Machine Design

## Author
Nabil Aktalati
