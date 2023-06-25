# mini-project
# Synopsis
## Abstarct
Static Random Access Memory (SRAM) is one of the core components in the digital world.
Generally, it consumes enormous amount of power and die area. Thereby extensive research
in SRAM is in progress related power dissipation, memory chip area and supply voltage
requirement. In this paper SRAM analysis in terms of Static Noise Margin, Data Retention
Voltage, Read Margin (RM) and Write Margin (WM) for low power application is
considered. Static Noise Margin (SNM) is one of the most essential parameters for memory
design because it affects both read and write margin. SNM is related to the threshold voltages
of the Negative Metal Oxide Semiconductor (NMOS) and Positive Metal-Oxide
Semiconductor (PMOS) devices of the SRAM cell. High Read and Write Noise Margin are
also significant challenges in the design of SRAM. Data Retention Voltage (DRV) is
calculated for 6T-SRAM cell for high-speed application. Different types of curves are taken
straightforwardly to analyses the 6t-SRAM by varying the size of the transistor. Performance
analysis is estimated in 6T-SRAM designed and implemented in 90nm technology.

## Introduction
Stability in SRAM when designed using the Complementary Metal–Oxide– Semiconductor (CMOS) technologies generally depend on the SNM. SRAM memory technology is used because of its speed and robustness. As the device is scaled down in sizes several design challenges arise in the nanometer size SRAM design. In an SRAM cell operation generally supply voltage scaling is performed. The minimum voltage also referred as DRV is the needed for a SRAM cell to store the data. Reducing the VDD reduces subthreshold leakage current and gate leakage. Conversely, when VDD is reduced too far data loss occurs in SRAM. The DRV is applied to preserve data in the bit cells of SRAM. For analyzing high speed SRAM calculation of read margin and WM is necessary. A significant vision in this paper is to analyze 6T SRAM cell is based on noise marginal by evaluating the DRV, Read Margin and Write Margin. Nowadays focus is on low supply voltage which reduces the SNM. The stability of SRAM cell can be analyzed based on the SNM value because performance is proportional to the SNM. Therefore, as SNM reduces the performance of SRAM cell also reduces or vice versa. For improving the performance of a 6T SRAM cell parameter such as Cell Ratio (CR), Pull up Ratio (PR), Voltage Supplies (VDD) is generally considered. 

## Block Diagram
![Untitled](https://github.com/GOURI12397/mini-project/assets/119784144/85507c0c-a9cb-4d37-81cf-8c450839b64c)

## REFERENCES
1. Shin C, Cho MH, Tsukmoto Y, Nguyen BY, Mazure C, Nikolic B, Liu TTK. Performance and area scaling benefits of FD-SOI technology for 6-T SRAM Cells at the 22-nm Node, IEEE Transactions on electron devices. 2010 Jun; 57(6). 13. Chandrak
2. Keerthi R, Chen H. Stability and SNM analysis of low power SRAM. IEEE International Instrumentation and Measurement Technology Conference, Victoria Canada; 2008 May. p.1541–4.
3. Christiensen D.C. Arandilla, Anastacia B. Alvarez, and Christian Raymund K. Roque “Static Noise Margin of 6T SRAM Cell in 90-nm CMOS” IEEE UKSim 13th International Conference on Modelling and Simulation, pp534-539, 2011.
4. Prajna Mishra, Eugene John and Wei-Ming Lin “Static Noise Margin and Power Dissipation Analysis of various SRAM Topologies” IEEE 56th International Midest Symposium on Circuits and System.
5. Calhoun, B.H., and Chandrakasan, A.: 'Analyzing static noise margin for sub-threshold SRAM in 65nm CMOS', Solid-State Circuits Conference, Proceedings of the 31st European, 2005, pp. 363-366ms (MWSCAS), pp469-472, 2013.
6.. Arora G, Poonam, Singh A, SNM Analysis of SRAM Cells at 45nm, 32nm and 22nm technology, International Journal of Engineering Research and General Science. 2014 Jun–Jul; 2(4):785–9.

