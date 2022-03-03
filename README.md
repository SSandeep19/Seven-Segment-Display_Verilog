# Seven-Segment-Display_Verilog
A module in Verilog to control Seven-Segment display. This module is designed and implemented for Xilinx Artix-7 FPGA.
The seven-segment display used in a Xilinx Artix-7 FPGA is a common anode diaplay with 8 digit display.
The common anode signals are avalable as eight pins. For Nexys A7 board the anode should be diven low to light up a particular seven-segment and for a particular segment to light up the respective cathode must be driven low.

The Sevensegment.V file is the verilog file controlling the seven-segment display.

Two inputs are provided to display two different values. When input A is high the seven segment will be displaying '7' on the right most digit and when input B is high it will be displaying 'R' on the digit infront of previous digit.
