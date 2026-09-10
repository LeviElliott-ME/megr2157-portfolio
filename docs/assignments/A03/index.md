# A3 – Parametric and FEA

## Objective

For this weeks assignment we are tasked with designing an aluminum metal bar parametrically. This task comes with some criteria. The bar must be made from aluminum. It must have a certain Young's modulus between (8.5-11.5) * 10^6 psi. The bar must have a circular cross section. Also, the bar must be fixed at one end. It must also have an applied direct load between 300lb<F<500lb and the max axial deflection of the bar is 0.009 inches.

Example Image

<div align="center">
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/86c404a7-d8b8-4cfd-bf7c-b4f44265b845" />
</div>

## Design Process

<div align="center">
<img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/ebdc1261-ed36-4529-a011-891bc3f47bdd" />
</div>

With the given values and my choice of a 1in diameter for the aluminum bar I found the length that is needed. It must be a length of 141.372in to withstand a max axial deflection of 0.009in and a tensile load of 500lb. I calculated the length by finding the cross-sectional area of the bar. Then, I pugged in my values into the direct elongation equation to find my overall length.

## CAD Design

<div align="center">
<img width="750" height="550" alt="image" src="https://github.com/user-attachments/assets/55807f86-9ea6-4863-a5ac-11a9aa32649a" />
</div>

First I opened up a new part in solid sorks. Then the next step I did was to edit the equations tab on the left. This is where I entered in all of my values. For area and length I entered the formulas. Doing this caused solid works to do the calculations to find the length and area with my given values. Also, this helped me to check my work.

<div align="center">
<img width="750" height="550" alt="image" src="https://github.com/user-attachments/assets/5a2dbbb3-c534-412f-b73e-1baedb091f86" />
</div>

Then, the next step I did was to create a circle from the origin. To do so I created a new sketch on the front plane. From there I selected a circle from the top tool bar and clicked on the origin to create the circle from the origin. The next step was to assign my diameter. To do this I selected smart dimensions. Then I pressed the equals sign to pull the diameter from my equations table.

<div align="center">
<img width="750" height="550" alt="image" src="https://github.com/user-attachments/assets/469695de-91b6-4cf4-9241-33cca61a32be" />
</div>

Lastly, making the actual rod from the circle we have to extrude. I did this by selecting extrude from the tool bar at the top of solid works. Then with that selected I had to add the length I needed the extrusion to be. To do so at the left side of the screen. In the dimension blank box I entered "Length" this pulls the calculated length value from the equations table. 

<div align="center">
<img width="750" height="550" alt="image" src="https://github.com/user-attachments/assets/4d25fa87-1251-4afe-b3d7-18733f57be32" />
</div>

For the material I made a custom aluminum material property that has a elastic modulus of 10*10^6.

## FEA Analysis

Then, under the simulation tap I created a new study. This allows us to run a simulation on our aluminum bar. I added a fixed end to one side of my bar using the fixture tool. I then applied a force of 500lbf On the other side of the bar using the force tool. When adding the force you have to make sure that the force is in the correct direction. If not there is a "reverse direction" button. 
 
<div align="center">
<img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/7f1f6de1-b6c9-4062-9ea9-99e89dcb0d65" />
</div>

<div align="center">
<img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/ba577c44-9bef-4930-85a2-d70d2c20a7bc" />
</div>

<div align="center">
<img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/9b029ef8-61bc-4683-873b-ae58f7e30137" />
</div>

After I applied the fixed end and the force end of the bar I meshed and ran my bar simulation. This gives us a von Mises Stress map and a deflection map. 

**Von Mises Stress Map** 

<div align="center">
<img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/b53a85ca-4917-47bb-af08-eb2b41db3f2c" />
</div>

**Deflection Map**

<div align="center">
<img width="850" height="450" alt="image" src="https://github.com/user-attachments/assets/f4fb9466-a3b8-46b3-bfe4-3b013b1aab46" />
</div>

## My Calculations Compared To FEA



## Decide


## Communicate

