# Bachelorarbeit-Lisann-Radmacher

This Repository is the work that was made during my bachelor thesis. It is an expansion of the "BSeries.jl" package.
There are three topics that were implemented during the last weeks. These topics are symmetrie and symplecticity of methods as well as two derivative Runge-Kutta methods.

The folder "Notebooks" contains three notebooks, one notebook for each topic.
The folder "Julia Code" contains Julia files, one file for each topic.

The implementation for checking the symmetry of a method can be found in the file "SymmetryBA.ipynb" (or "SymmetryBA.jl"). 
In this file you'll find the implementation of the inverse and the adjoint of a given B-Series as well as the function returning up to what order a method is symmetric.

The implementation for checking the symplecticity of a method can be found in the file "SymplecticBA.ipynb" (or "SymplecticBA.jl").
In this file you'll find the implementation of the symplecticity condition, the function which checks the condition for a pair of trees and the function returning up to what order a method is symplectic.

The implementation for two derivative Runge-Kutta methods can be found in the file "TDRK.ipynb" (or "TDRK.jl").
In this file you'll find the implementation of TDRK methods as a new time integration method, the elementary weight of a TDRK method as well the B-series of TDRK method.
