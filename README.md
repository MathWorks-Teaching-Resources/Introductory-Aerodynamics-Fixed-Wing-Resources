# Aerodynamics

This project contains several resources for instructors of an introductory 
aerodynamics course, with application to design of fixed-wing aircraft.  
Starting with a simple trajectory analysis of a body including the 
aerodynamic forces of drag and lift, students can understand how these
forces are calculated, and how they are used in practical applications, 
using the StepByStepTrajectory script.  

After the initial introduction, students can use the 
CompleteFlightTrajectory script to include the forces calculation in a 
helper function which can be used with ODE solvers for higher accuracy.
  
Next, potential flow theory is used to derive the basic concepts of 
circulation, streamlines, and boundary conditions for lifting bodies.  
Basic 2D potential flows can be calculated and visualized in both 
Cartesian and polar coordinates using the PotentialFlows script.  In this
script students can compute and visualize the flow over a 2D lifting
cylinder.  Students also learn valuable techniques for deriving
equations using symbolic math, including derivatives and vector operations.

Finally, potential flow theory can be used to derive the Kutta-
Joukowski theorem which relates the overall circulation in the flow field
to the lift on the body.  Symbolic math is used to demonstrate the
role of each term in the integral equation for conservation of vertical
momentum, in generating circulation and therefore lift, for the case
of the 2D lifting cylinder.

## Step by Step Trajectory
Open the Live Scipt [StepByStepTrajectory.mlx](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Introductory-Aerodynamics-Fixed-Wing-Resources&file=StepByStepTrajectory.mlx)

## Complete Flight Trajectory
Open the Live Script [CompleteFlightTrajectory.mlx](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Introductory-Aerodynamics-Fixed-Wing-Resources&file=CompleteFlightTrajectory.mlx)

## Potential Flows
Open the Live Script [PotentialFlows.mlx](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Introductory-Aerodynamics-Fixed-Wing-Resources&file=PotentialFlows.mlx)

## Kutta-Joukowski Theorem
Open the Live Script [KuttaJoukowskiTheorem.mlx](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Introductory-Aerodynamics-Fixed-Wing-Resources&file=KuttaJoukowskiTheorem.mlx)


# References

Though these examples were authored by me, we utilized the text book
in the class, and it includes the development of the potential flow
theory and Kutta-Joukowski theorem.  Note that it does not cover 
trajectory analysis, which is my own addition for teaching practical
aerodynamics.

https://www.amazon.com/Introduction-Flight-John-Anderson-Jr/dp/0078027675/ref=sr_1_4


