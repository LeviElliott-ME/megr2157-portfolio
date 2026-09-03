# A2 – Truss Stress Analysis

## Objective

For assignment we were given a task of designing and modeling a 3D truss that follows given requirements. 

- Design a lightweight planar truss using A500 steel (Some software does not have this material so use a different type of steel) and following geometric constraints.
- Create free body diagrams for joints and critical pins of the truss.
- Calculate the minimum cross-sectional area of truss members and pins with a safety factor. The pin must withstand the expected shear forces.
- Determine pin sizes based on shear forces with a safety factor.
- Estimate the total weight of the A500 steel truss and pins.
- Create a CAD model of the truss with the dimensions and connections.
- Compare CAD weight predictions of the material mass with hand calculations.
- Document the truss design process, calculations, and an analysis of your reasoning.

Our requirements are based off of this image.

<div align="center">
  <img width="350" height="300" alt="image" src="https://github.com/user-attachments/assets/45ee35bf-2ed4-453b-b577-758a4911d123" />
</div>

 A is a pin and B is a roller. There are two distance measurements. They are a = 0.4 meters and b = 0.3 meters. There are two forces (P) acting on the truss in the y direction. We can choose our own P value. The ranges we can choose from are 20kN-30kN. For my truss I choose P = 20kN. The largest internal force will be used to calculate the required cross-sectional area of the elements. In doing so we will use a safety factor of 3.5. The pins must have a shear strength of 170 ksi with a density of 0.278 lb/in^3. The pins must be designed with a single shear connection with a safety factor of 4. Compression members are assumed not to fail by buckling. The material that I will be using is A500 structural steel. Pin material is hardening tool steel.

A500 structural steel grade C is a good choice for this assignment. This is because it is usually used for trusses and supports. This is because it has a high tensile strength and yield strength. The tensile strength of A500 structural steel grade C is 425 MPa. The yield strength is 315 MPa. These values came be found by the website below.

https://www.octalsteel.com/resources/astm-a500-grade-c-pipe/

## My Truss Design/Analyze

<div align="center">
  <img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/d713607c-fbc6-4cc5-a91b-79f3c654fafc" />
</div>


I choose this truss design because it was the first design I thought of when l was looking at the image of the criteria. I choose this design because it does not have a lot of members. Less members provides a cheaper material cost, fewer failure points, and easier to calculate internal and external loads. It also only consists of five joints. So, my design will save time and money when manufactoring.

## External Forces

The first thing to do is to solve for all of the unknown external forces. These where Ax, Ay, and Ey. To do this I used the sum of the forces in y equals zero. This gave me the result Ax=0kN. Then I used the sum of the forces in x equals zero. This gave me the result Ay=6.67kN. Lastly, to find Ey I did a moment around E. This gave me the result Ey=-6.67kN

<div align="center">
  <img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/efdc1dec-1be6-4150-98d5-07124e2145ae" />
</div>


## Internal Forces

Then, I solved for my internal forces. To do this I used the external forces that I found. I also used method of joints for all of the five joints. I found that my largest force in tension was BC=16.02kN. I found that my largest compression force was DC=16.02kN

<div align="center">
  <img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/207fdc83-5220-470c-b877-4ac384ff2c43" />
</div>
<div align="center">
  <img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/58c17a9f-693a-4cb4-9005-9c9c92595423" />
</div>

## Cross-Sectional Area

The next step is to calculate our cross-sectional area. To do this we use our highest force member with for me is 16.02kN. We also have to use our safety factor of 3.5. Then, we also have to use the yield strength of our material which is 315MPa. I created an equation to find the cross-sectional area symbolically first. Then I plugged in my known numbers. This gave me my minimum cross-sectional are of 178mm^2. Then we have to find the weight of the truss. I did so by adding all of the lengths together. Then multiplying the total to the minimum cross-sectional area that we calculated. I found the mass in kg then I converted it into newtons.

<div align="center">
<img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/f4f9559d-371a-48d1-9ebc-ff69309b24dd" />
</div>

## Pin Calculations

The next step in designing our truss is to calculate the shear loads of the pins that will hold our truss members together.  





## Decide
_Which geometry did you select, and why? This is your first open design choice in the course — defend it._

## Communicate

