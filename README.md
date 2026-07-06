# Multi-commodity-Energy-hub-Linear-Programming-of-a-Dutch-Greenhouse
A Python model, made for my Complex Systems Engineering & Management (CoSEM) Master Thesis at the TU Delft using PyPSA (Python for Power System Analysis), of a sustainable heat, electricity and CO2 network of a greenhouse that can replace the current CHPs (Combined Heat and Power). The goal is to evaluate the system on Self-Sufficiency, Grid Alignment and Economic performance. The latter was done using a simplified MGA. Which redispatches the system without changing the sizes of the equipment to show the possibilities within a economically optmised system.

The sustainable system is based on spectral-splitting PV from Voltiris. Which can be used within the greenhouse to generate electricity without taking away PAR light from the crops. Furthermore the electrical system consisted of a BESS and the grid import. The heat system consists of Geothermal heat (which uses electricity to pump up the heat), a thermal storage system and a heat pump. Furthermore, CO2 was produced using Direct Air Capture which needed electricity and heat as input.

Three models where made with similar structure:
1. Electrical system only; BESS, PV, grid import and electrical load. With an additional model doing a rolling horizon of 24h with 12h overlap. 
2. Electrical and heat system; BESS, PV, grid import, electrical load, geothermal heat, heat pump, thermal storage and heat load.
3. Complete system; BESS, PV, grid import, electrical load, geothermal heat, heat pump, thermal storage,  heat load, Direct Air capture and CO2 storage.

For Questions you can contact Jesse Labe on https://nl.linkedin.com/in/jesse-labe-0b8b021a3
