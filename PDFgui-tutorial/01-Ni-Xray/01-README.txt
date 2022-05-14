Nickel refinement information:

Space group:		Fm-3m
lattice a:		3.524 Angstroms
fractional coordinate:	0.0	0.0	0.0
Uiso:			0.005
Qmax:			Qmax Inv. Angstroms (different data with different Qmax, PDFgui will read that info if in metadata)
Qdamp:		initially set to 0.045
Qbroad:		initially set to 0.01 

Data: Ni 300K X-ray data collected at X7B at NSLS at BNL (Qmax=22 A**-1), 11IDC at APS at ANL (Qmax=27 A**-1), 
and at XPD at NSLS II at BNL (Qmax=25 A**-1) using Perkin Elmer image plate detector. Why is Qmax different?

GOAL: Familiarization with PDFgui. Set up and refine X-ray 300K Ni data. Learn what various parameters do, and what is their sensitivity. 
Explore how the same sample is seen at different instruments (data variability). Pick one data set of your choice. 

TASKS:
0) Pick one data set of your choice (say ni-q22r080t300-X7B-NSLS.gr).
1) Set up and refine 300K dataset without refining correlated motion parameters, refinement range 1.5-10 Angstroms
2) Observe the fit result
3) Repeat the refinement with correlated motion parameters, first delta1 only, then delta2 only, then both
4) Observe the fit result, consult results pane
5) Use one delta parameter (say delta1). Expand the fitting range to 20 Angstroms and refine. What do you see?
6) Set initial Qdamp to 0.05 and refine it. Did fit improve?
7) Expand fitting range to 50 Angstroms and repeat. How well it fits?
8) Add Qbroad to game by setting it to 0.01 initially and refine it as well? Did fit improve? 
What happened to refined parameters as compared to previous cases.
9) Repeat 1)-8) for the remaining two data sets. Compare the results for final refinements for 3 datasets. How different are they? Why?

***Various exercises worked out in 01-nickel-01.ddp and 01-nickel-02.ddp project files