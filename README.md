# FPS_GT511C3
Repository for example code for SEN-11792 at SparkFun.com https://www.sparkfun.com/products/11792.


Fingerprint Scanner - TTL (GT-511C3)(SEN-11792)

This fingerprint module is developed by ADH-Tech that communicates over TTL Serial.

This repository contains example code to work with  Arduino Board Leonardo, Arduino Board Micro and Arduino Board Yun.
or basically any board that runs ATmega32U4 Processor.

This Library is modified version of The library created by Josh Hawley. 
You can find the original library that works with Arduino Uno at https://github.com/sparkfun/Fingerprint_Scanner-TTL

The library for Arduino Uno actually uses SoftwareSerial Library to communicate with the Sensor. But in Atmega32U4 processor there are HardwareSerial available by the keyword Serial1 which can directly be used to communicate with the sensor.
According to the Pin Diagram of ATmega32U4 processor Pin number 0 and 1 acts as RX and TX respectively.

