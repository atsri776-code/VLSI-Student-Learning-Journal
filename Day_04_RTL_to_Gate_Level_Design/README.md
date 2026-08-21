# Day 04 — Standard Cell Libraries and Timing

## Objective

To understand the role of standard-cell libraries in digital design and synthesis.

## Topics Covered

- Standard-cell libraries
- Liberty files
- Cell functionality
- Cell area
- Cell power
- Cell delay
- PVT conditions
- Process variation
- Voltage variation
- Temperature variation
- Setup time
- Hold time
- Clock frequency
- Combinational delay

## Standard Cell Library

A `.lib` file contains information about the standard cells available for synthesis.

The library provides information such as:

- Logic functionality
- Area
- Timing characteristics
- Power characteristics
- Input capacitance
- Output behavior

## PVT

PVT stands for:

- **P — Process**
- **V — Voltage**
- **T — Temperature**

These conditions affect the performance of a digital circuit.

## Timing Concepts

The clock period must accommodate:

- Clock-to-Q delay
- Combinational logic delay
- Setup time

Hold time is also important to ensure that data does not change too quickly after the clock edge.

## Learning Outcome

I learned why different standard-cell sizes and flavors are available and how area, power, delay, and timing requirements influence cell selection during synthesis.
