### NAME:SUGESHWA S
### REG NO:24900706
### EXPERIMENT 4:FULL ADDER AND FULL SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

### AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

### Full Adder and Full Subtractor

### Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

### Figure -1 FULL ADDER

### Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

### Truthtable

### Full adder:
![image](https://github.com/user-attachments/assets/626153d0-3b1a-4d5f-b097-ba235a2a10d5)

### Full subtractor:
![image](https://github.com/user-attachments/assets/c308d644-9e81-4135-b8ae-f4701ffd35b4)

### Procedure

Write the detailed procedure here

### Program:

![Screenshot 2024-12-12 111159](https://github.com/user-attachments/assets/0eb673bb-b13d-4593-b3f6-fecdec4a4997)


### RTL Schematic
![Screenshot 2024-12-12 111141](https://github.com/user-attachments/assets/a1759d3c-73d8-4224-82db-211dd5d1292c)

### Output Timing Waveform
![image](https://github.com/user-attachments/assets/991cff5a-af37-47f6-9797-16a2b53b6d41)

### Result:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



