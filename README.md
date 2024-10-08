# VERILOG-LCD-SPARTAN-3E-FPGA

## Project Description
This project demonstrates how to use Verilog to program and control an LCD display using the Spartan 3E FPGA development board. The primary objective is to interface an LCD with the FPGA to display characters or numerical data, showcasing the ability of hardware description languages (HDL) in managing peripherals like an LCD.

The project involves writing Verilog code to control the LCD, simulating the design using testbenches, and eventually deploying the design onto the Spartan 3E FPGA. It covers aspects such as signal timing, FSM (Finite State Machine) design for controlling the display, and proper use of FPGA I/O pins.

## Features
- **LCD Display Control**: Implement basic operations like displaying characters, clearing the screen, and moving the cursor.
- **FPGA Interfacing**: Demonstrates how to interface an LCD with the Spartan 3E FPGA board using Verilog.
- **Simulation and Testing**: Testbenches are provided to simulate and validate the functionality of the LCD control logic.

## Project Structure
- **`src/`**: Contains Verilog source files for the LCD control logic.
- **`testbench/`**: Includes testbench files used for simulation and testing.
- **`docs/`**: Documentation related to the project, including schematics and reference materials.
- **`constraints/`**: UCF (User Constraints File) for mapping FPGA pins to the LCD connections.

## Prerequisites
- **Xilinx ISE Design Suite**: Required for synthesizing and simulating the Verilog code.
- **Spartan 3E FPGA Development Board**: The FPGA board used for this project.
- **LCD Module**: A compatible LCD display connected to the Spartan 3E FPGA board.

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MinhThien-2702/VERILOG-LCD-SPARTAN-3E-FPGA.git
   cd VERILOG-LCD-SPARTAN-3E-FPGA

2. **Open the project in Xilinx ISE**:

Open Xilinx ISE Design Suite.
Create a new project and add the Verilog source files from the src/ directory.
Set up the constraints using the UCF files in the constraints/ directory.

3. **Compile and Synthesize**:

Compile the Verilog code to ensure there are no syntax errors.
Synthesize the design to generate the bitstream file for programming the FPGA.

4. **Simulate the Design**:

Use the provided testbench files in the testbench/ directory to simulate the LCD control logic.
Verify that the simulation output matches the expected behavior.

5. **Program the FPGA**:

Connect the Spartan 3E board to your computer.
Use the generated bitstream file to program the FPGA.
Connect the LCD to the FPGA following the documentation provided.

6. **Run the Project**:

Once the FPGA is programmed, observe the output on the LCD display.
Modify the Verilog code as needed to customize the display functionality.

## Contributing
Contributions are welcome! If you have improvements or new features to add, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any questions or feedback, please contact Nguyễn Minh Thiện at minhthien2047@gmail.com