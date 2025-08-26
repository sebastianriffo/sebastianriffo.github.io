---
layout: page

title: Projects

lang: en
ref: projects
ref2: academia

published: true
order: 2
---
<!--
## <strong style="color:#303F9F"> Personal projects </strong>
-->

<div class="row">
  <div class="column">
    <img src="/docs/prev/2024_MOMA.png">
    <div class="text">
    <a href="https://sebastianriffo.github.io/MOMA-static/dataviz.html" style="font-size: 18px; color:#b300b3" target="_blank">Metrics for ORCHIDEE Model Analysis (2024)</a>
    <br> A D3.js/Flask visualization prototype of mean climatologies and time series for IPSL's terrestrial module simulations. Static version hosted in github.
    </div>
  </div> 

  <div class="column">
    <img src="/docs/prev/2023_visualizacion-2.png">
    <div class="text">
    <a href="https://sebastianriffo.github.io/congreso-chile/en/home.html" style="font-size: 18px; color:#b300b3" target="_blank">Chilean parliamentary election maps (2023)</a>
    <br> An interactive visualization of the chilean parliamentary elections from 1932 onwards, for both the Chamber of Deputies and the Senate, integrating several public sources. 
    </div>
  </div>
</div>

<!--
  <div class="column">
    <img src="/docs/prev/2020_parareal_DD26_square.png">
    <div class="text">
    <strong style="font-size: 18px; color:#303F9F"> Parallel-in-time data assimilation </strong>
    <br> A procedure to couple unbounded in time data assimilation methods with the Parareal algorithm.
    </div>
  </div>

**Time-parallelization of sequential data assimilation problems.**

In the first part, we propose a procedure to couple unbounded in time data assimilation methods with time-parallel algorithms. The combination between the Luenberger observer and Parareal algorithm is studied, providing a way to estimate the number of parareal iterations required to preserve the observer rate of convergence, as well as an estimation of the theoretical efficiency of the entire procedure.

We propose a procedure to couple unbounded in time data assimilation methods with time-parallel algorithms. In order to do so, we design a procedure called Diamond
strategy, that consists in splitting the infinite time interval into bounded windows and then apply, following a sequential order, the time-parallel solver on each. The
problem we consider deals with the identification of a system state by using a Luenberger observer. This strategy gives rise to an exponential rate of convergence, that we aim at preserving when coupling it with the Parareal algorithm. We provide a way to estimate, on each window, the number of parareal iterations required to preserve the observer rate of convergence. In addition, we estimate the theoretical efficiency of the whole procedure.

## <strong style="color:#303F9F"> Past projects </strong>
In the last few years, my research focused on the development and analysis of algorithms for solving differential equations through  Domain Decomposition Methods (Parareal, Schwarz), with possible applications to data assimilation and imaging problems.

<div class="row">
  <div class="column">
    <img src="/docs/prev/2022_FD-Schwarz_square.png">
    <div class="text"> 
    <h4 style="color:#303F9F"> Domain decomposition methods for seismic imaging</h4> 
    </div>
  </div>
  <div class="column">
    <img src="/docs/prev/2021_batrymetry_inv-topography-top-approx_square.png">
    <div class="text"> 
    <h4 style="color:#303F9F"> Bathymetry optimization </h4> 
    </div>
  </div>
  <div class="column">
    <img src="/docs/prev/2021_BEM_Iter_square.png">
    <div class="text"> 
    <h4 style="color:#303F9F"> Analysis of algorithms </h4>
    </div>
  </div>
</div>

**ORAS** combined with geophysics**  
The young researcher will be in charge of the development and optimization of a time-harmonic wave-equation solver (Helmholtz problem) for applications in the fields of seismic and medical imaging. The numerical schemes will rely on a compact finite-difference method on regular Cartesian grids and on the finite element method on unstructured tetrahedral meshes. The numerical schemes will be developed for both the acousto- and elasto-dynamic equations. The linear system resulting from the discretization of the wave equation will be solved with iterative methods such as GMRES (Generalized minimal residual) preconditioned by the two-level domain-decomposition method ORAS (Two-level Optimized Restricted Additive Schwarz). The wave equation solver will be interfaced with 3D imaging code based upon frequency-domain Full Waveform Inversion (FWI), a PDE-constrained optimization problem for wavefield and parameter estimation 


#### <strong style="color:#E91E63">Optimization</strong>
**.**  

We then discuss the determination of a bathymetry from an optimization perspective. Imposing that wave propagation must fulfill a certain criterion associated with a cost functional, we consider a PDE-constrained optimization problem where the bathymetry plays the role of control and wave propagation is described by the Helmholtz equation. We are
able to prove, under suitable assumptions, the continuity of the control-to-state mapping and the existence of an optimal solution, including also some results about solutions to Helmholtz problem and convergence in a discrete framework. This work is complemented by numerical experiments.

Closely related to the previous topic...   

The wave equation is often used to model wave propagation in coastal engineering problems, since its simplicity leads to an explicit
solution, provided a flat bathymetry. Lifting this assumption yields a different formulation of the Helmholtz equation describing the total wave amplitude, being
necessary to address the continuity and boundedness of its solution. Since we are interested in the determination of a bathymetry from an optimal control perspec-
tive, we study a PDE-constrained optimization problem in which the bathymetry plays the role of control. We prove the continuity of the control-to-state mapping
and the existence of an optimal solution. The discrete optimization problem is also addressed, studying the convergence to the discrete optimal solution as well as the convergence of a FEM approximation.

**Mathematical analysis of the blade element momentum theory (BEM).**
The last part of this work is devoted to analyze the convergence of the Blade element momentum theory, a classical method used to determine the propeller efficiency as well as its design parameters. We propose a reformulation of the method that allows to obtain conditions for existence of solutions and establish the convergence of some solving
algorithms. We also study the associated optimization problem in certain contexts.
 
The Blade element momentum (BEM) theory is a classical method to determine the design parameters of a blade and maximize the propeller efficiency. Nevertheless, it has
never been analyzed from a mathematical point of view. We then propose a reformulation of the model that allows to obtain conditions for existence of solutions and
establish the convergence of some solving algorithms. We also study the associated optimization problem in various contexts.

The Blade Element Momentum theory (BEM), introduced by H. Glauert in 1926, provides a framework to model the aerodynamic interaction between a turbine and a fluid flow.
This theory is either used to estimate turbine efficiency or as a design aid. However, a lack of mathematical interpretation limits the understanding of some of its angles. The aim of this paper is to propose an analysis of BEM equations. Our approach is based on a reformulation of Glauert’s model which enables us to identify criteria which ensure the existence of solution(s). In this framework, we also study the convergence of solution algorithms and analyze turbine design procedures. The mathematical analysis is completed and illustrated by numerical experiments.
-->

