Parameterized FIR Filter in Verilog
This Verilog implementation demonstrates a parameterized Finite Impulse Response (FIR) filter.
FIR filters are widely used in digital signal processing applications for tasks such as filtering, noise reduction, and signal enhancement.

Overview
The FIR filter is designed to perform convolution between an input signal and a set of filter coefficients, producing an output signal.
This implementation allows for easy customization of filter length, coefficient values, and input data width.

Features
Parameterized filter length
Customizable coefficient values
Adjustable input data width


Files
fir_building_block.sv: Building block pof FIR filter.
fir_module.sv: Main Verilog module implementing the FIR filter.
module_tb.sv: Testbench module for simulation and verification of the FIR filter.
h_bin.dat: Text file containing filter coefficients.
inp_bin.dat: Input data in binary format.
README.md: This file providing information about the project.
