---
usemathjax: true
title: Research
layout: page
---
## <strong style="color:#303F9F">Research Interests</strong>
My current work focuses on the development and analysis of algorithms for solving differential equations, mainly using Domain Decomposition Methods (Parareal, Schwarz), to be applied to problems such as data assimilation, seismic imaging and blade design.  

From a mathematical point of view, my research is related with :

<!-- 
KEYWORDS
Parareal algorithm, Parallel data assimilation, 
Bathymetry optimization, Helmholtz equation, 
Blade element method, Blade design.
-->

#### <strong style="color:#0288D1">Domain decomposition methods</strong>

**Time-parallelization of sequential data assimilation problems.**
In the first part, we propose a procedure to couple unbounded in time data assimilation methods with time-parallel algorithms. The combination between the Luenberger observer and Parareal algorithm is studied, providing a way to estimate the number of parareal iterations required to preserve the observer rate of convergence, as well as an estimation of the theoretical efficiency of the entire procedure.

<!--
We propose a procedure to couple unbounded in time data assimilation methods with time-parallel algorithms. In order to do so, we design a procedure called Diamond
strategy, that consists in splitting the infinite time interval into bounded windows and then apply, following a sequential order, the time-parallel solver on each. The
problem we consider deals with the identification of a system state by using a Luenberger observer. This strategy gives rise to an exponential rate of convergence, that we aim at preserving when coupling it with the Parareal algorithm. We provide a way to estimate, on each window, the number of parareal iterations required to preserve the observer rate of convergence. In addition, we estimate the theoretical efficiency of the whole procedure.
-->

**ORAS** <!-- combined with geophysics**   
The young researcher will be in charge of the development and optimization of a time-harmonic wave-equation solver (Helmholtz problem) for applications in the fields of seismic and medical imaging. The numerical schemes will rely on a compact finite-difference method on regular Cartesian grids and on the finite element method on unstructured tetrahedral meshes. The numerical schemes will be developed for both the acousto- and elasto-dynamic equations. The linear system resulting from the discretization of the wave equation will be solved with iterative methods such as GMRES (Generalized minimal residual) preconditioned by the two-level domain-decomposition method ORAS (Two-level Optimized Restricted Additive Schwarz). The wave equation solver will be interfaced with 3D imaging code based upon frequency-domain Full Waveform Inversion (FWI), a PDE-constrained optimization problem for wavefield and parameter estimation -->


#### <strong style="color:#E91E63">Optimization</strong>
**Bathymetry optimization.**
<!-- 
We then discuss the determination of a bathymetry from an optimization perspective. Imposing that wave propagation must fulfill a certain criterion associated with a cost functional, we consider a PDE-constrained optimization problem where the bathymetry plays the role of control and wave propagation is described by the Helmholtz equation. We are
able to prove, under suitable assumptions, the continuity of the control-to-state mapping and the existence of an optimal solution, including also some results about solutions to Helmholtz problem and convergence in a discrete framework. This work is complemented by numerical experiments.
-->
Closely related to the previous topic...   

The wave equation is often used to model wave propagation in coastal engineering problems, since its simplicity leads to an explicit
solution, provided a flat bathymetry. Lifting this assumption yields a different formulation of the Helmholtz equation describing the total wave amplitude, being
necessary to address the continuity and boundedness of its solution. Since we are interested in the determination of a bathymetry from an optimal control perspec-
tive, we study a PDE-constrained optimization problem in which the bathymetry plays the role of control. We prove the continuity of the control-to-state mapping
and the existence of an optimal solution. The discrete optimization problem is also addressed, studying the convergence to the discrete optimal solution as well as the convergence of a FEM approximation.

#### <strong style="color:#E91E63">Analysis of algorithms</strong>

**Mathematical analysis of the blade element momentum theory (BEM).**
The last part of this work is devoted to analyze the convergence of the Blade element momentum theory, a classical method used to determine the propeller efficiency as well as its design parameters. We propose a reformulation of the method that allows to obtain conditions for existence of solutions and establish the convergence of some solving
algorithms. We also study the associated optimization problem in certain contexts.
 
<!--
The Blade element momentum (BEM) theory is a classical method to determine the design parameters of a blade and maximize the propeller efficiency. Nevertheless, it has
never been analyzed from a mathematical point of view. We then propose a reformulation of the model that allows to obtain conditions for existence of solutions and
establish the convergence of some solving algorithms. We also study the associated optimization problem in various contexts.
-->

<!--
The Blade Element Momentum theory (BEM), introduced by H. Glauert in 1926, provides a framework to model the aerodynamic interaction between a turbine and a fluid flow.
This theory is either used to estimate turbine efficiency or as a design aid. However, a lack of mathematical interpretation limits the understanding of some of its angles. The aim of this paper is to propose an analysis of BEM equations. Our approach is based on a reformulation of Glauert’s model which enables us to identify criteria which ensure the existence of solution(s). In this framework, we also study the convergence of solution algorithms and analyze turbine design procedures. The mathematical analysis is completed and illustrated by numerical experiments.
-->


