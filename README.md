# MicroPLC Kernel – Concept

## Vision
This project defines a PLC kernel philosophy designed to run on highly constrained
microcontrollers (e.g. Arduino Uno class devices).

## Core Idea
The system separates:
- A fixed PLC kernel
- External user logic
- Runtime logic injection without full firmware rewrite

## Architecture Principles
- Kernel is immutable during operation
- Logic is loaded dynamically
- Communication via WebSerial API
- Logic can be updated at runtime

## Status
Concept and architecture definition phase.
No implementation yet.
