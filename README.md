# Linear Regulated Power Supply

## Overview

This project presents the design of a protected 5 V / 1.5 A linear regulated power supply based on the LT1086 adjustable voltage regulator. The power supply is designed to provide a stable 5 V output from a 12 VAC input while incorporating multiple protection mechanisms for safe and reliable operation.

The design includes input inrush current limiting using an NTC thermistor, input and output fuse protection, a standby mode implemented with the LT1086 shutdown function, and an overvoltage crowbar protection circuit based on a TL431 precision shunt regulator and a BT169 SCR.

The complete circuit was designed in KiCad, while circuit verification and performance evaluation were carried out through SPICE simulations. Design calculations and simulation results are included to document the engineering process behind the final implementation.
