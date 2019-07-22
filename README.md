# acoustic_localization
Closed Form Solutions and Simulation code 

Closed form solutions are present in the equation.py script. In simulation.py paramters of corresponding hyperbolas are computed directly and values are fed into closed from solutions, which retreives soruce information just like it would do if hyperbola paratemters were found by TDOA analysis.


you can test your own coordinates by appenidng it to the "test_sources" array at line 77

note that due to symmetry of the problem test source components are always positive in the script 

In simulation.py we introduce hyperbola objects to make the code more intuitive and readable, equations.py can be used directly without using that objects. 
