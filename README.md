# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/
Logic symbol & Truthtable
RTL realization

### Output:
![hal add pro](https://github.com/AnbuSelvanS7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151528411/37403bd9-60f7-4416-b6e4-3db203790158)

![full add pro](https://github.com/AnbuSelvanS7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151528411/1a2c3164-9a14-48c1-a7fc-81b701f28567)


### RTL
![rtl hal](https://github.com/AnbuSelvanS7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151528411/c8bc5a81-669c-47b4-bfe3-276f6d9397c1)
![rtl full](https://github.com/AnbuSelvanS7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151528411/a420f00a-5c62-414b-96b2-536b600478ad)


### TIMING DIAGRAM
![hal time](https://github.com/AnbuSelvanS7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151528411/39c8c468-f82d-477f-b51f-b78baeadd1e4)

![ful time](https://github.com/AnbuSelvanS7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151528411/b883bd1b-d003-489f-b232-958e7f794403)

### TRUTH TABLE 
![TT hal](https://github.com/AnbuSelvanS7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151528411/7751ab31-a784-437a-8aa4-49689a6fecda)

![TT full](https://github.com/AnbuSelvanS7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151528411/10fe06fa-0663-4f5d-b356-5ca7d61ecb3e)



### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
