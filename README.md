# IST-Sem-3-Project-Calculator-In-Assembly-Language
In our 3rd semester we created a calculator using assembly language for our course computer organization &amp; assembly language. The calculator features basic mathematical operations.

# Theory:
We have designed the calculator in assembly language and used the following 13 functions:
1) Addition of two numbers          
2) Subtraction of two numbers          
3) Division of two numbers            
4) Multiplication of two numbers                    
5) Factorial a Number            
6) Computing power of any number       
Following formulas have been used:
7) a+b/2                         
8) (a + b)^2    
9) (a + b)^3 
10) (a - b)^3 
11) a^1 + b^2 + c^3 + d^4        
12) (a^3 + b^3) 
13) (a^3 - b^3)

# Implementation:

In the output window, the calculator interface defined by us is displayed to the user showing the list of 13 mathematical functions along with a few algebraic formulas with each function having its own serial number allotted to it. The user is then asked to input the serial number mention against the desired function the user wants to perform. After confirming the desired selection, the user is then again asked to input the values of variable that will be used to compute the selected mathematical function or formula. Each function has a precisely defined logic that will be discussed in detail in the next paragraph.
We start by defining 4 different variables namely v1, v2, v3 & v4 along with r1, r2, r3 & r4 and v1_i, v2_i, v3_i & v4_i for taking input from the user. Then by using the print command we create the main user interface that is displayed in the output window. After that, we use the scroll function in our code to scroll up the printed text in the output window along with the clear screen function. We also use the MOV command to mov the data section into AX register along with initializing the data segment. The code is then added with the LEA instruction for addressing strings, as an interrupt to print strings. After that, we use the scan_num operation to take input from user in the program. Then, we use the compare instruction along with the jump instruction for comparing different values throughout the program. Finally, we make separate labels for each function to be performed by the calculator. Surely, we use the system defined arithmetic instruction for our function like, ADD, MUL, SUB etc. The result is printed by another label named “result” and lastly, the two end labels for printing wrong number and then restarting the program again and a label for exiting the program.
