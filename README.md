# 8-Bit-Microcomputer Using Logisim-Evolution

## Overview

This project involves the development of an 8-bit microcomputer using Logisim-Evolution, an open-source tool for designing and simulating digital logic circuits. The microcomputer performs basic arithmetic operations and displays the results on a 7-segment display.

## Project Description

### Components
- **Program Counter (PC)**
- **Memory Address Register (MAR)**
- **Random Access Memory (RAM)**
- **Instruction Register (IR)**
- **Control Unit (CU)**
- **Accumulator**
- **Arithmetic Logic Unit (ALU)**
- **Registers**
- **Output Register**

### Instructions and Operations
The microcomputer supports a set of 5 instructions:
- **LDA (0000):** Load data from RAM into the accumulator.
- **ADD (0001):** Add data from RAM to the accumulator.
- **SUB (0010):** Subtract data in RAM from the accumulator.
- **OUT (1110):** Output data from the accumulator to the display.
- **HLT (1111):** Halt the process.

### Timing and Execution
The operations of the microcomputer consist of six timing states, with three states dedicated to the fetch cycle and three to the execution cycle.

### State Diagram
Each instruction involves a series of states where data is transferred between different components of the microcomputer. The state diagram includes:

- **T1:** Connection between PC and MAR.
- **T2:** Counter starts counting.
- **T3:** Data fetched from MAR to IR.
- **T4 to T6:** Execution of instructions like LDA, ADD, SUB, and OUT.

## Results
The project successfully implements a basic 8-bit microcomputer capable of performing addition and subtraction, displaying results on a 7-segment display.

## Key Learnings
- The importance of the Control Unit in managing the overall operation.
- The fetch cycle is critical before every execution.
- Understanding the operation and design of digital circuits using Logisim-Evolution.

## Conclusion
This project provided valuable hands-on experience in designing a simple microprocessor system and understanding the basics of microcomputer architecture.

