

# 🖥️ 16-Bit Bus-Based Computer Architecture

This project implements a simplified 16-bit computer system based on Mano basic bus architecture. It models the core functional units of a classic computer design, focusing on instruction processing, data movement, and control sequencing.

## 🚀 Features

* **16-bit Data Path**
* **Registers**:

  * `AC` (Accumulator)
  * `DR` (Data Register)
  * `IR` (Instruction Register)
  * `TR` (Temporary Register)
  * `PC` (Program Counter)
  * `INPR` (Input Register)
  * `OUTR` (Output Register)
* **Common Bus System**: Used for internal data transfer between all components
* **Sequence Counter (SC)**: Controls the timing and sequencing of micro-operations
* **Control Logic**: Decodes instructions and manages operation phases
* **Memory Unit**: Addressable memory to store instructions and data
* **Basic Instruction Set**: Includes `LDA`, `ADD`, `STA`, `INC`, `CLR`, etc.
* **Clock-Driven Operation**: Each micro-operation is driven by a system clock cycle

## ⚙️ Architecture Overview

![image](https://github.com/user-attachments/assets/0311a47d-2d11-4fd0-b01e-9455e1aa52b0)
![image](https://github.com/user-attachments/assets/059c24a7-0956-45c2-b98d-7d6fbc378731)
![image](https://github.com/user-attachments/assets/d8fd83d1-56bc-41ca-b08e-b32445be9080)
![image](https://github.com/user-attachments/assets/92875f2f-9990-4f5b-8ced-f41bdcc972a2)
![image](https://github.com/user-attachments/assets/d4976097-8aef-4ce0-a37d-04d9cd39304c)





## 🛠️ Implementation Details

* Built using Proteus 8 pro 
* Control signals are generated via sequence counter and decoded instruction bits
* Supports interrupt handling using input/output registers

## 📚 Learning Objectives

This project demonstrates:

* How a basic CPU works under the von Neumann architecture
* How control units manage sequences of micro-operations
* How registers interact over a shared bus
* How data flows from memory to processing units and output


## 📄 License

This project is open-source under the MIT License.

