# Muhammed Muhad

Electronics & Communication Engineering student based in Kochi, India.
I'm interested in communication systems, RF engineering, VLSI and digital/analog design, FPGA and DSP.

## Projects

**Digital design & VLSI**
- [riscv-pipelined-cpu](https://github.com/Muhad33/riscv-pipelined-cpu): 5-stage pipelined RV32I core in Verilog with forwarding, hazard detection, a Python golden model, random-program verification and Yosys synthesis
- [riscv-gdsii-openlane](https://github.com/Muhad33/riscv-gdsii-openlane): the RV32I core taken from RTL to a signed-off GDSII layout on SkyWater sky130 with LibreLane/OpenLane 2: 50 MHz with timing met in all 9 corners, clean DRC/LVS/antenna, clock-period sweep and gate-level simulation of the final netlist
- [verilog-uart](https://github.com/Muhad33/verilog-uart): UART transmitter/receiver in Verilog with 16x oversampling, optional parity and self-checking testbenches
- [8bit-ALU](https://github.com/Muhad33/8bit-ALU): 8-bit ALU in Verilog (14 operations, zero/carry/overflow flags) with a self-checking testbench

**Communications & DSP**
- [ofdm-transceiver](https://github.com/Muhad33/ofdm-transceiver): end-to-end OFDM link over Rayleigh multipath with LS channel estimation, ZF/MMSE equalization, PAPR analysis and fixed-point test vectors
- [ber-awgn-simulator](https://github.com/Muhad33/ber-awgn-simulator): Monte Carlo BER of BPSK, QPSK and 16-QAM over AWGN, checked against theory

**RF engineering**
- [openems-patch-antenna](https://github.com/Muhad33/openems-patch-antenna): 2.45 GHz inset-fed patch antenna on FR4, designed analytically, simulated and tuned with openEMS FDTD (mesh convergence, S11 −46.8 dB, 3.3 dBi gain, NF2FF patterns) and exported to Gerber/KiCad for fabrication, with a NanoVNA measurement workflow
- [rf-amplifier-design-toolkit](https://github.com/Muhad33/rf-amplifier-design-toolkit): single-stage LNA design from S-parameters: stability, gain and noise circles, lumped and microstrip matching, Monte Carlo tolerance analysis
- [smith-chart-matching-tool](https://github.com/Muhad33/smith-chart-matching-tool): L-section and single-stub impedance matching with Smith chart visualization

**FPGA**
- [FIR-Audio-Filter](https://github.com/Muhad33/FIR-Audio-Filter): IIR biquad audio filters (LPF/HPF/BPF) designed in MATLAB/Simulink, generated with HDL Coder and deployed on a Xilinx Zedboard with the ADAU1761 codec

## Tools

- **HDL & EDA:** Verilog, Icarus Verilog, GTKWave, Yosys, Vivado, MATLAB/Simulink HDL Coder
- **ASIC flow:** LibreLane / OpenLane 2, OpenROAD, OpenSTA, Magic, KLayout, Netgen, SkyWater sky130 PDK
- **EM simulation:** openEMS (FDTD), CSXCAD
- **Languages & libraries:** Python (NumPy, SciPy, Matplotlib, scikit-rf), C, RISC-V assembly
- **Hardware:** Xilinx Zedboard, Arduino

## Contact

[LinkedIn](https://www.linkedin.com/in/muhad-/) · muhadpsy@gmail.com
