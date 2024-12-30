Name:SHRAWYA.A.K
Company:CODTECH IT SOLUTIONS
ID:CT08FOX
Domain:C++ programming
Duration:december 20th,2024 to january 20th,2025
Mentor:Neela Santhosh Kumar

overview of project:
The program will convert temperatures between three major scales: Celsius, Fahrenheit, and Kelvin. It will enable the user to input a temperature in one scale, select the target scale for conversion, and display the result.
Allow the user to specify the scale of the input temperature (Celsius, Fahrenheit, or Kelvin).
Let the user select the desired scale for the output.
Conversion Logic:

Implement formulas for converting between the three temperature scales:
Celsius to Fahrenheit: 
𝐹
=
𝐶
×
9
5
+
32
F=C× 
5
9
​
 +32
Celsius to Kelvin: 
𝐾
=
𝐶
+
273.15
K=C+273.15
Fahrenheit to Celsius: 
𝐶
=
(
𝐹
−
32
)
×
5
9
C=(F−32)× 
9
5
​
 
Fahrenheit to Kelvin: 
𝐾
=
(
𝐹
−
32
)
×
5
9
+
273.15
K=(F−32)× 
9
5
​
 +273.15
Kelvin to Celsius: 
𝐶
=
𝐾
−
273.15
C=K−273.15
Kelvin to Fahrenheit: 
𝐹
=
(
𝐾
−
273.15
)
×
9
5
+
32
F=(K−273.15)× 
5
9
​
 +32
[30/12, 7:35 pm] Kavya: Interactive Menu:

Provide a menu for the user to select input and output scales.
Allow the user to perform multiple conversions or exit the program.
Validation:

Validate user input to ensure it is numeric and within reasonable bounds (e.g., Kelvin should not be negative).
Output:

Display the converted temperature in the desired scale with appropriate units.
[30/12, 7:35 pm] Kavya: Planned Steps:
Define the Conversion Functions:

Create separate functions for each conversion formula.
Design the User Interface:

Use a simple text-based menu for user interaction.
Continuously prompt the user until they decide to exit.
Handle Edge Cases:

Ensure robust handling of invalid inputs (e.g., non-numeric values).
Account for scientific accuracy in edge cases like absolute zero.
Testing:

Test with a variety of inputs to ensure the program is accurate and user-friendly
[30/12, 7:35 pm] Kavya: Possible Enhancements:
Allow batch processing of multiple conversions.
Add graphical user interface (GUI) using libraries like Tkinter or PyQt.
Extend functionality to include other temperature scales (e.g., Rankine).
Provide a web-based version using Flask or Django.
Would you like to proceed with implementation or need additional details for any of these steps?
