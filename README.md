BIT 2118 Scientific Computing - Group Work

This is our group submission for Tasks 2 to 20. For every task we did the following:

Wrote and ran the original program
Changed one input or parameter and ran it again (Instruction C)
Made a new program for a different real-world case (Instruction E)
Saved the outputs and graphs
Wrote a short explanation of what happened
What is in each folder
Folder / file	What is inside
code/	The 19 original programs (Task 2 to Task 20)
changed_parameter/	Same programs, but with one input or parameter changed
modified_case/	New programs for a different real-world case
outputs/	Text output of each program and all the graphs (PNG)
docs/	One markdown file per task: inputs, what the program does, the change, what the results mean, and the new case
PRESENTATION_SUMMARY.txt	Short summary we will use for the presentation
Tasks and the real-world case we used
Task	Topic	Our modified case
2	NumPy arrays	Water tank level monitoring (IoT)
3	Math functions and vectorization	Currency conversion plus VAT on 2 million transactions
4	Floating-point errors	Adding one million small bank deposits
5	Matrix algebra	Drone waypoints moved using homogeneous coordinates
6	Systems of linear equations	Traffic flow through three roads
7	Gaussian elimination and LU	Circuit mesh currents with different voltage settings
8	Iterative methods	Steady-state heat along a rod with 7 points
9	Eigenvalues and eigenvectors	PageRank of a five-page website
10	Bisection and fixed-point	Break-even of a product with congestion cost
11	Newton-Raphson and secant	Finding the interest rate of a loan
12	Polynomial and nonlinear equations	Drone vs a no-fly zone, and projectile landing time
13	Interpolation	Filling in missing sensor readings
14	Curve fitting	Mobile app user growth (exponential vs linear)
15	Numerical differentiation	Acceleration from velocity data, and a step-size study
16	Numerical integration	Total river water volume from flow readings
17	ODEs with Euler method	Logistic population growth with different step sizes
18	ODEs with SciPy	SIR epidemic model
19	Optimization	Production planning to maximize profit
20	Random numbers and Monte Carlo	Project completion risk, and estimating pi
How to run
bash
pip install -r requirements.txt
cd code
python Task_02_numpy_arrays.py

Run each program from inside its own folder (code, changed_parameter or modified_case). The programs that draw graphs save a PNG in outputs/ and then open the plot window. Close the window to let the program finish.

You need Python 3.10 or newer and NumPy 2.0 or newer, because np.trapezoid only works from NumPy 2.0.

Notes
We discussed the work as a group, but the GitHub repository is individual, so each of us uploaded the folder to our own repo.
The repo link and documentation are submitted on VLMS.
