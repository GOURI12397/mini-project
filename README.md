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
