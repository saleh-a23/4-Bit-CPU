# CPU in Logisim

This project is a simple 4-Bit CPU implemented in Logisim.
It demonstrates the fundamentals of Computer Architecture and Organization by combining essential components into a working processor.

## Features
- **Arithmetic and Logic Unit (ALU)**  
  - Addition  
  - AND  
  - OR  
  - XOR  

- **Core Components**  
  - **Register File** – for storing operands and results  
  - **Program Counter (PC)** – keeps track of instruction execution  
  - **ROM** – stores program instructions  
  - **Control Signals** – manage data flow and operation selection  

## File
- `CPU.circ` → main Logisim project file.

## How to Run
1. Install Logisim.  
2. Open `CPU.circ`.  
3. Load the circuit, run the clock, and observe how instructions are fetched from ROM, decoded, and executed.  

## Instruction Set
This CPU currently supports:
- **ADD** – addition of two registers  
- **AND** – bitwise AND  
- **OR** – bitwise OR  
- **XOR** – bitwise XOR  

## Notes
- This project is designed as an **educational CPU** for learning Computer Arcitecture and Organization.  
- Further improvements can be made.  

