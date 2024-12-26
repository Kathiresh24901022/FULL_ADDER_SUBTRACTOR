### NAME:KATHIRESH.M

### REG NO:24901022

### EXPERMENT 4 :FULL ADDER and FULL SUBTRACTOR

### AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

### EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

### FULL ADDER AND FULL SUBTRACTOR:

### FULL ADDER:

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

### FIGURE -1 FULL ADDER:

### FULL SUBTRACTOE:

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

### TRUTHTABLE:
### FULL ADDER:
![Screenshot 2024-12-12 105807](https://github.com/user-attachments/assets/7bd156b6-462b-4a04-8c93-e0577ab03f3b)

### FULL SUBRACTOR:
![Screenshot 2024-12-12 105819](https://github.com/user-attachments/assets/66eb2e7c-a1ad-44e7-b816-da46bc426f56)


### PROCEDURE:

1.Type the program in Quarts software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic digram.

4.Create nodes for inputs and output to generate the timing digram.

5.For different input combinations generate the timing diagram.
### PROGRAM:

![Screenshot 2024-11-28 115120](https://github.com/user-attachments/assets/3ab473f6-bcc5-4e5b-afaa-7d53789080bd)


### TIMING DIAGRAM:

![Screenshot 2024-11-28 115245](https://github.com/user-attachments/assets/fc964cab-3df2-4446-a143-70402eca03ca)

### RTL:
![Screenshot 2024-12-12 105707](https://github.com/user-attachments/assets/e2d7a81b-5e86-4431-969d-8f86e65951ed)

### RESULT:

 The Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software using verilog programming successfully.
