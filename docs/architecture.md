# High-Level Architecture

## Components
- PLC Kernel (on microcontroller)
- Logic Storage / Execution Unit
- Web Interface (WebSerial API)

## Flow
1. Kernel boots
2. Web interface connects via serial
3. Logic (.hex or logical representation) is transmitted
4. Kernel validates and executes logic at runtime

## Constraints
- Limited RAM
- Limited Flash
- Deterministic execution
