## Solving two dimensional problem of solid mechanics

There are several methods to solve
two-dimensional problems in solid mechanics,
including:

1.  Analytical Methods: These methods
involve solving equations by hand, often
using mathematical techniques such as
calculus and linear algebra.  These methods
are typically used to solve relatively
simple problems where the geometry and
boundary conditions are well-defined.

1.  Finite Element Method (FEM): This is a
numerical method that divides the problem
into smaller, simpler elements and then
solves for the unknowns at each node of the
mesh.  FEM is a powerful and flexible method
that can handle complex geometries and
boundary conditions, but it requires
significant computational resources and
expertise.

1.  Boundary Element Method (BEM): This is a
numerical method that solves the governing
equations using only the boundary conditions
of the problem.  BEM is often used for
problems with infinite domains or for
problems where the solution is expected to
be smooth near the boundary.

1.  Meshless Methods: These are numerical
methods that do not require a predefined
mesh to solve the problem.  Instead, they
use scattered data points to construct a
basis function that can be used to
approximate the solution.  Meshless methods
are particularly useful for problems with
complex geometries or for problems where the
domain changes over time.

1.  Analytical-Numerical Hybrid Methods:
These methods combine the advantages of
analytical and numerical methods.  For
example, the method of differential
quadrature (DQ) combines the accuracy of
analytical methods with the flexibility of
numerical methods.  In DQ, the governing
equations are discretized using a set of
discrete points, and the unknowns are
expressed as a series of weighted functions.

1.  Airy's stress function method: It
involves introducing a scalar function,
known as the Airy stress function, which
satisfies Laplace's equation and is related
to the stresses in the material.  By using
the Airy stress function, the problem can be
reduced to a set of two simultaneous partial
differential equations that can be solved
using analytical or numerical techniques.

1.  Cauchy's integral method: This method
involves expressing the stresses in terms of
a complex variable and then using complex
analysis techniques to solve for the
stresses.  This method is particularly
useful for problems with circular or
rectangular domains, where the solution can
be expressed in terms of simple, closed-form
integrals.

## Procedure for solving problems using Airy's stress function:

1. Step 1: Identify the governing equations

    The first step is to identify the governing
equations that describe the deformation of
the solid under the applied loads.  These
equations are typically given in terms of
the stresses and strains in the material,
and can be derived from the laws of
conservation of mass, momentum, and energy.

    In two-dimensional problems, the governing
equations typically take the form of two
simultaneous partial differential equations,
which relate the stress components to the
derivatives of the Airy stress function. 
These equations are given by:

    σ_xx = ∂²ψ/∂y²

    $$\sigma_{xx} = \frac{\partial^2\psi}{\partial y^2}$$

    σ_yy = ∂²ψ/∂x²

    $$\sigma_{yy} = \frac{\partial^2\psi}{\partial x^2}$$

    where σ_xx and σ_yy are the normal stresses
in the x and y directions, respectively, and
ψ is the Airy stress function.

1. Step 2: Define the domain and boundary
conditions

    The next step is to define the domain over
which the problem is being solved and the
boundary conditions that must be satisfied. 
The domain is typically defined by
specifying the geometrical shape of the
solid, such as a rectangle or a circle.

    The boundary conditions specify the stress
or displacement conditions on the boundaries
of the domain.  For example, the boundary
conditions might specify that the normal
stresses are zero on a certain boundary, or
that the displacement is fixed at a certain
point.

1. Step 3: Introduce the Airy stress function

The next step is to introduce the Airy
stress function, which is a scalar function
that satisfies Laplace's equation and is
related to the stresses in the material. 
The Airy stress function is typically
defined as:

ψ = ∑(A_nsinh(nπy/h) +
B_ncosh(nπy/h))(C_ncos(nπx/h) +
D_nsin(nπx/h))

where h is the height of the solid, A_n,
B_n, C_n, and D_n are constants, and n is an
integer that determines the number of terms
in the series.

1. Step 4: Solve for the constants

The next step is to solve for the constants
A_n, B_n, C_n, and D_n by applying the
boundary conditions.  This involves
evaluating the Airy stress function and its
derivatives at the boundaries of the domain,
and then equating them to the specified
stress or displacement conditions.

1. Step 5: Compute the stresses and strains

Once the constants have been determined, the
stresses and strains in the material can be
computed using the partial differential
equations in Step 1.  This involves taking
the derivatives of the Airy stress function
with respect to x and y, and then
substituting them into the equations for
σ_xx and σ_yy.

1. Step 6: Check for equilibrium and
compatibility

The final step is to check that the stresses
and strains satisfy the equilibrium and
compatibility conditions.  Equilibrium
requires that the sum of the forces and
moments acting on the solid is zero, while
compatibility requires that the strains are
compatible with the deformation of the
material.

In summary, the steps involved in solving
two-dimensional problems in solid mechanics
using Airy's stress function method are to
identify the governing equations, define the
domain and boundary conditions, introduce
the Airy stress function, solve for the
constants, compute the stresses and strains,
and check for equilibrium and compatibility. 
While this method can be computationally
intensive, it is a powerful and flexible
tool for solving a wide range of solid
mechanics problems.

## Airy's stress function.

Airy's stress function is a scalar function
that is used to describe the stress state in
a solid subject to applied loads.  It was
introduced by George Biddell Airy, an
English mathematician and physicist, in the
mid-19th century as a method for solving
problems in elasticity.

The Airy stress function, denoted by ψ,
satisfies Laplace's equation, which is a
second-order partial differential equation
that describes the behavior of the function
in the interior of the solid.  In
two-dimensional problems, the Airy stress
function is typically defined as:

ψ = ∑(A_nsinh(nπy/h) +
B_ncosh(nπy/h))(C_ncos(nπx/h) +
D_nsin(nπx/h))

where h is the height of the solid, A_n,
B_n, C_n, and D_n are constants, and n is an
integer that determines the number of terms
in the series.

The stresses in the material can then be
calculated from the derivatives of the Airy
stress function with respect to the x and y
coordinates.  Specifically, the normal
stresses in the x and y directions are given
by:

σ_xx = ∂²ψ/∂y²
σ_yy = ∂²ψ/∂x²

The advantage of using Airy's stress
function is that it reduces the number of
equations that need to be solved, and can
simplify the calculation of stresses in
complex geometries.  In addition, it allows
for the use of boundary conditions that are
more general than those that can be
expressed in terms of displacement or stress
components.

## About Airy's stress function

Airy's stress function is a mathematical
tool used in solid mechanics to simplify the
calculation of stresses and strains in a
solid under applied loads.  It was developed
by the English mathematician and physicist
George Biddell Airy in the mid-19th century.

The Airy stress function is a scalar
function that satisfies Laplace's equation
and is related to the stresses in the
material.  It can be defined for
two-dimensional problems as a function of
the two coordinates x and y, and is
typically denoted by ψ.  The function is
chosen such that it satisfies certain
boundary conditions, such as zero stresses
on certain boundaries, and it simplifies the
calculation of the stresses and strains
throughout the material.

The relationship between the Airy stress
function and the stresses in the material is
given by two partial differential equations,
which are derived from the equations of
equilibrium and compatibility. 
Specifically, in two-dimensional problems,
the normal stresses in the x and y
directions are given by:

σ_xx = ∂²ψ/∂y²
σ_yy = ∂²ψ/∂x²

By solving for the Airy stress function and
substituting it into these equations, the
stresses throughout the solid can be
determined.  In addition, the Airy stress
function can be used to determine the
displacement and strain fields, as well as
the energy stored in the material.

The use of Airy's stress function can
greatly simplify the calculation of stresses
and strains in complex geometries, and it
has found wide application in the analysis
of mechanical and structural systems.

## How to find Airy's stress function?

There are several methods for finding Airy's
stress function depending on the problem at
hand, but one common approach is to use the
principle of superposition to construct a
function that satisfies the boundary
conditions of the problem.

Here are the general steps to find Airy's
stress function for a two-dimensional solid
mechanics problem:

Write down the equations of equilibrium and
compatibility for the problem.

Determine the boundary conditions for the
problem, including any prescribed stresses
or displacements.

Write the Airy stress function as a series
of terms that satisfy the boundary
conditions.

Substitute the Airy stress function into the
equations of equilibrium and compatibility
to obtain a set of equations that relate the
coefficients of the terms in the series.

Solve for the coefficients using the
boundary conditions, and use them to
construct the complete Airy stress function.

Calculate the stresses and strains in the
material using the Airy stress function, and
verify that they satisfy the equations of
equilibrium and compatibility.

Here is an example of how to find Airy's
stress function for a problem involving a
rectangular plate with a central circular
hole under a uniform tensile stress:

The equations of equilibrium and
compatibility are:

∂σ_xx/∂x + ∂σ_xy/∂y + F_x = 0
∂σ_xy/∂x + ∂σ_yy/∂y + F_y = 0
∂²u/∂x² + ∂²u/∂y² = 0
∂u/∂x = ε_xx
∂u/∂y = ε_yy

where σ_xx and σ_yy are the normal stresses
in the x and y directions, σ_xy is the shear
stress, F_x and F_y are the applied forces,
u is the displacement, and ε_xx and ε_yy are
the normal strains in the x and y
directions.

The boundary conditions for this problem are:
σ_xx = σ_0
σ_yy = 0 at y = ±b/2 and x = ±a/2
σ_xy = 0 on all boundaries
u = 0 on all boundaries except on the edge of the hole, where u is continuous

The Airy stress function can be written as:

ψ = A(x²-y²) + Bxy + Cx³ + Dy³ + E(x²-y²)² +
F(x²-y²)xy + Gxy³

where A, B, C, D, E, F, and G are constants.

Substitute the Airy stress function into the
equations of equilibrium and compatibility
to obtain a set of equations that relate the
coefficients of the terms in the series:

∂²ψ/∂y² = σ_xx = σ_0
∂²ψ/∂x² = σ_yy = 0
∂²ψ/∂x∂y = σ_xy = 0
∂²ψ/∂x² + ∂²ψ/∂y² = 0

These equations can be used to solve for the
constants A, B, C, D, E, F, and G.

Use the boundary conditions to determine the
values of the constants.  For example, the
condition that σ_xx = σ_0 at the edge of the
hole implies that A = -σ_0/4b.  Once all the
constants have been determined, the complete
Airy stress function can be constructed.

Calculate the stresses and strains in the
material using the Airy stress function, and
verify that they satisfy the equations of
equilibrium and compatibility.

This is just one example of how to ... limit
crossed :-(

-----

Other methods.

Stiffness Method
Displacement Method
Variational Methods (e.g., Ritz Method, Galerkin Method)
Weighted Residuals Methods (e.g., Least-Squares Method, Collocation Method)
Isoparametric Formulation
Substructuring Methods (e.g., Guyan Reduction Method)
Reduced Integration Methods
Penalty Methods
Augmented Lagrangian Methods
Element-Free Galerkin (EFG) Method
Smoothed Particle Hydrodynamics (SPH)
Peridynamics
Extended Finite Element Method (XFEM)
Partition of Unity Method (PUM)
Material Point Method (MPM)
Radial Basis Function (RBF) Method
Differential Quadrature Method (DQM)
Spectral Element Method (SEM)
Spectral Finite Element Method (SFEM)
Higher-order Continuum Mechanics (HOCM)
Distinct Element Method (DEM)
Lattice Boltzmann Method (LBM)
Smoothed Finite Element Method (SFEM)
Note that some of these methods may overlap or have variations, and there may be other methods not included in this list.

