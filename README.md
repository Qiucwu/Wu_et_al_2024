# Scripts for figures from Wu et al. 2024
### Content Summary
The code database contains jupyter notebooks used to make figures for the publication. Each notebook is commented and annotated.

This publication includes modeling of pharmacokinetics and pharmacodynamics of murine interleukin 17A (mIL-17A) and Fc fusion of mIL-17A (Fc-mIL-17A).
Parameter fitting was performed using Scipy.optimize to identify parameters for:
1. A three-compartment pharmacokinetics model 
2. Emax pharmacodynamics model with a hill-coefficient = 1

The fitted PK and PD models were then combined create a PK/PD model to predict dosing regimens for mIL-17A and Fc-mIL-17A. 

### Publication Citation:
Wu, QC., Lee, JM., Swaminathan, A., Winward, A., Hwang, Y., Socolovsky, M., Way, JC., Klein, AM. Design and characterization of Fc-Fused Interleukin-17A for increased in vivo half-life. (2024)
