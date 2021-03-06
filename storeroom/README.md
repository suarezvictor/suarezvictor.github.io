# Embedded Storeroom

A collection of tools for embedded development. The main idea is to have clear what's the current list of useful development tools for embedded systems, since there are many it's difficult to know them all.
Ideally a brief comment of what they do and how they interact tools too should be added, and a link. The tool should be run from the **commandline** or be a plugin of another tool that does! Libraries are listed [here](LIBS.m)

If some tool is missing or you know how to improve any description, please contact!

# SOFTWARE

## Compilers
**CNU GCC**: C/C++ compiler https://gcc.gnu.org/<br>
**Clang**: C/C++ compiler https://clang.llvm.org/<br>

## Debuggers and frontends
**GDB**: debugguer for GNU GCC https://www.gnu.org/software/gdb/<br>
**cdtdebug**: eclipse CDT standalone debugger: https://wiki.eclipse.org/CDT/StandaloneDebugger<br>
**gdbwave**: (TBD once I understand this advanced tool): https://github.com/tomverbeure/gdbwave<br>

## Simulators
**Verilator**: Verilog simulator https://www.veripool.org/verilator/<br>
**CXXRTL**: Yosys simulation backend https://github.com/YosysHQ/yosys/tree/master/backends/cxxrtl<br>
**GHDL**: simulator for VHDL http://ghdl.free.fr/<br>
**Icarus Verilog**: imulation and synthesis http://iverilog.icarus.com/<br>

## Synthesis tools
**Xilinx Vivado**: https://www.xilinx.com/products/design-tools/vivado.html<br>
**Intel Quartus}**: https://www.intel.la/content/www/xl/es/software/programmable/quartus-prime/overview.html<br>

## Place and route
**NextPNR**: Place and route https://github.com/YosysHQ/nextpnr<br>
**VtR**: Verilog to routing: https://verilogtorouting.org/<br>

## HDLs
**Verilog**<br>
**VHDL**<br>
**Chisel**: https://www.chisel-lang.org/<br>
**SpinalHDL**: https://github.com/SpinalHDL/SpinalHDL
**migen**: https://m-labs.hk/gateware/migen/<br>
**Amaranth**: https://github.com/amaranth-lang/amaranth<br>
**PipelineC**: C-like HDL with autopipelining https://github.com/JulianKemmerer/PipelineC<br>
**CflexHDL**: Experimental C-like HDL aimed to fast simulation: https://github.com/suarezvictor/CflexHDL<br>
**Silice**: https://github.com/sylefeb<br>
**Wyre**: https://github.com/nickmqb/wyre<br>

## SoC generators
**LiteX**: Based on migen, lots of interesting cores! https://github.com/enjoy-digital/litex<br>

## Formal tools
**SymbiYosys (sby)**: formal hardware verification https://github.com/YosysHQ/sby<br>

## Testbench
**mcy**: (Yosys) testing testbenches coverage: https://github.com/YosysHQ/mcy<br>

## Bitstream generation / manipulation
**altsyncram**: Manipulate quartus MIF files https://tomverbeure.github.io/2021/04/25/Intel-FPGA-RAM-Bitstream-Patching.html

## Software for embedded devices
**Micropython**: python for microcontrollers https://micropython.org/<br>

## Flashing tools
**OpenOCD**: Debugging and flash tool, interacts with GDB. https://openocd.org/<br>
**OpenFPGALoader**: for FPGAs https://github.com/trabucayre/openFPGALoader<br>

## Waveform viewers/editors/generators
**GTK**: http://gtkwave.sourceforge.net/<br>
**Wavedron**: Rendering and editor for the web https://wavedrom.com/

## IDEs (only if supports embedded development)
**IceStudio:** IDE for FPGA development. Based on IceStorm/Apio https://icestudio.io/<br>
**Platform.io**: https://platformio.org/<br>
**Eclipse CDT**: https://www.eclipse.org/cdt/<br>

# HARDWARE

## JTAG
**RPi pico** based dongles: https://github.com/phdussud/pico-dirtyJtag/<br>



