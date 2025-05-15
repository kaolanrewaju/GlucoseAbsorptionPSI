# GlucoseAbsorptionPSI
Material balance for glucose entering the PSI is modeled as a series of continuous stirred tank reactors (CSTRs) for each segment.
No spatial dependence is considered; focus is on temporal variation of glucose concentration along the luminal channel.
The material balance is represented by a series of ordinary differential equations (ODEs), with each ODE corresponding to a segment.
Number of segments modeled: 258.
ODE models are implemented in a MATLAB livescript developed by a graduate student under supervision.
Parameters used in the ODE model, based on literature data:
Total length of PSI: 275 cm
Length of each segment (dz): 0.6 cm
Gastric emptying rate (flow rate): 1.5 cm³/s
Small intestine radius (r): 0.9 cm
Absorption rate constant: 0.002/s
Simulation duration: 180 minutes
Initial glucose concentration exiting the gastric unit: 50 g/m³
Estimated parameters from literature:
Number of segments: 258
Segment volume: 1.527 cm³
