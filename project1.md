## Project 1: Development of Cohesive Zone Model (CZM)-Based Finite-Volume Homogenization technique towards the modeling of damage evolution in periodic materials

* **Two global systems of equations:** Primary system of equations and auxiliary system of equation. The primary system establishes the relations between continuous displacements and displacement discontinuities. The auxiliary system relates the interfacial tractions of damaged or cracked interfaces to the corresponding displacement discontinuities.

* **High efficiency:** Primary system of equations only needs to be solved once and auxiliary system of equations is solved iteratively at each loading step. The number of auxiliary equations is equal to the number of interfaces undergoing damage multiplied by the associated degrees of freedom.

* **A straightforward way to implement CZM:** Explicit traction-interfacial separation relations are available through the local stiffness matrix.

* **Publications:** One peer-reviewed article has been published and two sequential papers are in the writing process. (need to add paper link)


![cohesive laws](/assets/cohesiveLaw.jpg)
*Coupled bilinear cohesive law*


# Application 1: fiber/matrix debonding in SiC/Ti composites 
![Sic-Ti discretization and homogenized response](/assets/discretizationAndHomogenizedResponse.jpg)
*Unit cell discretization and homogenized response*

![stress evolution](/assets/sicTi_stressDistribution.jpg)
*Stress distribution at different loading steps with progressive interfacial damage*