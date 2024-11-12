# Support code for Proposition 12

The code is written in Python 3 and requires the numpy, scipy and pyomo libraries, and the json and ast Python modules.
The suggested runtime environment is Python 3.10 with numpy 1.26.4, scipy 1.14.1 and pyomo 6.8.0.
<br><br>
"generate_combinations.py" is the main script for generating the combinations of path-length sequences.
<br>
"config.py" is a configuration script containing values for the parameters "n" (i.e, the number of leaves) and "solver", which depends on the MILP solver installed on the runtime platform (e.g., "cplex" for IBM CPLEX and "xpress" for FICO Xpress, according to pyomo documentation: https://pyomo.readthedocs.io/en/stable/).

