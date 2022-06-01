# PML-FYP
## Investigating Absorbing Boundary Conditions for Computational Aeroacoustics Problems

I completed my Master's degree at Loughborough University in aeronautical engineering, specialising in computational aeroacoustics boundary conditions - supervised by Dr Hao Xia.

![Summary](https://user-images.githubusercontent.com/29175819/170326782-ae6e92cf-5b1b-4db2-9514-8c62bf1255bc.png)

### Summary

Presented are the methods and results of implementing & optimising a perfectly matched layer boundary condition in a MATLAB-based linearised Euler equation solver. 

The design of modern turbofan acoustic liners requires accurate prediction of wave propagation - characterised by the underlying numerical methods. This umbrella term encompasses many individual elements, but the boundary conditions are the focus of the project. A literature review has concluded that absorbing zone non-reflecting boundary conditions are top performers in their class, and have quite rightly been the subject of reams of research looking to increase prediction accuracy.


When discretised using dispersion relation preserving finite difference schemes and multi-level Adams Bashforth time integration schemes, the developed solver accurately predicts wave propagation in the domain, and the absorption of outgoing waves in the perfectly matched layer zone. The solver has shown to perform well when subject to NASA-sponsored CAA workshop problems, and predicts similarly to more mature research solvers.


The results indicate that there exists a finite set of BC parameter combinations that produce minimal domain error, and these conditions align relatively well with those that have been analytically derived in other research. Further work is necessary to assess these combinations on another research solver in order to solidify the conclusions.


### Target audience
This report should be accessible to 3rd and 4th year engineering students with basic knowledge of acoustics and fluid dynamics.



