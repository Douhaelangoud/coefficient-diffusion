# coefficient-diffusion
Diffusion Coefficient Calculator with Jupyter Widgets
Description
This project is a Jupyter Notebook-based application that calculates the diffusion coefficient 
D
A
B
D 
AB
​
  for a binary mixture (e.g., methanol-water) using a mathematical model. The application uses ipywidgets to create an interactive interface where users can input mole fractions (
x
A
x 
A
​
  and 
x
B
x 
B
​
 ) and compute the diffusion coefficient. It also compares the calculated value with a reference experimental value to determine the relative error.

Features
Interactive interface: Built with ipywidgets for easy input and output.

Real-time calculation: Computes the diffusion coefficient and error instantly.

Error handling: Ensures that 
x
A
+
x
B
=
1
x 
A
​
 +x 
B
​
 =1 before performing calculations.

Scientific output: Displays results in scientific notation for precision.

Technologies Used
Python: The core programming language.

Jupyter Notebook: For creating an interactive environment.

ipywidgets: For building the user interface.

NumPy: For mathematical computations.
