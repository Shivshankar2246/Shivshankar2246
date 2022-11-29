# **Wind Turbine Model**
Copyright 2009-2020 The MathWorks(TM), Inc.

[![View Wind Turbine Model on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/25752-wind-turbine-model)

Open project "Wind_Turbine.prj" to set the path and load key values.

Please note:

1. Wind_Turbine_Demo_Script.html will walk you through most parts of the wind turbine demo.  

2. Some configurations are invalid.  
   Turbine Inputs, Blade Loads, Main Controller, and Pitch Controller must be compatible

	Valid combinations:	
	Turbine Inputs	Main Controller	Blade Loads	Pitch Controller
	Commands	Direct Input	Torque		Inner Loop
	(all other)	Wind Input	(not Torque)	PI on AoA

3. The model Wind_Turbine_Flexible_Blades.slx is not built to be 
attached to Wind_Turbine.slx.  It is proof of concept only.

