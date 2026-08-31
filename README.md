# APB-SPI-Master-IP-Core

## Overview
RTL design of an APB-interfaced SPI Master IP Core using Verilog HDL.

## Features
- APB Slave Interface
- SPI Master communication
- Programmable Baud Rate
- Shift Register
- Slave Select Control
- Functional Simulation

## Architecture
```text
APB Master
    |
APB Slave Interface
    |
SPI Control
    |
+---+---+---+
|       |   |
Baud   Shift  CS
Rate   Register
    |
 SPI Interface
