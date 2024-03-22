# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: NITHISH R
RegisterNumber:212223040135
## program
## module combinationalcircuit(A,B,C,D,F1);
## input A,B,C,D;
## output F1;
## wire x1,x2,x3,x4,x5;
## assign x1=(~A)&(~B)&(~C)&(~D);
## assign x2=(A)&(~C)&(~D);
## assign x3=(~B)&(C)&(~D);
## assign x4=(~A)&(B)&(C)&(D);
## assign x5=(B)&(~C)&(D);
## assign F1=x1|x2|x3|x4|x5;
## endmodule 





**RTL realization**
![Screenshot 2024-03-22 135232](https://github.com/NithishR15/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870685/021f7695-90d3-4cdd-820f-39bf29f5230e)

## Truth table
![Screenshot 2024-03-22 135353](https://github.com/NithishR15/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870685/04a0ca4f-f113-4206-bbe1-61131b52feb7)



**Timing Diagram**
![Screenshot 2024-03-22 135501](https://github.com/NithishR15/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870685/c5770d0a-5a24-485d-87a9-5141364be059)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

