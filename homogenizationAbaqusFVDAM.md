---
layout: default
title: Wenqiong Tu
---
## Homogenized Moduli Evaluation of Periodic Materials with Finite-Volume Micromechanics and Abaqus

* FVDAM’s accuracy  and efficiency in computing homogenized properties and local stress fields are verified with Abaqus.  

* Python scripting capability in Abaqus makes it possible to automate the imposition of periodic boundary conditions via coupling equations




![homogenization](/assets/homo-mesh.jpg)
*Basic building block of hexagonal unit cell with 40% volume fraction (Discretization is doubled for analysis)*





Flow chart of computing homogenized properties in Abaqus


Results: Homogenized Properties
FVDAM: Windows 7 64bit OS with Intel(R) Core(TM) i7-2760QM CPU @2.40GHz, 8GM RAM
Abaqus: Windows 7 64bit OS with Intel(R) Core(TM) i7-2820QM CPU@2.3GHz, 16GB RAM
Note: FVDAM uses generalized plane strain analysis to generate the entire set of properties while a 3D mesh is used in Abaqus - hence the difference in execution times. 


Selected stress fields with imposition of only unit --