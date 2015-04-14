---
layout: default
title: Wenqiong Tu
---
## Cohesive Zone-Based Damage Evolution in Periodic Materials Via Finite-Volume Homogenization

* **Two global systems of equations:** Primary system of equations and auxiliary system of equation. The primary system establishes the relations between continuous displacements and displacement discontinuities. The auxiliary system relates the interfacial tractions of damaged or cracked interfaces to the corresponding displacement discontinuities.

* **High efficiency:** Primary system of equations only needs to be solved once and auxiliary system of equations is solved iteratively at each loading step. The number of auxiliary equations is equal to the number of interfaces undergoing damage multiplied by the associated degrees of freedom.

* **A straightforward way to implement CZM:** Explicit traction-interfacial separation relations are available through the local stiffness matrix.

* **Publications:** One peer-reviewed article has been published in [Journal of Applied Mechanics](http://appliedmechanics.asmedigitalcollection.asme.org/article.aspx?articleid=1892761) [pdf file](/JAM-2014-Tu & Pindera.pdf) and two sequential papers are in the writing process.


![cohesive laws](/assets/cohesiveLaw.jpg)
*Coupled bilinear cohesive laws which control interfacial separation*


# Application: fiber/matrix debonding in SiC/Ti composites 
![Sic-Ti discretization and homogenized response](/assets/discretizationAndHomogenizedResponse.jpg)
*Unit cell discretization and homogenized response*

![stress evolution](/assets/sicTi_stressDistribution.jpg)
*Stress distribution at different loading steps with progressive interfacial damage*
