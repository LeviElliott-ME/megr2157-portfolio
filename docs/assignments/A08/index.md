# A8 – Gears

## Objectives

-Design a gearbox that can be assembled and disassembled.

-Analyze and size input and output shafts for strength.

-Design journal bearings to support shafts.

-Create a gearbox housing with proper clearance and fastening.

-Use parametric CAD modeling to generate a final design.

-Document calculations, sketches, and lessons learned.

## Description

Design a gearbox which can be assembled and disassembled. The spur gears have a gear ratio of 24:9 and are listed in the resource section. The output gear torque and speed are to be 1.25 in-lbf and 1100 rpm relative. The input (pinion,power-transmission) and output (gear, short shaft) shaft diameters are .125 and .25 inches respectively and each have a length of 1 inch. Use the appropriate equations in the Machinery’s Handbook for empirical units. The critical features of the gearbox include the shafts, and the journal bearings.

Assumptions: 

-Assume appropriate strength of shafts, use Machinery’s Handbook.

-The gear train is ideal.

-The moment of the radial force from the gear train is small enough to be ignored.

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/c4d760a6-8c29-4cb4-a794-bc5a03dc3344" />
</div>

## Shaft Design

To design the input shaft and the output shaft I needed to find the equations From the machinery's handbook. We need to find the equations for the power going through the shafts, the torque applied on each shaft, and the speed of each shaft. With the given 24:9 ratio, I used the equations to find the speed and torque. Our input shaft we needed to use a maximum shear stress of 4000psi and for the output shaft we needed to use a max shear stress of 8500psi. With these equations I was able to solve for diameters that are related to the power and torque. The diameters I solved for were each sufficient so I could keep the original diameters. 

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/80c43372-341c-4d56-944e-e9cb32270c93" />
</div>

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/b5000f97-0944-4c40-8e6b-7cf3fdde2e38" />
</div>

## Journal bearing Design

For the journal bearing design we are provided options from the McMaster-Carr Catalog. Although, we have to calculate the thickness of the input bearing and the output bearing. We also have to calculate what material of bearings we need. To do so we have to solve for velocity, pressure, and the PV rating. While looking through the catalog I figured I would use a bearing length of a 1/4in. The bearings are designed as running/sliding fits. I used the RC5 table to determine the inner bearing diameter for both shafts. Then I solved for velocity, pressure, and PV rating and determined the material that I am going to use is the Graphite (dry). Then the next step was to solve for the thickness of the bearings. To solve for the thickness I used the pressure/axial stress formula. Using the radial force acting on the bearing and the cross-sectional area of the bearing diameter. I was able to find the thickness for each of the bearings.

**Input Bearing**

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/d7a1bf2b-f9b7-4ff1-9f29-bf393755f36c" />
</div>

**Output Bearing**

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/47ed52f6-3fd7-4450-8949-5921f17d0326" />
</div>

**Bearing Thickness**

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/23a9181f-cdc8-4eb3-8b80-7256e3b7c965" />
</div>

**McMaster-Carr bearings**

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/7a341b58-0e25-4911-8392-223f9a7932ab" />
</div>

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/5af6666d-cd92-4ce0-a617-327af99bf575" />
</div>

## CAD Design and Assembly

The McMaster-Carr Catalog provided use the pinion, gear, and the journal bearings. Using CAD we were tasked with designing the input and output shafts and housing for the assembly. Designing the shafts we use the given diameters of 0.125in and 0.250in. Then we use the length of 1in. Designing these did not take long at all. Since the shafts are press fit I added filets on the ends. Then I started designing the housing. I decided to use a snap fit design for the housing. This means that the housing can come apart into two pieces without needing bolts. I made the housing big enough for the gears to fit into. Then I extrude cut the holes in the sides for the bearings to fit into. I then started on the assembly. I mated the shafts, journal bearings, and the gears together. then the tricky part was mating the gears correctly so they function with one another. To do this I used the mechanical mate and chose the 24:9 gear ratio. 


**Gear Box Drawing**

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/5bac13a8-ad1f-4f7c-8001-b44cf3b87c2a" />
</div>

**Input Shaft**

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/f03f2c2c-df41-4b67-bf9c-b0da2c05d3f8" />
</div>

**Output Shaft**

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/72fd568b-267f-42dd-9503-097e8b15e04a" />
</div>

**Input Bearing**

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/1daecede-2951-4c63-9d9a-e5e9359e1463" />
</div>

**Output Bearing**

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/311c72a9-404c-4789-9786-0c52ea90dd0d" />
</div>

**Pinion**

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/5e6e59ca-1697-4b39-9827-93805f16cbcf" />
</div>

**Gear**

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/c4551791-9052-4026-b664-00a93c06d91d" />
</div>

**Gear, Shaft, and Bearing mates**

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/223d8aa9-435f-4dc0-a2b5-6e876adf257e" />
</div>

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/04188aca-cb03-4951-bff2-0311daf569bd" />
</div>

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/74d57804-4dcd-4860-9ead-acbacbdaef86" />
</div>

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/13c0dc99-230b-4368-bfc5-818c76098a35" />
</div>

<div align="center">
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/efe49eb8-fd7f-408f-a423-cfdcc10dd3e4" />
</div>






## Analyze


## Decide


## Communicate

