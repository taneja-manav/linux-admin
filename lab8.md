Write shell scripts to print system information. 
Write shell script to perform basic mathematical 
calculation. 
Use redirection operators to store the output of 
commands. 

implementation
--------------------------------
#!/bin/bash
echo $(lscpu)>info.txt
df -h
------------------
![image](https://github.com/user-attachments/assets/13dd9c01-fc36-4de0-b7c3-da10e5d7b5ee)
----------------------------------------------

implementation
-----------------------
#!/bin/bash
echo "simple calculator"
echo "enter first number1"
read num1
echo "enter second number"
read num2
echo "addition"
echo $((num1+num2))
echo "diffrence"
echo $((num1-num2))
echo "product"
echo $((num1*num2))
echo "division"
echo $((num1/num2))
---------------------------------------------
![WhatsApp Image 2025-03-19 at 12 41 37_8b4f016d](https://github.com/user-attachments/assets/77474960-e921-4f68-9da5-e275ebb2a5c6)
