# 28T_Full_Adder using 28nm CMOS Technology

## Abstract
Full adder is an essential component for the design and development of all types of processors like digital signal processors (DSP), microprocessors etc. In most of these systems adder lies in the critical path that affects the overall speed of the system.An adder is a digital circuit that performs addition of numbers and it plays an important role in today’s digital world. In processors and other kinds of computing devices, Adders are used in the arithmetic logic units. They are also utilized in other parts of the processors for calculating addresses, table indices, increment and decrement operations and other similar operations because it is the basic building block of on-chip libraries. Also, it can be used for the construction of many number representations and it is a trivial to modify an adder into an adder-subtractor. Full adder reduces circuit complexity and can be integrated in the calculators for addition and subtraction operations. At DSP oriented system and at networking side full adder is used mostly. Full adders can be cascaded (e.g.: ripple carry adder) easily so that one can make a cascade to add any number of bits that form the word- width of a system.
## Reference Circuit Details

Conventional CMOS Full Adder is the most basic full adder implementation techniques. Conventional CMOS Full Adder consists of 28 transistors. A, B and Cin are the inputs and Sum & Cout are the outputs. Static logic provides robustness against noise effects, so automatically provides a reliable operation. Pseudo NMOS pass-transistor logic and reduce the number of transistors required to implement a given logic function but these suffer from static power dissipation. On the other hand, dynamic logic requires less silicon area for implementation of complex function but charge leakage and charge refreshing are required which reduces the frequency of operation. This circuit uses both NMOS and PMOS transistors. In Conventional CMOS Full Adder, there are many leakage paths which lead to more sub threshold leakage.

## Reference Circuit Diagram
<img width="1371" alt="Reference_Ckt" src="https://user-images.githubusercontent.com/59500283/155388072-53c63be1-69c2-4d84-90e7-4cb95889fb67.png">

## Reference Circuit Waveform
<img width="1436" alt="Reference_Waveform" src="https://user-images.githubusercontent.com/59500283/155388452-6be190ea-c1f7-40b9-b905-c51b84594cd4.png">

## Desirable Truth Table
![Full_adder_Truth_Table](https://user-images.githubusercontent.com/59500283/155389650-b7823b97-2f40-4cf2-bb7a-72e5364af9b2.jpeg)




  
