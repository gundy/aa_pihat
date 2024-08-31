# AA Boards and Tools

This repository contains some schematics and board designs that have been useful when trying to understand the communications used by the AA system.

- [An interceptor board](./hardware/boards/aa_interceptor/README.md) that sits between the tablet and CB and allows the RS485 lines to be read.
- [A 'hat' for a Raspberry Pi](./hardware/boards/pi_hat/README.md) that uses the 14v supply to power the Pi, and provides circuitry to allow the PI's built-in serial port to communicate with the RS485 data bus.

As always, YMMV. Verify designs before using them. Don't mess with stuff you can't afford to break.
