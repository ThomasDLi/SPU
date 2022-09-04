# SPU (work in progress)
Sigma Processing Unit: an indelendently driveable 8-bit CPU designed by myself, inspired by the interface used to communicate with the 6502 microprocesser and Ben Eater's 8 bit cpu.
<img width="593" alt="image" src="https://user-images.githubusercontent.com/77999105/187117492-b33b1505-24b4-45d1-8b19-c9c5a9dc9f05.png">
(zoomed out screenshot of the schematic)

## Specs
- 8 bit address bus for a total of 256 memory locations (including program counter, which starts at address 0, and can also go up to 255)
- 8 bit data bus

- full 8 bit load immediate instructions supported

- 2 general purpose registers
- add/subtraction for ALU with conditional junps for both Zero and Carry flags

- 16 instructions avaliable currently with minimal edits required in order to increase up to 128 instructions
- 16 clock cycles required for each instruction

- R/W flag for memory

- support for external I/O

- turing complete

- maximum clock speed of idfk

### instruction set

- still writing firmware

## todo

- write firmware
- create pcb
- design a VIA for the processor for I/O
- design ram and motherboard

## downloading design

This CPU was designed using 74LS series ICs from Texas Instruments, and was made using Autodesk Eagle.
