# x86-Emulator (NEMU) - NJU ICS Programming Assignment

## Overview
The fundamental way to understand "how a program runs on a computer" is to build a complete computer system from scratch. This project is a simplified yet functional **x86 architecture emulator** named **NEMU** (NJU EMUlator), developed as part of the *Introduction to Computer Systems* (ICS) course at **Nanjing University**.

The project involves implementing a subset of the x86 instruction set, memory management units, and I/O devices. The ultimate goal is to run the typing game on this self-built emulator, exploring the core principles of program execution and hardware-software interfaces.

---

## Key Features & Milestones
I have successfully completed all mandatory and optional components, passing all validation tests at each stage.

### PA 0: Development Environment
* Established a robust Linux development environment.
* Familiarized with GNU toolchains (GCC, Make, GDB) and project scaffolding.

### PA 1: Data Representation & Computation
* **Data Storage:** Implemented physical memory storage logic.
* **Integer & Floating Point:** Realized ALU operations and IEEE 754 floating-point arithmetic.

### PA 2: Instruction Execution & Program Loading
* **Instruction Cycle:** Developed the Decode-Execute loop for the x86 instruction subset.
* **ELF Loading:** Implemented an ELF loader to parse and load programs.
* **Debugger (Optional):** Enhanced the internal monitor with watchpoints.

### PA 3: Memory Management
* **Cache Simulation:** Implemented a high-performance Cache simulator.
* **Segmentation & Paging:** Realized Protected Mode, GDT, and **Virtual Address Translation**.

### PA 4: Exceptions, Interrupts & I/O
* **Interrupt Handling:** Implemented IDT and response logic for traps/faults.
* **Peripheral & I/O:** Simulated keyboard, VGA, and timer devices.
* **Game Porting (Optional):** Successfully ported and ran **"Paladin"** on the emulator.

---

## Technical Stack
* **Language:** C / C++
* **Tools:** Makefile, GDB, Git, Linux
* **Architecture:** x86 (ISA subset)
