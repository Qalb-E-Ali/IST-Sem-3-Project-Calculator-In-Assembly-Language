# IST-Sem-3-Project-Calculator-In-Assembly-Language
In our 3rd semester we created a calculator using assembly language for our course computer organization &amp; assembly language. The calculator features computing basic mathematical operations and algebraic expression.

# Theory:
We have designed the calculator in assembly language and used the following 13 functions:
1) Addition of two numbers          
2) Subtraction of two numbers          
3) Division of two numbers            
4) Multiplication of two numbers                    
5) Factorial a Number            
6) Computing power of any number       

Following formulas have been used:
1) a+b/2                         
2) (a + b)^2    
3) (a + b)^3 
4) (a - b)^3 
5) a^1 + b^2 + c^3 + d^4        
6) (a^3 + b^3) 
7) (a^3 - b^3)

# Implementation:

In the output window, the calculator interface defined by us is displayed to the user showing the list of 13 mathematical functions along with a few algebraic formulas with each function having its own serial number allotted to it. The user is then asked to input the serial number mention against the desired function the user wants to perform. After confirming the desired selection, the user is then again asked to input the values of variable that will be used to compute the selected mathematical function or formula. Each function has a precisely defined logic that will be discussed in detail in the next paragraph.
We start by defining 4 different variables namely v1, v2, v3 & v4 along with r1, r2, r3 & r4 and v1_i, v2_i, v3_i & v4_i for taking input from the user. Then by using the print command we create the main user interface that is displayed in the output window. After that, we use the scroll function in our code to scroll up the printed text in the output window along with the clear screen function. We also use the MOV command to mov the data section into AX register along with initializing the data segment. The code is then added with the LEA instruction for addressing strings, as an interrupt to print strings. After that, we use the scan_num operation to take input from user in the program. Then, we use the compare instruction along with the jump instruction for comparing different values throughout the program. Finally, we make separate labels for each function to be performed by the calculator. Surely, we use the system defined arithmetic instruction for our function like, ADD, MUL, SUB etc. The result is printed by another label named “result” and lastly, the two end labels for printing wrong number and then restarting the program again and a label for exiting the program.

# Debugging / Test Run

![Picture1](https://user-images.githubusercontent.com/92357124/193456349-6655158e-e962-46b5-9ab1-9c4cbaf59793.png)
![Picture2](https://user-images.githubusercontent.com/92357124/193456365-7761b0db-4264-4834-ae22-aedf056ec17d.png)
![Picture3](https://user-images.githubusercontent.com/92357124/193456386-bda23e1a-39ba-4ae5-a969-9d18e9664560.png)
![Picture4](https://user-images.githubusercontent.com/92357124/193456475-db9da274-15fa-4fb2-b792-80a942f786ae.png)
![Picture5](https://user-images.githubusercontent.com/92357124/193456532-88bf6646-677e-4f5b-97a9-0760587f6082.png)
![Picture6](https://user-images.githubusercontent.com/92357124/193456537-26341844-f626-4815-9bad-d1d74627dea2.png)
![Picture7](https://user-images.githubusercontent.com/92357124/193456547-09302529-683b-48f3-bf8e-65c6bb09ecc7.png)
![Picture8](https://user-images.githubusercontent.com/92357124/193456552-9d5834d2-0952-4503-81aa-e9c7bdde8370.png)
![Picture9](https://user-images.githubusercontent.com/92357124/193456560-c96eba78-8c44-49e2-bf78-9f78354845ef.png)
![Picture10](https://user-images.githubusercontent.com/92357124/193456565-27da16ce-8d62-40f7-b1dc-b27aa4c84e03.png)
![Picture11](https://user-images.githubusercontent.com/92357124/193456562-5e4deda7-6350-4480-b4d9-8d0f30e9bc62.png)
![Picture12](https://user-images.githubusercontent.com/92357124/193456582-99297f26-77b2-40fe-8841-f05839d06657.png)
![Picture13](https://user-images.githubusercontent.com/92357124/193456585-ef326b35-b5dc-47d7-b25c-5e53f2ab40b2.png)
![Picture14](https://user-images.githubusercontent.com/92357124/193456597-8219d046-117b-4b8d-8197-91e56d056a04.png)
![Picture15](https://user-images.githubusercontent.com/92357124/193456601-409e70d7-2c5a-4389-a409-4f60454dcc5d.png)
![Picture16](https://user-images.githubusercontent.com/92357124/193456606-b284c4ad-985e-4f54-95b8-d4c276640b1a.png)

# Contributors
- Qalb E Ali
- Ahsan Ali
