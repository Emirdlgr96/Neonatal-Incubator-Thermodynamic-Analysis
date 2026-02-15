# Neonatal-Incubator-Thermodynamic-Analysis
Thermodynamic modeling and PID control analysis of a neonatal incubator to optimize infant thermal balance.

# Project Overview
Premature infants face significant risks of hypothermia due to insufficient thermoregulation capabilities. This project analyzes the thermodynamic interactions within a neonatal incubator to optimize the infant's energy balance. By modeling the infant as a lumped thermal mass, we quantitatively investigate heat losses through conduction, convection, radiation, and evaporation.

# Methodology & Equations
1. Transient Energy Balance
The fundamental energy balance of the infant is described by;
$\frac{dU}{dt} = Q_{met} - (Q_{cond} + Q_{conv} + Q_{rad} + Q_{evap})$.

3. Metabolic Heat Production
Metabolic Heat ProductionFor premature infants, metabolic production is empirically modeled as a function of body weight (W):
Metabolic heat production is calculated using;
$Q_{met} = 0.0522 \cdot W^{0.75}$.

5. Heat Loss Mechanisms
The total heat dissipation is analyzed through three primary physical mechanisms:

* **Convection ($Q_{conv}$):** Governed by Newton's law of cooling, highlighting a strong dependence on airflow velocity ($V$) and the Reynolds number ($Re$).
* **Radiation ($Q_{rad}$):** Modeled by the Stefan-Boltzmann law; it constitutes a substantial portion of total heat loss due to the large exposed surface area of preterm infants.
* **Evaporation ($Q_{evap}$):** Driven by the vapor pressure gradient between the infant's skin and the surrounding air, where ambient humidity acts as the primary regulating factor.

# Key Findings & Results
1. The Critical Role of Humidity: Increasing relative humidity from 40% to 80% yields an approximately 30% reduction in total heat loss.

2. Double-Wall Efficiency: Geometric design analyses revealed that double-wall structures reduce radiative heat loss by 25% compared to single-wall systems.

3. Thermal Stability: Proposed a closed-loop PID control architecture to maintain thermal stability against external disturbances, such as the opening of access ports.

## Conclusion
Based on our thermodynamic analysis, an ideal neonatal incubator cannot rely solely on air temperature regulation. An optimized system must integrate the following three fundamental components: 

* **High Humidity Capacity:** Essential to minimize the vapor pressure gradient and prevent excessive evaporative heat losses. 
* **Double-Wall Geometry:** Crucial to maintain a higher inner wall temperature and mitigate radiative heat transfer. 
* **Intelligent Control Algorithms:** Advanced PID architectures are required to manage external disturbances and maintain thermal stability. 

---

## Authors & Acknowledgments
This study was conducted as part of the **BME3921 Biothermodynamics** course project at **Yıldız Technical University**. 

* **Team Members:**
  * Emir DÜLGER
  * Atakan PARLAK 
  * Ceren ALEMDAĞ  
  * Furkan BİROĞLU  
  * Sinan Ahmet YALÇINKAYA 
  * Emirhan ALTUNGÖK 
* **Supervisor:** Görke Gürel PEKÖZER 

