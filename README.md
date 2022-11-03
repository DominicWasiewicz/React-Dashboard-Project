 # E-Commerce Application   

### Table of Contents

- [Description](#description)
- [Description of Modules](#description-of-modules)
- [New Instruction “AND”](#new-instruction-and)

---

## Description

This project uses the React framework to build and deploy a fully functional dashboard with many components. The dashboard includes many important metrics such as earnings, yearly salaries, sales overview,  and recent transactions. The dashboard has three pages where you can view customer orders, current employees, and customers. Many crucial applications have been implemented into the dashboard. These applications include a fully functional calendar, a Kanban scheduling system, a text editor, and a color-picker for users to theme their application. The dashboard also includes several interactive charts to display information.

## Technologies

- HTML/CSS
- JavaScript
- React
- Syncfusion 

[Back To The Top](#e-commerce-application)

---

## Description of Modules

### Program Counter

The program counter holds the address of the instructions and passes down each instruction individually to the instruction memory. The instructions are then fetched from the instruction memory using the address. After passing it down, it increases the address by 1, basically moving on to the next instruction address. There are some cases where we have either a branch or jump instruction. In this case, the program counter takes the branch or jump instruction address from the decoder and the ALU sends a signal, allowing both the branch and jump instructions to execute. Overall the address increases by an increment of one unless there is a branch or jump instruction, the ALU signals either instruction is executed.

### CPU_top

The combination of all the modules, connecting all the individual modules together to function together as a unit.

### Instruction Memory

The instruction memory uses the address received from the PC and then fetches the instruction. The instruction is then sent to the decoder to be decoded. If the instructions are received, the load instruction command gets the instruction indexed by the address from PC.
 

### Decoder



### Functionality of The New Instruction AND

