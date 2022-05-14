Nickel refinement information:
==============================
Space group:		Fm-3m
lattice a:		3.52 Angstroms
fractional coordinate:	0.0	0.0	0.0
Uiso:			0.005
Qmax:			27.0 Inv. Angstroms
Qdamp:		initially set to 0.045
Qbroad:		initially set to 0.01 

Silicon refinement information:
===============================
Space group:		F-43m
lattice a:		5.43 Angstroms
fractional coordinates:	0.0	0.0	0.0
				0.25	0.25	0.25
Uiso:			0.008
Qmax:			27.0 Inv. Angstroms
Qdamp:		initially set to 0.045
Qbroad:		initially set to 0.01

Data: 300K X-ray data for Ni, Si, and mixture of Ni and Si, collected at 11-ID-C beamline of APS using Perkin Elmer image plate detector

GOAL: demonstration of a 2-phase refinement. Extraction of phase content information.

TASKS:
1) Refine Ni 300K PDF
2) Refine Si 300K PDF
3) Set up a 2-phase refinement to fit Si-Ni mixture 300K data
	What is proper phase fraction and scale factor parameter setup?
4) Determine the phase content
5) Think of a situation where such a refinement could be handy
6) Note that you have also original intensity files ni.iq, si.iq, and si90ni10.iq files (ascii) which you can plot 
and inspect the reflections of the two ingredient phases. Think about possible issues in PDF analysis in a situation 
where you admixed a calibrant powder to be used for e.g. temperature calibration in temperature dependent measurement.

***Exercises worked out in 04-si.ddp and 04-sini-mixture.ddp project files