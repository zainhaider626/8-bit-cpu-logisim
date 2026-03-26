# 8-bit-cpu-logisim
A custom 8-bit Central Processing Unit (CPU) designed and simulated entirely from scratch using Logisim. It features a complete custom Arithmetic Logic Unit (ALU), dedicated registers, and a hardwired control unit built from basic logic gates.


# 8-Bit CPU in Logisim

## Project Overview
A custom 8-bit Central Processing Unit (CPU) designed and simulated entirely from scratch using Logisim. It features a complete custom Arithmetic Logic Unit (ALU), dedicated registers, and a hardwired control unit built from basic logic gates.

## Architecture Details
This project explores the fundamental principles of computer architecture and digital logic design. The core components include:
* **Arithmetic Logic Unit (ALU):** Handles 8-bit mathematical and logical operations.
* **Control Unit:** Decodes instructions and orchestrates the flow of data across the internal bus.
* **Register File:** Custom registers for temporary data storage.
* **Memory Mapping:** Interfaces with RAM/ROM for fetching instructions and storing operational data.
* **Program Counter (PC):** Tracks the memory address of the next instruction to be executed.

## Instruction Set Architecture (ISA)
The CPU operates on a custom instruction set. Basic operations include:
* **LDA / STA:** Load and Store data between registers and memory.
* **ADD / SUB:** Basic arithmetic operations.
* **AND / OR / NOT:** Bitwise logical operations.
* **JMP:** Jump to specific memory addresses.
* **HLT:** Halt execution.

## How to Run the Simulation
1. Download and install [Logisim](http://www.cburch.com/logisim/).
2. Clone this repository or download the `.circ` files.
3. Open the main circuit file in Logisim.
4. Load your machine code or test program into the ROM module.
5. Enable the clock ticks (`Ctrl + K` or `Simulate > Ticks Enabled`) to watch the CPU execute the code.
