# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/

## Output:
HALF SUBTRACTOR:
LOGIC DIAGRAM
![212878777-38549802-1273-44e8-9f04-f923188fea27](https://user-images.githubusercontent.com/119475762/214550637-52d204bc-3f31-4b5c-b2f7-1320d2e71f3a.png)

TRUTH TABLE:
![212879600-002737cf-0a82-473f-b6ec-56d0ab059b40](https://user-images.githubusercontent.com/119475762/214550861-8f3f1ecc-c3a8-4d0e-aec5-a62d179827b6.png)

##  RTL realization
![212879859-b64d2705-0585-4719-82d1-129491d9c236](https://user-images.githubusercontent.com/119475762/214550989-f2354aa8-3672-4d80-acf4-9fc020271d6d.png)

## Timing diagram 
![212880018-74d4e40d-7e63-427f-8500-60cd290cf934](https://user-images.githubusercontent.com/119475762/214551056-6a344af8-5978-4b7e-9e79-6d680cd1ceca.png)
 
 FULL SUBTRACTOR
LOGIC DIAGRAM:
![212880379-64e48ea8-0b02-4bdd-ac5f-e0c505871e58](https://user-images.githubusercontent.com/119475762/214551325-328c8e9d-b1e8-474d-ba17-c106c82e5ca1.png)

TRUTH DIAGRAM:
![212882200-fd2e63cb-7170-4381-9c09-a9ffb5f6a611](https://user-images.githubusercontent.com/119475762/214551403-f6696eb3-4e37-41a4-9115-0ce1697346f9.png)

RTL REALIZATION
![212882700-848bf97e-55f7-4a44-b7c3-0a8fb555d883](https://user-images.githubusercontent.com/119475762/214551664-7687985c-9f06-4f88-bf23-5992fc4cad84.png)

TIMING DIAGRAM
![212882876-7945b928-d45d-4308-8cf3-7ade90626b91](https://user-images.githubusercontent.com/119475762/214551750-31bf7858-db17-4201-b9d3-3fed813a8daa.png)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
