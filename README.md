# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three
binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![316380387-d0433287-bca1-4a42-941b-7ebe73f982fa](https://github.com/velupradeep/FULL_ADDER_SUBTRACTOR/assets/150329341/d303e2db-493a-4378-b578-bc203e43a82e)
![316380435-89454d27-9645-4632-a76b-83fd89b93be1](https://github.com/velupradeep/FULL_ADDER_SUBTRACTOR/assets/150329341/860e63f9-aad0-4ac6-a50e-1021410fc7ff)


**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
```
module exp04(a,b,c,sum,carry,BO,DIFF);
input a,b,c;
output sum,carry,BO,DIFF;
//FULL ADDER
assign sum = a^b^c;
assign carry = (a&b) | (b&c) | (a&c);
wire a0;
not (a0,a);
//FUKK SUBTRACTOR
assign DIFF = a^b^c;
assign BO = (a0&b) | (b&c) | (a0&c);
endmodule

```

Developed by: Pradeep V RegisterNumber:212223240119
*/

**RTL Schematic**
![316380018-6e9a0272-f5ff-4c66-a05c-fe4ca977de81](https://github.com/velupradeep/FULL_ADDER_SUBTRACTOR/assets/150329341/0648244b-82bf-4654-9868-9b470d8be731)

**Output Timing Waveform**
![316380043-ac6a4ddd-bf53-4d24-a049-082f31171294](https://github.com/velupradeep/FULL_ADDER_SUBTRACTOR/assets/150329341/de17215a-0167-4f2e-9088-d563c77dbc84)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



