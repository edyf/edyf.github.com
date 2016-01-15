---
layout: post
published: false
title: Homemade Arduino board runs on 2 AA batteries
---

Usually Arduino boards run at 5 or 3.3 Volts, but what is if you want to run your project on 2 AA batteries only? The good news is that Atmel Atmega 328 operation Voltage is between 1.8 - 5.5V (<a href="http://www.atmel.com/images/atmel-8271-8-bit-avr-microcontroller-atmega48a-48pa-88a-88pa-168a-168pa-328-328p_datasheet_complete.pdf" target="_blank">Datasheet</a>).


To prevent the microcontroller to reset when the current drops too low one can disable brown-out detection (BOD). Arduino IDE sets BOD by default to 2.7V 
