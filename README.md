# AnkiAssistant
Embedded Linux System controlling Browser and Anki SRS Tool with a gesture control interface

## Components

# Microcontroller Interface
An ATmega 328 controlls the Boot-Sequence of the main system by waiting for infrared commands and PIR-Sensor signal

## Embedded Linux System
An Rasberry PI controlls a webbrowser and the Anki SRS Tool. Instead the usual mouse/keyboard interface, this approach uses an user specific set
of gesture controls to navigate through the menus.

## Operating Systems
MCU: ChibiOS
RPI: Linux, Rasberry PI OS / Manjaro ARM / Poky (Dunfell)
