# SPU (work in progress)
Sigma Processing Unit: an indelendently driveable 8-bit CPU designed by myself, inspired by the interface used to communicate with the 6502 microprocesser and Ben Eater's 8 bit cpu. I have also written an article on this project! https://thomasdli.notion.site/Designing-An-8-Bit-CPU-Thomas-Li-f7da20de04c84557adcc27d55567141a

<img width="999" alt="image" src="https://user-images.githubusercontent.com/77999105/188357888-0de9cc34-74df-4725-9b52-c6da3d99f465.png">

(pcb)

<img width="869" alt="image" src="https://user-images.githubusercontent.com/77999105/188374037-af4aeea7-f655-4e7e-8a70-22cf283e15ec.png">

(pcb layout)

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
- design a VIA for the processor for I/O

## downloading design

This CPU was designed using 74LS series ICs from Texas Instruments, and was made using Autodesk Eagle.
