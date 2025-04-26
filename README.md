A Robin-Robin splitting method for the Stokes-Biot fluid-poroelastic structure interaction model, authored by: Aashi Dalal, Rebecca Durst, Annalisa Quaini, Ivan Yotov.

Abstract:  We develop and analyze a splitting method for fluid-poroelastic structure interaction. The fluid
 is described using the Stokes equations and the poroelastic structure is described using the Biot
 equations. The transmission conditions on the interface are mass conservation, balance of stresses,
 and the Beavers-Joseph-Saffman condition. The splitting method involves single and decoupled
 Stokes and Biot solves at each time step. The subdomain problems use Robin boundary conditions
 on the interface, which are obtained from the transmission conditions. The Robin data is represented
 by an auxiliary interface variable. We prove that the method is unconditionally stable and establish
 that the time discretization error is O(√T∆t), where T is the final time and ∆t is the time step. We
 further study the iterative version of the algorithm, which involves an iteration between the Stokes
 and Biot sub-problems at each time step. We prove that the iteration converges to a monolithic
 scheme with a Robin Lagrange multiplier used to impose the continuity of the velocity. Numerical
 experiments are presented to illustrate the theoretical results.

 Keywords: Stokes-Biot; fluid-poroelastic structure interaction; domain decomposition; Robin interface
 condition.
