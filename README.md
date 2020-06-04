# WEIS_CCD
A place to share controls co-design tools for the WEIS project


I think we will want folks to install WISDEM (for running OpenFAST simulations, getting wind turbine cost functions and constraints) and the ROSCO_Toolbox and have a working version of openfast.


The main areas we'll develop will be:
- Modelling (linear state space and frequency domain, Level 1 models when available)
- Controllers (a library of ROSCO-like controllers and open loop optimal controllers)
- Cost Functions (what should we be optimizing and what are the constraints?)
- Optimizers (tools for running optimizations, given the above parameters)

We'll need to decide as a team: 
- Consistent modelling interfaces
- How state-space/linear models should look when used by the various controllers)
  - Consistent inputs and outputs of models w.r.t. controllers, cost functions and optimizers (we could use openmdao to be consistent with other WEIS teams)
- A roadmap for future development, who works on which parts of the repo, etc.
