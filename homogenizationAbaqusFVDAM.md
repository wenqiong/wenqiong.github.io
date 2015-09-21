---
layout: default
title: Wenqiong Tu
---
## Homogenized Moduli Evaluation of Periodic Materials with Finite-Volume Micromechanics and Abaqus [pdf poster](/DS Simulia RUM Poster-Wenqiong Tu.pdf)

* FVDAM’s accuracy  and efficiency in computing homogenized properties and local stress fields are verified with Abaqus.  

* Python scripting capability in Abaqus makes it possible to automate the imposition of periodic boundary conditions via coupling equations


![homogenization mesh](/assets/homo-mesh.jpg)
*Basic building block of hexagonal unit cell with 40% volume fraction (Discretization is doubled for analysis)*


![homogenized relation](/assets/homo-relation.jpg)
*Homogenized relation*


![homogenization flow chart](/assets/homo-flowchart.jpg)
*Flow chart of computing homogenized properties in Abaqus*


![homogenized moduli](/assets/homo-moduli.jpg)
*Results: Homogenized Properties* <br>
Note: FVDAM uses generalized plane strain analysis to generate the entire set of properties while a 3D mesh is used in Abaqus - hence the difference in execution times. 


![homogenized moduli](/assets/homo-stress.jpg)
*Selected stress fields with imposition of only unit epsilon22=1*