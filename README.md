# FPGA Arcade Game Design | VHDL, Basys 3 

Developed a real-time "Dodge Falling Blocks" arcade game on a Xilinx Artix-7 FPGA (Basys
3) using VHDL.

-Designed a custom VGA Controller to drive a 640x480 display at 60Hz, implementing a
clock divider to step down the system clock from 100 MHz to 25 MHz.

-Implemented hardware-level game logic including collision detection, pseudo-random
object generation, and player movement state machines.

-Mapped physical I/O (buttons) to digital control signals and generated 12-bit RGB video
output for the monitor interface.
