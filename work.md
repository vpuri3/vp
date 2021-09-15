
+++
title = "Work"
hascode = true
date = Date(2021, 9, 15)
rss = "Work summary"
+++
@def tags = ["syntax", "code"]

# Work summary
This page is an extended curriculum viatte with unnecessary commentary. Check out my single page [CV](https://github.com/vpuri3/vpCV/raw/master/vpCV.pdf) if you're feeling lazy.

\toc

## BS @ University of Illinois Urbana-Champaign
I attended the University of Illinois Urbana-Champaign, where my interests in mechanics and computation pushed me to get bachelor's degrees in *Mathematics*, and *Engineering Mechanics*. While at university, I wrote spectral element codes to solve for fluid-flows in interesting geometries, and interned at the National Center for Supercomputing Applications on numerical partial differential equations, and then at Argonne National Laboratory on wall-bounded turbulent flows. I also have substantial on-campus engagement through Society for Engineering Mechanics, a student organization that I led in 2018.

**Society for Engineering Mechanics**: We engineerined mechanics.

**TAM 210 Course Assistant**
At UIUC, I discovered an interest in teaching when I was selected in freshman year to be a course assistant for *Statics*, a mechanics course where students learn to model mechanical interactions as forces and moments. The instructors for *Statics* invited me to attend the *Strategic Instructional Innovations Program* meetings to assist with curriculum design for mechanics courses serving $2500$ students annually. I created engineering-design oriented activities for students and coordinated with the Society for Engineering Mechanics, a student organization that I led in my senior year, to manufacture instructional demonstrations for introductory courses in *Statics*, *Dynamics*, and *Solid Mechanics*.

## National Center for Supercomputing Applications, 2017-18

My work at NCSA on initial data generation for gravitational wave simulations resulted in a talk that I delivered at the {American Physical Society April Meeting 2018}. Under Dr. Roland Haas of the Gravity Group, I solved nonlinear elliptic {initial data} equations for gravitational wave simulations in the cosmological framework {Einstein Toolkit}. I implemented the novel Scheduled Relaxation Jacobi technique which relies on precomputing a set of relaxation factors by nonlinear optimization for Laplacian-dominated PDEs. The relaxation solve was embedded within a Newton-Raphson loop to alleviate the stiffness due to nonlinearity, reducing the time-to-solution by several orders of magnitude.

## Argonne Natinoal Laboratory, 2018
I studied turbulence near wavy boundaries at Argonne as part of a larger {United States Department of Energy} project on simulating airflow in open-ocean windfarms. The opportunity was facilitated by Professor Paul Fischer at UIUC after I took his graduate numerical PDEs course as a junior. Under Dr. Ramesh Balakrishnan, and Dr. Aleksandr Obabko of the Mathematics and Computer Science division, I examined the physics of flows over curved geometries by conducting {Direct Numerical Simulations}. The interaction of boundary curvature and shear produced a free-shear layer separating from the back of the wavy wall and blocking off a persistent recirculation region before reattachment.

To facilitate the development of {wall-models} for {Large Eddy Simulations}, I computed the terms of the tensor Reynolds Stress Transport Equation within the spectral element fluid dynamics code NEK5000. The converged {Reynolds Stress budgets} (third order statistics) verify my DNS as well as reveal the spatial distribution and relative magnitudes of the production, dissipation, and transport mechanisms of turbulent energy.


## Argonne Natinoal Laboratory, 2020
I continued ANL 2018 work at UIUC as thesis research and returned to Argonne after graduation.

This time my work was on conducting Large Eddy Simulations (LES) of airflow near building-like geometries for the DOE’s Distributed Windproject. The overarching goal of my work is to obtain high-resolution  LES  and  DNS  data to  support  development  of subgrid-stress  models  and  wall-models for Detached Eddy Simulations and Reynolds Averaged Navier-Stokes simulations.

## Carnegie Mellon University, 2020
Started work on fully differentiable spectral element solver implemented in Julia.

## Julia Computing, 2021
`SEM.jl`, `NeuralPDE.jl`, `diffMesh.jl`, associated tech.
