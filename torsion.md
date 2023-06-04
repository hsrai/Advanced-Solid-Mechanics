# TORSION OF PRISMATIC BARS

### INDEX
1. Saint Venant's Method
2. Prandtl's Membrane Analogy
3. Torsion of Rectangular Bar
4. Torsion of Thin Tubes

## Torsion of Prismatic Bars
Torsion: Torsion of a uniform bar of homogeneous isotropic material means twisting deformation produced by equal and opposite twisting moments applied to the ends of the bar. 
![torsion](https://github.com/Harsimrat05/Advanced-Solid-Mechanics/assets/126183138/9fc8b08b-586b-43fd-9212-02ffc7171de6)

## Saint Venant's Method
Saint Venant's method is a mathematical approach used in solid mechanics to analyze the behavior of a structural member subjected to external loads.

The Saint Venant's method involves replacing a complex, three-dimensional solid body with a simpler, two - dimensional cross-section that can be analyzed more easily. This simplification is made possible by the fact that the stress and strain distributions in a solid body are highly concentrated near the points of load application and tend to dissipate quickly away from these points.
The two-dimensional cross-section is analyzed using the theory of elasticity to determine the stress and strain distributions. These distributions are then used to calculate the deformations and internal forces that result from the applied loads.   

Assume that the cross section is rotated about an axis, the twist per length be $\theta$.
Let the component 0f this displacement are:
$U_x = -r \theta z sin \beta $..............(1)

$U_y = r \theta z cos \beta$..............(2)

![rai sir1](https://github.com/Harsimrat05/Advanced-Solid-Mechanics/assets/126183138/0f6c6dd0-651e-40cc-bed6-c89d06f963eb)

$sin \beta= \frac{y}{r}$

$cos \beta= \frac{x}{r}$

Now put the value of $sin \beta$ and $cos \beta$ in equation 1 and 2.

$U_x=-\theta y z$..............(3)

$U_y=\theta x z$..............(4)

$U_z=\theta \psi (x,y)$..............(5)

$\psi(x,y)$ is called warping function.

then from displacement components, calculate strain components.

$\epsilon_{xx}=\frac{\partial u_x}{\partial x}$

$\epsilon_{yy}=\frac{\partial u_y}{\partial y}$

$\epsilon_{zz}=\frac{\partial u_z}{\partial z}$

$\gamma_{xy}=\frac{\partial u_x}{\partial u_y} + \frac{\partial u_y}{\partial x}$

$\gamma_{yz}=\frac{\partial u_y}{\partial z} + \frac{\partial u_z}{\partial y}$

$\gamma_{zx}=\frac{\partial u_x}{\partial z} + \frac{\partial u_z}{\partial x}$

Then from equation 3,4,5

$\epsilon_{xx}=\epsilon_{yy}=\epsilon_{zz}=\gamma_{xy}=0$

$\gamma_{yz}= \theta (\frac{\partial\psi}{\partial y} + x)$.............(6)

$\gamma_{zx}= \theta (\frac{\partial\psi}{\partial x} - y)$

Then from hooke's law, we have,

$\sigma_x=\frac{vE}{(1+v)(1-2v)} \Delta+\frac{E}{1+v} \epsilon_{xx}$

$\sigma_y=\frac{vE}{(1+v)(1-2v)} \Delta+\frac{E}{1+v} \epsilon_{yy}$

$\sigma_z=\frac{vE}{(1+v)(1-2v)} \Delta+\frac{E}{1+v} \epsilon_{zz}$

$\tau_{xy} = G\gamma_{xy}, \tau_{yz} = G\gamma_{yz}, \tau_{zx} = G\gamma_{zx}$

where $\Delta = \epsilon_{xx} + \epsilon_{yy} + \epsilon_{zz}$

Substituting the above set of equation in it as :

$\sigma_x =\sigma_y = \sigma_z = \tau_{xy} = 0$

$\tau_{yz} = G\theta (\frac{\partial \psi}{\partial y} + x )$

$\tau_{zx} = G\theta (\frac{\partial \psi}{\partial x} - y )$

The above stress component should satisfy the equillibrium equations:

$\frac{\partial\sigma_x}{\partial_x} + \frac{\partial\tau_{xy}}{\partial y} + \frac{\partial\tau_{zx}}{\partial z} = 0$

$\frac{\partial\tau_{xy}}{\partial_x} + \frac{\partial\sigma_y}{\partial_y} + \frac{\partial\tau_{zx}}{\partial_z} = 0$

$\frac{\partial\tau_{zx}}{\partial_x} + \frac{\partial\tau_{yz}}{\partial_y} +\frac{\partial\sigma_z}{\partial_z} = 0$

Substituting the stress components, the two  equations gets satisfied and third equation we obtained as

$G\theta(\frac{\partial^2\psi}{\partial_x^2} +\frac{\partial^2\psi}{\partial_y^2})= 0$

$\frac{\partial^2\psi}{\partial_x^2} +\frac{\partial^2\psi}{\partial_y^2} = \nabla^2\psi = 0 $

consider the boundary conditions. If Fx, Fy and Fz are the components of the stress on a plane with outward normal n (nx, ny, nz) at a point

$n_x \sigma_x + n_y\tau_{xy} + n_z\tau_{xz} = F_x$

$n_x \tau_{xy} + n_y\sigma_y + n_z\tau_{yz} = F_y$

$n_x \tau_{xz} + n_y\tau_{yz} + n_z\sigma_z = F_z$

In this case, there are no forces acting on the boundary and the normal n to the surface is perpendicular to the z-axis, i.e. $n_z$ = 0.\par Using the stress components we get the first two equations are satisfied. the third equation yields as

$G\theta(\frac{\partial\psi}{\partial_x} - y)n_x +$ $G\theta(\frac{\partial\psi}{\partial y}+x)n_y =0$

put $n_x = cos(n,x)=\frac{dy}{dx}$

$n_y = cos(n,y) = \frac{-dx}{ds} $

Substituting the value in above equation:

$(\frac{\partial\psi}{\partial x} - y)\frac{dy}{ds} -$ $(\frac{\partial\psi}{\partial y} + x)\frac{dx}{ds} = 0$

For finding the resultant forces in the region. integrate 

$\iint_R \tau_{zx} d_xd_y = G\theta \iint_R(\frac{\partial\psi}{\partial x}-y)d_x d_y$ 

Then using Gauss theorem the above surface integral gets converted to the line integral as:

$\iint_R \tau_{zx} d_xd_y = G\theta \oint_S[(\frac{x \partial\psi}{\partial x}-y)n_x + x(\frac{\partial\psi}{\partial y} + x)n_y]$  = 0

After applying the boundary conditions we get

$T = GJ \theta$   ................. eq. (A) 

From the above equation (A) it is clear that torque T is proportional to the angle of twist per unit length $\theta$

Here  T= torque

GJ = Torsional Rigity 
     
## Prandtl's membrane analogy

It is also known as the boundary layer analogy, is a concept in fluid dynamics that compares the flow of fluid over a solid surface to the behavior of a thin, elastic membrane that is attached to the surface.

The thin layer of fluid near the surface is called the boundary layer, and its behavior can be modeled using the same mathematical equations that describe the behavior of a thin, elastic membrane. In other words, the behavior of the boundary layer is analogous to the behavior of a membrane that is attached to the surface and moves in response to the flow of fluid.

This analogy has been used to develop theories and models for the study of fluid flow.

Prandtl leads to a simpler boundary condition.

In this method, the principal unknowns are the stress components rather than the displacement components as in the previous approach.

The stress components 

$\sigma_x, \sigma_y, \sigma_z$ 
and 
$\tau_{xy}$ 

are assumed to be zero. In order to satisfy the equations of equilibrium we should have


$\frac{ \partial \tau_{zx} } {\partial Z} = 0, \frac{ \partial \tau_{yz} } {\partial Z} = 0, \frac{ \partial \tau_{zx} } {\partial Z}  + \frac{ \partial \tau_{yz} } {\partial Z} = 0$

If it is assumed that in the case of pure torsion, the stresses are the same in every normal cross-section, i.e. independent of z, then the first two conditions above are automatically satisfied. In order to satisfy the third condition, we assume a function
$\phi $ 
(x, y) called the stress function, such that

 $\tau_{zx} = \frac{\partial \phi }{\partial y}$ ,
 $\tau_{yz} = - \frac{\partial \phi }{\partial x}$
 
 With this stress function (called Prandtl’s torsion stress function), the third condition is also satisfied.  
 
The assumed stress components, if they are to be proper elasticity solutions, have to satisfy the compatibility conditions. We can substitute these directly into the stress equations of compatibility. Alternatively, we can determine the strains corresponding to the assumed stresses and then apply the strain compatibility conditions given by Eq.

The strain components from Hooke's law are

$\epsilon_{xx} = 0,$
$\epsilon_{yy} = 0,$
$\epsilon_{zz} = 0,$ 

$\gamma_{xy}=0,     \gamma_{yz}= \frac{1}{G} \tau_{yz},     \gamma_{zx}=\frac{1}{G} \tau_{zx},$   

Substituting from Eq.

$\gamma_{yz} = - \frac{1}{G}\frac{\partial\phi}{\partial_x},$ 
and 
$\gamma_{zx} = - \frac{1}{G}\frac{\partial\phi}{\partial_y}$

The non-vanishing strain compatibility conditions are (observe that 
$\phi$
is independent of z

$\frac{\partial}{\partial_X} (- \frac{\partial\gamma_yz}{\partial_X} + \frac{\partial\gamma_zx}{\partial_y}) = 0$

$\frac{\partial}{\partial_y} (\frac{\partial\gamma_yz}{\partial_X}-\frac{\partial\gamma_zx}{\partial_y}) = 0$

$\frac{\partial}{\partial_X} (\frac{\partial^2\phi}{\partial_x^2} + \frac{\partial^2\phi}{\partial_y^2}) = 0;$

$\frac{\partial}{\partial_y} (\frac{\partial^2\phi}{\partial_x^2} + \frac{\partial^2\phi}{\partial_y^2}) =0$

Hence, 
$\frac{\partial^2\phi}{\partial_x^2} + \frac{\partial^2\phi}{\partial_x^2} = \nabla^2\phi$ 
= a constant F 

The stress function, therefore, should satisfy Poisson's equation. The constant "F" is yet unknown. Next, we consider the boundary conditions.
The first two of these are identically satisfied. The third equation gives

Substituting for 
$n_x$ 
and 
$n_y$
from Equation:

$n_x \frac{\partial\phi}{\partial_y} - n_y \frac{\partial\phi}{\partial_x}$

i.e.  
$\frac{d\phi}{ds}=0$

Therefore, 
$\phi$
is constant around the boundary. Since the stress components depend only on the differentials of 
$\phi$

Now For a simply connected region, no loss of generality is involved in assuming

$\phi = 0$
on s

For a multi-connected region R, certain additional conditions of compatibility are imposed.

On the two end faces, the resultants in x and y directions should vanish, and the moment about O should be equal to the applied torque T. The resultant in x direction is

$= \int\int_R \tau_{zx} dx dy =  \int\int_R \frac{\partial\phi}{\partial_y} dy =0$

Since 
$\phi$
is constant around the boundary. Similarly, the resultant in y direction also vanishes. Regarding the moment:

T = 
$\int\int_R ( x\tau_{zy} - y\tau_{zx})  dx dy$

Integrating by parts and observing that 
$\phi$
= 0 of the boundary, we find that each integral gives  

$\int\int \phi  dx dy$ 

Thus,
$T = 2\int\int\phi dx dy$ 

Hence, we observe that half the torque is due to 
$\tau_{zx}$ 
and the other half to 
$\tau_{yz}$.

Thus, all differential equations and boundary conditions are satisfied.

## Torsion of Rectangular Bars
Torsion of rectangular bars is a common phenomenon in solid mechanics that occurs when a rectangular bar or shaft is subjected to a twisting force or torque. The torsional stress caused by the twisting force produces shear stresses in the material that can cause deformation or failure if the stress exceeds the material's yield strength.

Let the sides of the rectangular cross-section be 2a and 2b with the origin at the centre, as shown in Figure.

![rect](https://github.com/Harsimrat05/Advanced-Solid-Mechanics/assets/126183138/4280f1e9-d6b7-47aa-909d-264557b21ffe)
![rect 2](https://github.com/Harsimrat05/Advanced-Solid-Mechanics/assets/126183138/0a4ddc7d-a2f9-4c2e-b8ca-cf84ccb1a326)

Our equations are,

$\frac{\partial^2 \psi}{\partial x^2} + \frac{\partial^2 \psi}{\partial y^2} = 0$ 

over the whole region R of the rectangle, and 

$(\frac{\partial\psi}{\partial x} - y)n_x + (\frac{\partial\psi}{\partial y} - x)n_y = 0$

on the boundary. Now on the boundary lines 
$x= \pm a$
or AB and CD, we have 
$n_x= \pm 1$
and 
$n_y= 0$.
On the boundary lines BC and AD, we have 
$n_y=x= 0$
and 
$n_y= \pm 1$.
Hence, the boundary conditions become 

$\frac{\partial\psi}{\partial x} = y$
on 
$x= \pm a$

$\frac{\partial\psi}{\partial y} = -x$
on 
$y= \pm b$

These boundary conditions can be transformed into more convenient forms if we introduce a new function $\psi_1$, such that

$\psi = xy - \psi_1$

In terms of 
$\psi_1$
, the governing equation is 

$\frac{\partial^2 \psi_1}{\partial x^2} + \frac{\partial^2 \psi_1}{\partial y^2} = 0$ 

over region R, and the boundary conditions become

$\frac{\partial\psi_1}{\partial x} = 0$ 
on 
$x= \pm a$

$\frac{\partial\psi_1}{\partial y} = 2x$  
on 
$y= \pm b$

It is assumed that the solution is expressed in the form of infinite series

$\[\psi = \sum_{n=1}^{\infty} X_n (x) Y_n (y)\]$

where 
$X_n$
and $Y_n$
are respectively functions of x alone and y alone. Substitution into the Laplace equation for 
$\psi_1$
yields two linear ordinary differential equations with constant coefficients. Further details of the solution can be obtained by referring to books on theory of elasticity. The final results which are important are as follows:

The function J is given by

$J= Ka^3b$

## Torsion of Thin-Walled Tubes

Consider a thin-walled tube subjected to torsion. The thickness of the tube need not be uniform. Since the thickness is small and the boundaries are free, the shear stresses will be essentially parallel to the boundary. Let 
$\tau$
be the magnitude of the shear stress and 
$t$
the thickness.

Consider the equilibrium of an element of length 
$\Delta l$,
as shown. The areas of cut faces AB and CD are respectively 
$t1 \Delta l$
and 
$t2 \Delta l$.

The shear stresses (complementary shears) are t1 and t2. For equilibrium in z direction we should have 

$\tau_1 t_1 \Delta l + \tau_2 t_2 \Delta l = 0$

![thin tube 1](https://github.com/Harsimrat05/Advanced-Solid-Mechanics/assets/126183138/4b2032e5-5419-4654-ad43-1a99e157e93b)

or
$\tau_1 t_1 = \tau_2 t_2 = q,$
a constant 

Hence, the quantity 
$\tau t$
is a constant. This is called the shear flow q, since the equation is similar to the flow of an incompressible liquid in a tube of varying area. For continuity, we should have 
$V_1A_1 = V_2A_2,$
where A is the area and V the corresponding velocity of the fluid there.

Consider next the torque of the shear about point O 

![2](https://github.com/Harsimrat05/Advanced-Solid-Mechanics/assets/126183138/e3335672-2023-41bf-afc9-c29283d3707f)
![3 tube](https://github.com/Harsimrat05/Advanced-Solid-Mechanics/assets/126183138/1868b0ef-57ec-4cc2-99fa-756b7e156543)

The force acting on an elementary length 
$\Delta s$
of the tube is

$\Delta F = \tau t \Delta s = q \Delta s$

The moment arm about O is h and hence, the torque is

$\Delta T = q \Delta sh = 2q \Delta A$ 

where 
$\Delta A$
is the area of the triangle enclosed at O by the base s. Hence, the total torque is 

$T= \sum 2 q \Delta A = 2 q A$ 

Where A is the area enclosed by the centre line of the tube. Equation is generally known as the Bredt–Batho formula. 

To determine the twist of the tube, we make use of Castigliano’s theorem. Referring to Fig., the shear force on the element is 
$\tau t \Delta s = q \Delta s$.
Because of shear strain 
$\gamma$,
the force does work equal to 

$\Delta U = \frac{1}{2} (\tau t \Delta s) \delta$ 

$= \frac{1}{2} (\tau t \Delta s) \gamma \Delta l$ 

$= \frac{1}{2} (\tau t \Delta s) \gamma \Delta l \frac{\tau}{G}$

$= \frac{q^2 \Delta l}{2 G} \frac{\Delta s}{t}$ 
 
$= \frac{T^2 \Delta l}{8 A^2 G} \frac{\Delta s}{t}$ 

using Eq. The total elastic strain energy is therefore 

$U= \frac{T^2 \Delta l}{8 A^2 G} \oint \frac{ds}{t}$

Hence, the twist or the rotation per unit length 
$(\Delta l = 1)$ 
is 

$\theta = \frac{\partial U}{\partial T} = \frac{T}{4A^2 G} \oint \frac{ds}{t}$ 

Using once again Eq. 

$\theta = \frac{q}{2 A G } \oint \frac{ds}{t}$

### Some Question's

1. Derive the governing equation for the solution to the general torsion using St. Venant's method.
2. Explain Prandtl stress function approach used in torsion of prismatic straight beam.
3. Discuss in detail, the torsion of thin walled tubes.

### Numericals


1.  (i) A 30 cm I Shape beam, with flanges and with a web 1.25 cm thick, is subjected to a torque T = 50000 kgfcm (4900 Nm).Find the maximum shear stress and the angle of twist per unit length.

(ii) In order to reduce the stress and the angle of twist, 1.25 cm thick flat plates are welded onto the sides of the section, as shown by dotted lines. Find the maximum shear stress and the angle of twist.
