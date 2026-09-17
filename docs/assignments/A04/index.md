# A4 – Motor Mount

## Objective

For this assignment we are tasked with designing a motor mount. We are given the motor and its specifications. The mount must support the motor and be fixed to a wall. We get to choose our material from different material options I chose ABS. The motor specifications were found using the link below.

https://www.omc-stepperonline.com/brushed-24v-dc-gear-motor-3-6kg-cm-46rpm-w-99-5-1-planetary-gearbox-pa28-28245800-g100

<div align="center">
<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/3a1ded60-722f-4801-bf9e-69d7e9b4d387" />
</div>

<div align="center">
<img width="750" height="350" alt="image" src="https://github.com/user-attachments/assets/53003536-c931-455c-8f27-9786def78881" />
</div>

## Material

This is more information I found about my chosen ABS material. In my materials elastic modulus range I chose the value of 2,000MPa. Then for the Yield strength range I chose a value of 40MPa. 

<div align="center">
<img width="550" height="350" alt="image" src="https://github.com/user-attachments/assets/4eb76616-5425-44bf-bda0-3bca3b7c2027" />
</div>

## Feature 1

For my first feature I listed my knowns and unknowns. This helped me identify the values I have and the values I needed to find. The first feature was the feature that the motor fits onto. I created a free body diagram of feature one. For the four bolt holes I used the example diameter of d=3.4mm. I used equations from class and symbolically solved to find the equation needed. Then, I solved from the cross-sectional area. I did this by solving for my max normal stress. I used that values and my other known values to find "b" under stress. Once I found my stress I then solved for deflection. After I found both of my values I found that my value for stress was larger then my deflection value. This means that my stress value was my ultimate value b1=4.463mm. 

<div align="center">
<img width="550" height="350" alt="image" src="https://github.com/user-attachments/assets/9940d3c9-7368-4ba8-8a53-4db2a5e9cdf8" />
</div>

<div align="center">
<img width="550" height="350" alt="image" src="https://github.com/user-attachments/assets/7b245fc2-0de0-4941-9c8a-06aba4714805" />
</div>
  
## Feature 2

For the second feature of the motor mount I listed my knowns and unknowns. This feature will be attached to a wall. It also has 4 bolt holds. For these holes I spaced them 2mm from the side of the mount. I did this because I did not want the bolt heads to exceed over the side of the mount. I then created a free body diagram of the feature. This feature has a moment because the bottom of the feature was free to bending. I had to solve for cross-sectional area "b" due to stress and deflection. I found my equations symbolically to solve. These were my moment equation, stress equation, and deflection equation. I then found that my stress value was larger than my deflection value. This means that my stress value was my ultimate value for feature two b2=1.311mm 

<div align="center">
<img width="550" height="350" alt="image" src="https://github.com/user-attachments/assets/c5c7ce28-faf7-43c7-a9ef-7b525d15b4b9" />
</div>

## Isometric Drawing Sketch

Once I found all of my needed values I created a drawing sketch of my motor mount with values

<div align="center">
<img width="550" height="350" alt="image" src="https://github.com/user-attachments/assets/7a16937e-cef9-42e8-be2f-105b563326b4" />
</div>

## CAD Motor Mount Model

First I created my base model, which for me was feature number 2. I then entered in my dimensions.

<div align="center">
<img width="550" height="350" alt="Screenshot 2026-09-16 213030" src="https://github.com/user-attachments/assets/a074e106-4d84-428d-b116-082da8b8ffb0" />
</div>

My next set was to sketch the holes. I did this by sketching four circles then adding my dimensions. since I wanted my holes to be 2mm away from the edge of the feature I found my radius from my diameter of 3.4mm. Which is 1.7mm then I added 2mm to that this gave me a value of 3.7mm from the center of my circle to the edge of the feature. Since I started with feature two and wanted to build feature one from it I had to make the bottom of my feature 8.163mm from the center of the bottom holes. I found this value by taking my value stated before of 3.7mm and adding my b1 value of 4.463mm. I did this because that is how think my second feature needs to be and I still wanted my holes 2mm away from the edge. Lastly I extruded the feature to my calculated value of b2=1.311mm.

<div align="center">
<img width="550" height="350" alt="Screenshot 2026-09-16 213525" src="https://github.com/user-attachments/assets/f0b64b46-3044-44bf-bfb3-95d91b2bfd8a" />
</div>

Once I finished the sketch it gave me a part that looked like this.

<div align="center">
<img width="550" height="350" alt="Screenshot 2026-09-16 213735" src="https://github.com/user-attachments/assets/93ed339a-8e01-4b94-add2-def15f0261ef" />
</div>

Then from the bottom I extruded out 26.689mm. This is because my b2 value equals 1.311mm and I want my overall length to be 28mm. Then I extruded up by my b1 value of 4.463mm.

<div align="center">
<img width="550" height="350" alt="Screenshot 2026-09-16 213921" src="https://github.com/user-attachments/assets/f2b7e06f-ea42-41a7-a07c-59e8308d183d" />
</div>

Then I created my same holes for my new feature one that I previously made for feature two. Then I had to make the center indent and hole for my motor to sit in and the shaft to fit through. The diameter of the large circle was 18mm and I made it a depth of 2mm. Then I made the hole for the shaft to go through. The shaft hole needed to be 6mm.

<div align="center">
<img width="550" height="350" alt="Screenshot 2026-09-16 215017" src="https://github.com/user-attachments/assets/9d78825a-1fca-4dab-943b-e4a4b9cf072e" />
</div>

I decided to design two supports on either side of the motor mount to prevent bending. I created them using a right triangle with a height of 12mm. A base of 9mm and a hypotenuse value of 15mm. I then extruded them 1mm. 

<div align="center">
<img width="550" height="350" alt="Screenshot 2026-09-16 215744" src="https://github.com/user-attachments/assets/2e059a19-ce49-4ffb-9358-a7e3b11730be" />
</div>

This is my final CAD design for my motor mount.

<div align="center">
<img width="550" height="350" alt="Screenshot 2026-09-16 215957" src="https://github.com/user-attachments/assets/1c0d2cd1-2ab1-4f44-901a-f3ea927f1963" />
</div>

## 2157 Students

We were tasked to make a drawing of our motor mounts. I did so with the right view, front view, top view, and isometric view. I added in my dimensions also. 

<div align="center">
<img width="550" height="350" alt="Screenshot 2026-09-17 003951" src="https://github.com/user-attachments/assets/e6c0995b-8afd-4f48-b519-052f15e1440d" />
</div>

## CAD File

**Part**
https://1drv.ms/u/c/9dc8fdbc6b2a0dfb/IQC-6JaQjAybRIXY7hvJ4KuiAY8yL29YwCh9f6yIhMiubtM?e=fDQgq7

**Drawing**
https://1drv.ms/u/c/9dc8fdbc6b2a0dfb/IQA9MG37hEUEQYvl3q4evTYnAfzrclJ4HJu7lzff3jmQDYM?e=veT8or

## Lesson Learned

During this assignment I learned that I need to study my formulas. This is because it had taken me a while to come up with the formulas to use. I also learned that I was rusty navigating through solid works drawings. This caused it to take longer than I expected.

## Completion Time

This assignment has taken me around 8 hours to complete.

