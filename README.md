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
![318459772-b2f3f217-76b3-4f12-a7ba-54b5ff8b4838](https://github.com/velupradeep/FULL_ADDER_SUBTRACTOR/assets/150329341/17593dd2-e365-4d49-ad8d-0f05be406e69)
![318459838-b0b7195c-e9a1-4ebf-a594-72a65835e8b2](https://github.com/velupradeep/FULL_ADDER_SUBTRACTOR/assets/150329341/9215e7f0-8c05-4c17-8823-417dd56a4fd2)



**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
```
![318460056-379aef4f-5d02-4e49-acd2-9bdbe7391808](https://github.com/velupradeep/FULL_ADDER_SUBTRACTOR/assets/150329341/4fd9dfd2-5979-4776-ae56-b45bdba9451c)
![318460115-42baaa46-0fb3-43f8-9c61-7025ae54e0e0](https://github.com/velupradeep/FULL_ADDER_SUBTRACTOR/assets/150329341/d3087462-d6d7-45b5-8385-7f094b19391c)

```

Developed by: Pradeep V RegisterNumber:212223240119
*/

**RTL Schematic**
![318460221-c56fbbea-084b-4a25-a1af-893635e8e8cd](https://github.com/velupradeep/FULL_ADDER_SUBTRACTOR/assets/150329341/7019a725-11b0-4ac1-9fa9-feda7c1b7d49)
![318460314-6bc0e1a2-bc9c-46df-ab7f-0ffd68cd061d](https://github.com/velupradeep/FULL_ADDER_SUBTRACTOR/assets/150329341/7e521308-93ca-4527-8985-f760fa534ef6)


**Output Timing Waveform**
![318460383-b6aa2dc0-3c90-48c6-a54e-43bf869a17ce](https://github.com/velupradeep/FULL_ADDER_SUBTRACTOR/assets/150329341/a66c3711-bfc9-47d9-829d-63b1711bb3b7)
![318460421-44f71d89-0fc5-4dfc-915a-0363c0c87dda](https://github.com/velupradeep/FULL_ADDER_SUBTRACTOR/assets/150329341/2d8aacbc-6dcc-4cd9-966c-fda9e6b2703a)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



