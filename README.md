
Assumptions: 
• The number can’t start with zero. 
• The number can't have 2 or more points “.”. 
• If there any error in the server or the calculation it shows “E” on the display screen. 
• Basic operations (add, subtract, multiply, divide) 
• Special functions (percentage, fraction, square, square root) 
• We can’t do more than one operation (ex: add two number and get the answer then 
mutiply the result with another number) 



https://github.com/user-attachments/assets/9e281ab0-8c8c-48dd-b956-3e6f0a2dbb58

Details: 
• To start a calculation, I type the first number, and the calculate function saves it 
as num1. It also saves the operation I chose (like add or subtract) and then pauses, 
waiting for me to press “equals.” When I press “equals,” the function reads the 
second number I entered and performs the saved operation. 
• When I’m ready to calculate, the function uses Axios to connect to the backend. It 
sends both numbers and the chosen operation. The backend uses these to figure 
out the answer and sends it back. Then, the result shows up on the display and is 
also saved as num1, so I can use it in the next calculation if I want. 
• For special operations, like finding a percentage, fraction, square, or square root, I 
don’t need to press “equals.” Just selecting one of these operations makes the 
calculator show the answer right away. This setup lets me quickly do both simple 
and advanced calculations.

