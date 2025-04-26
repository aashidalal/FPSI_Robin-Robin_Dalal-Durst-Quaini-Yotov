FPSI_Robin-Robin(Dalal-Durst-Quaini-Yotov).pdf contains the pdf file of the research paper titled, "A Robin-Robin splitting method for the Stokes-Biot fluid-poroelastic
 structure interaction model".
fpsi-robin-robin-rev.tex is the tex file of the research paper titled, "A Robin-Robin splitting method for the Stokes-Biot fluid-poroelastic
 structure interaction model".
fpsi-robin-robin.bib is the bibtex file of the research paper titled, "A Robin-Robin splitting method for the Stokes-Biot fluid-poroelastic
 structure interaction model".
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
CODES, IMAGES, TXT FILES, AND ZIP FOLDERS FOR EXAMPLE 1: CONVERGENCE TEST
CODES:
code1-noniter.edp consist of FreeFem++ code for the non-iterative Robin-Robin algorithm- Algorithm 1 (3.15-3.21 on Pages 8-9 of the pdf file of the research paper).
code2iter.edp consist of FreeFem++ code for the iterative Robin-Robin algorithm- Algorithm 2 (6.1-6.6 on Pages 19-20 of the pdf file of the research paper).
code3mon.edp consist of FreeFem++ code for the monolithic scheme (6.12-6.17 on Page 22 of the pdf file of the research paper).
IMAGES:
domain_blank.png is the schematic representation of a 2D computational domain.
DomainA.png is the computational domain and mesh for convergence test.
TXT FILES:
output-convergence results.txt consists of errors (discretization in time) and convergence tables given by running the 3 codes (code1-noniter.edp, code2iter.edp, code3mon.edp) for gamma=1, h=1/32 fixed.
ZIP FOLDERS:
Convergence plots for gamma=0.001, 0.01,0.1,1,10,100 for the iterative Robin-Robin algorithm with 10 iterations.zip folder consists of matlab 
   files to plot images in Figure 5 on Page 28.
Convergence plots for gamma=0.001, 0.01,0.1,1,10,100 for the non-iterative Robin-Robin algorithm.zip folder consists of matlab 
   files to plot images in Figure 4 on Page 27.
Convergence plots for gamma=0.001,1,100 for the non-iterative, iterative Robin-Robin methods and the monolithic method.zip folder consists of matlab 
   files to plot images in Figure 3 on Page 27.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
CODES, IMAGES, AND ZIP FOLDERS FOR EXAMPLE 2: BLOOD FLOW TEST
CODES:
bloodflow-noniter-1.edp runs the FreeFem++ code for the non-iterative algorithm- Algorithm 1 to obtain the paraview 2D plots of Figures 7 and 8 on Pages 30-31 for 
   gamma= 1000.
bloodflow-monolithic-3.edp runs the FreeFem++ code for the monolithic scheme (6.12-6.17 on Page 22 of the pdf file of the research paper) to obtain the paraview 2D plots 
  of Figures 7 and 8 on Pages 30-31 for gamma= 1000.
Pfunctioncos.edp is the FreeFem++ code for inlet pressure defined in equation 7.2 on Page 29 of the research paper titled, 
  "A Robin-Robin splitting method for the Stokes-Biot fluid-poroelastic structure interaction model".
IMAGES:
DomainB.png is the computational domain for blood flow test.
DomainB-zoom.png is the zoomed-in view of the mesh at the fluid-structure interface for blood flow test.
pressure(N=70)1.png, pressure(N=140)1.png, pressure(N=210)1.png are png images of Fluid and Darcy pressure computed by the non-iterative Robin-Robin scheme 
  at times t=0.007, 0.014, 0.021s.
pressuremono(N=70)1.png, pressuremono(N=140)1.png, pressuremono(N=210)1.png are png images of Fluid and Darcy pressure computed by the monolithic scheme 
  at times t=0.007, 0.014, 0.021s.
velocity(N=70)1.png, velocity(N=140)1.png, velocity(N=210)1.png are png images of Fluid and Darcy pressure computed by the non-iterative Robin-Robin scheme 
  at times t=0.007, 0.014, 0.021s.
velocitymono(N=70)1.png, velocitymono(N=140)1.png, velocitymono(N=210)1.png are png images of Fluid and Darcy pressure computed by the monolithic scheme 
  at times t=0.007, 0.014, 0.021s.
ZIP FOLDERS:
Matlab Post-Processing for Figure 9 Example 2.zip folder contains all the FreeFem++ codes, .csv excel files, .m matlab files, .png images to obtain images in Figure 9 on Page 31.
Matlab Post-Processing for Figure 10 Example 2.zip folder contains all the FreeFem++ code, .csv excel files, .m matlab files, .png images to obtain images in Figure 10 on Page 32.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
