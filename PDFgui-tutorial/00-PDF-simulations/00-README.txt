Nickel simulation information:

Space group:		Fm-3m
lattice a:		3.524 Angstroms
fractional coordinate:	0.0	0.0	0.0
Uiso:			0.005

GOAL: Familiarization with PDFgui. Set up and simulation of X-ray and neutron 300K Ni PDF. Exploration of various effects in PDF. 

TASKS:
1) Set up 300K Ni structure
2) Expand unit cell 
3) Chose radiation type: X-ray and neutron
4) Calculate X-ray and neutron PDFs from 0.01 to 10 Angstroms. Plot the result by using plotting utility.
5) Compare them (set offset to 0 in plotting utility) and observe the difference. Are you surprised?
6) Copy your original neutron calculation and set Scale to 0.2, compare with original
7) Copy your original neutron calculation and set Qmax to 15 Inverse Angstroms, compare with original
8) Copy your original neutron calculation and recalculate from 0.01 to 100 Angstroms
9) Copy your 100 Angstrom neutron calculation 8) and recalculate with Qdamp=0.05, compare with calculation in 8)
10) Copy your 100 Angstrom neutron calculation 8) and recalculate with spdiameter=20 ANgstrom, compare with calculation in 8)
11) Compare 9) and 10) and notice the similarity of effects
12) Copy your original neutron calculation, set stepcut to 5.25 Angstroms and recalculate. Compare to original.
13) Pick one of the refinements. Select phase. In phases dropdown window select calculate bondlengths and display first three   
by making appropriate selection. This is your tool for bondlength calculations. Similarly you can calculate bond angles.
***Various exercises worked out in 00-nickel.ddp project file

EXTRA TASKS I:
GOAL: Playing with multielement system BaTiO3. Probe choice. Things to keep in mind.

14) Do it yourself: try the same steps for some oxide structure, e.g. BaTiO3 and compare them. 
15) Use CIF file to load the structure
16) Determine if you need to expand the cell or not 
17) Set Uiso of all atoms to a very very small value of 0.0005 Angstroms**2
18) Simulate X-ray and neutron PDFs from 0.01 to 10 Angstrom, and compare them. Make some observations.
19) What can you say about the suitability of the probe used?
20) Set Uiso of all atoms to a value of 0.005 Angstroms**2 (still small but 10x larger than before). 
Repeat 14)-19), compare with Uiso=0.0005 Angstroms**2 case: the thermal broadening effects on the PDF resolution.
21) Copy your neutron calculation from 18) and change Included pairs from all-all to Ti-O. Compare with original.
This is how you can obtain so called partial PDFs.
***Various exercises worked out in 00-BaTiO3.ddp project file

EXTRA TASKS II:
GOAL: Chemical ordering and PDF. Sensitivity to scattering contrast.
22) Repeat neutron simulation for nickel
23) Copy fit 22) and set up new simulation with one Ni replaced by Au (25% substitution). 
24) Same as 23) but this time duplicate all Ni atoms, and set 4 out of 8 atoms to be Au. Adjust occupancies of 
Ni to 0.75 and Au to 0.25. This way every site is 75% Ni and 25% Au. All sites are identical now. 
25) Compare simulated PDFs in 22), 23), and 24). What do you see? What does it mean?
***Worked out in 00-nickel-02.ddp project file


