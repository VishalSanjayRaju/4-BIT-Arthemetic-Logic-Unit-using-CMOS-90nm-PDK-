4-BIT Arthimetic and Logic Unit using CMOS 90nm PDK
 
 This Projects presents a 4-bit Arithmetic Logic Unit (ALU) design and implementation using 90nm CMOS (Complementary Metal-Oxide-Semiconductor) technology. The ALU is a fundamental building block of any central processing unit (CPU) and is responsible for performing arithmetic and logical operations. The design process involves the schematic design of adder, subtractor, comparator, divider, multiplier, 1’s complement, 2’s complement, and shift register for the development of the ALU architecture followed by simulation of the design using Cadence Virtuoso EDA (Electronic Design Automation) tools. The implementation phase focuses on layout design to ensure the functionality and manufacturability of the ALU. The performance metrics such as power consumption, area, and speed are analyzed to validate the efficiency of the design. The successful realization of the 4-bit ALU showcases the potential for advancements in integrated circuit design and the practical application of CMOS technology in modern computing systems.

Architecture

<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/ef59c3d2-0956-4a0f-af58-1dd63ece121f" />




In this project, the methodology for designing the 4-bit adder, 4-bit subtractor, 4-bit magnitude 
comparator, 3:8 decoder and 4-bit 1’s complement was based on 90nm CMOS technology 
using Cadence Virtuoso. The first step involved creating the schematics for each of the 
components. For the 4-bit adder and subtractor, full adders and subtractors were designed using 
CMOS logic gates, ensuring that both operations could handle 4-bit inputs and produce 
accurate sum and difference outputs. The 4-bit magnitude comparator was designed to compare 
two 4-bit inputs and generate the corresponding output based on equality, greater than, or less 
than conditions. The 3:8 bit decoder will decode the input 3-bit and give the 8-bit output. The 
4-bit 1’s complement will invert the input 2 4-bit and give 2 4-bit as output. After the schematic 
design, the next step was to create the corresponding test benches for all five blocks. These test 
benches were constructed to validate the functionality of the blocks under various input 
conditions, simulating both normal and edge cases. 
Following the schematic and test bench creation, the waveform analysis was performed using 
Cadence Virtuoso’s simulation tools. The simulation allowed for observing the behaviour of 
the designed circuits under different input combinations and ensured that the outputs met the 
expected results. By analysing the waveforms, any discrepancies in the operation, such as 
incorrect outputs or timing issues, could be identified and rectified. The simulation results 
confirmed the correct functionality of the 4-bit adder, subtractor, magnitude comparator, 1’s 
complement and decoder. This process of schematic design, test bench creation, and waveform 
analysis ensured the reliability and correctness of the individual blocks, laying a solid 
foundation for their integration into a larger ALU design. 

COMPLETE SCHEMATIC OF ALU

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/eece824d-b61b-432e-a75d-7448a4da938b" />

COMPLETE LAYOUT OF THE ALU

<img width="653" height="727" alt="custom_layout" src="https://github.com/user-attachments/assets/c0f726b5-5428-45e3-b664-1ade5d3743fd" />

REFERENCES

[1] L. Dhulipalla and A. Lourts Deepak, "Design and implementation of 4-bit ALU using 
FINFETS for nano scale technology," International Conference on Nanoscience, 
Engineering and Technology (ICONSET 2011), Chennai, India 

[2] S. Balaji Ramakrishna, A. G. Prasad, P. Anand and T. Aravind, "High Performance GDI
ALU Using 10T Adder Cells," 2018 3rd IEEE International Conference on Recent Trends 
in Electronics, Information & Communication Technology (RTEICT), Bangalore, India, 
2018 

[3] Jin-Young Kim, Sehoon Kim and Joonhee Kang, "Construction of an RSFQ 4-bit ALU 
with half adder cells," in IEEE Transactions on Applied Superconductivity, vol. 15, no. 2, 
pp. 308-311, June 2005 

[4] A. Pathak, S. Gupta and B. Jena, "Design and Evaluation of a 4-bit ALU and RAM 
System: A Step towards Ultra-Low Power Computing," 2023 International Conference on 
Next Generation Electronics (NEleX), Vellore, India, 2023 

[5] E. A. Cortés-Barrón, M. A. Reyes-Barranca, L. M. Flores-Nava and A. Medina-Santiago, 
"4-Bit Arithmetic Logic Unit (ALU) based on Neuron MOS Transistors," 2012 9th 
International Conference on Electrical Engineering, Computing Science and Automatic 
Control (CCE), Mexico City, Mexico, 2012 

