# High-Performance-Binary-to-Gray-CodeConverter-using-Transmission-GATE
# Abstract
The circuit gives an idea to improve power efficiency and effective area of binary to gray code converter using very popular transmission gate technology. Some sensors send information in gray code. So this must be important to convert a given binary stream into its equivalent gray code. In this paper the binary to gray code converter has been developed using gate, circuit level. The conversion has beendone using conventional and transmission gate level and comparing these two in terms of power, number of transistors used and last but not the least area. The simulation result shows that binary to gray code converter using transmission gate has improved power efficiency and area by 76.22% and 72.3% respectively.
# INTRODUCTION
Low power and area efficient technologies are the primeconcern for VLSI system designers. Together with that, the high speed binary to gray code converter that use low power consumption have indisputably become one of the most crucial components of a processor because they are mostly used in arithmetic logic unit.
 
Second term of consideration for designing of low power area efficient binary to gray code converter is delay which affects the overall performance of circuit to be concern.The extensive development in the field of portable system and cellular network has intensified the research efforts in low power micro-electronics. This paper concern with 3XOR gate as one unit which is the basic building block in various circuit especially arithmetic circuit .Here we propose a new design of XOR gate using transmission gate with CMOS inverter circuit. It cover less area compared to 12 transistor X-OR with CMOS circuit as well as less power with smaller delay.The strength of a signal is measured by how closely it approximates an ideal voltagesource.Transmission gates require lower switching energy and it reduces the count of transistors used to make different logic gates.In VLSI implementation, major problems are heat dissipation and power consumption. To solve this problem it is required to reduce power supply voltage, switching frequency and capacitance of transistor. Area, delay and power dissipation have emerged as the major concern of the designers. The performance of the complex logiccircuits is affected by XNOR-XOR circuits.To summarize, this paper focused on some of the performance criteria are considered in the designing and evaluation of this converter cells while some are utilized for the ease of design, robustness, silicon area, delay and last but not the least power consumption.The technology used in this paper i.e. Transmission gate use less area and less transistors compare with conventional design logic.
# Binary to Gray code converter
This code converter combinational circuit is designed to convert binary to gray code. The input code of code converter is binary and output code of code converter is gray code.

- Following truth table shows 4-bit binary to gray code converter:
![image](https://user-images.githubusercontent.com/100506927/155873334-7a5027e4-6d33-4e4f-9c39-d6b4495d4c1f.png)

- Logic circuit design of binary to gray code converter:

![image](https://user-images.githubusercontent.com/100506927/155873482-9ebee343-5802-43f4-952c-1b5a24099251.png)

- CMOS implementation using transmission gates:

![2-67bf544d19abcnb](https://user-images.githubusercontent.com/100506927/155874035-4a0f0459-ec16-4767-9219-ec447a0b4e36.jpg)

# Tools Used 
 - Synopsys Custom Compiler:  The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.
  
 - Synopsys Primewave:  PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.
  
 - Synopsys 28nm PDK:  The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.
  
# DESIGN APPROACH
- First of all, I have created a 2-bit XOR Gate to implement the circuit design:
 
 ![2022-02-25 (14)](https://user-images.githubusercontent.com/100506927/155874930-60726d70-a840-4740-bcaa-d7a930dbbc63.png)
- Now using the symbol of the above XOR Gate, I have now created the schematic of 4-bit Binary to Gray converter:
 
 ![2022-02-25 (15)](https://user-images.githubusercontent.com/100506927/155875024-e991971a-f442-421b-984c-cec7c7ba2b1f.png)
- TRANSIENT ANALYSIS:
 
 ![2022-02-25 (16)](https://user-images.githubusercontent.com/100506927/155875057-980a6af8-f890-462c-b7d6-70de77966b7f.png)
- Final WAVEFORM of 4-bit Binary to Gray Conerter:

![2022-02-25 (17)](https://user-images.githubusercontent.com/100506927/155875110-7674d916-7b88-472b-8447-1b8da21b0eeb.png)

# Author
- Shivani, B.Tech Electronics and Communication Engineering, J.C. Bose University of Science and Technology,YMCA.

# Acknowledgements
- [Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/)
- [Cloud Based Analog IC Design Hackathon](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')
- [Synopsys India](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')
- [Sameer Durgoji, NIT Karnataka](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')
- [Chinmay panda, IIT Hyderabad](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')

# References
- Saradindu Panda, A.banerjee, B.maji and Dr. A.K. Mukhopadhyay,“Power and delay comparison in between different types of full addercircuits”, International Journal of advanced research in electrical,electronics and instrumentation engineering, volume 1, issue3.pp.168-172, 2012.
- Swati Sharma and Rajesh Mehra, “Area and power efficient design ofXNOR-XOR logic using 65nm technology”, International Journal ofengineering and technical, pp.57-60, 2014.
- Neil H.E.Weste, David Harris and Ayan Banaerjee, “CMOS VLSIdesign”. Pearson Education,Inc., pp. 11, Third Edition, 2005.
- S,Goel.M.A. Elgamel, M.A. Bayoumi, and Y.Hanarty. “Designmethodologies for high performance noise-tolerant XOR-XNORcircuits,” circuits and systems I:Regular papers, IEEE Transactionson, vol.53,pp.817-878,2006.
