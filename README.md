# Asynchronous Equation Solver:
This repository hosts an Asynchronous Equation Solver implemented in HTML, CSS, and JavaScript. The solver calculates the resultant force and angle by decomposing two forces acting on an object at an angle.

# Overview:
The repository consists of an HTML file (index.html) with accompanying CSS styles and JavaScript logic for the equation solver.

# Usage:
### How Equation Solver Works?
The equation solver performs the following steps asynchronously:

## Data Input:
Asynchronously inputs the values of forces F1 and F2, along with the angle θ in radians.
## Force Decomposition:

Asynchronously calculates the horizontal and vertical components of forces F1 and F2 using trigonometry.
## Resultant Horizontal and Vertical Components:

Calculates the resultant horizontal and vertical components (Rx, Ry) by summing the decomposed components of forces F1 and F2.
## Resultant Force Magnitude:

Computes the magnitude of the resultant force (R) using the Pythagorean theorem.
## Resultant Angle Calculation:

Determines the angle α using trigonometry based on the computed horizontal and vertical components of the resultant force.
## Return Results:

Returns the values of R (Resultant Force) and α (Resultant Angle) to the user.
# Steps to Use:
Open the index.html file in a web browser.
Enter the values of forces F1, F2, and the angle θ prompted by the browser pop-ups.
Click the "Calculate" button to initiate the calculation process.
The results of the computation will be displayed below.
# Structure:
## index.html:
Contains the user interface and functionality for input and calculation.
## styles.css:
Defines the styling for the HTML elements.
## JavaScript: 
Within the HTML file handles the asynchronous calculation and updating of the results dynamically on the page.
# Dependencies:
The code relies on jQuery (v3.6.4) for DOM manipulation and asynchronous calculation handling.
# Notes:
Ensure that modern web browsers supporting JavaScript and jQuery are used for proper functionality.
The calculation is performed synchronously, but inputs are taken asynchronously for a better user experience.
# Contribution:
Contributions via suggestions, issues, or pull requests are welcome!
