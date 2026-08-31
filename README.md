# APB-SPI-Master-IP-Core

## Overview
RTL design of an APB-interfaced SPI Master IP Core using Verilog HDL.

## Features
- APB Slave Interface
- SPI Master
- Programmable Baud Rate
- Shift Register
- Slave Select Control
- Functional Simulation

## RTL Modules
- `APB_SLAVE_INTERFACE.v` – APB communication
- `Top_module.v` – Top-level integration
- `baudrate_generator.v` – SPI clock generation
- `shift_register.v` – Serial data shifting
- `spi_slave_control_select.v` – Slave select control

## Project Structure

```text
APB-SPI-Master-IP-Core
├── RTL
├── Simulation
├── README.md
└── LICENSE
