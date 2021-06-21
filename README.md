# trajopt-biped2D-ICB2021
Trajectory optimization code for minimum-distance gait termination in planar 9DOF biped, used in ICB paper 'Tails, Flails and Sails: How appendages improve terrestrial maneuverability by improving stability'

## Requirements
Python 3.7.3 (default, Apr 24 2019, 15:29:51) [MSC v.1915 64 bit (AMD64)]
Pyomo 5.6.6 with access to IPOPT and HSL ma97 solver 
Sympy 1.4

## Contents
biped_arms_loop.ipynb - Jupyter notebook that generates symbolic equations of motion, constructs Pyomo model and runs batch of seeds
new_sprint - pickle file containing sprint stride trajectory for sampling initial position and velocity
