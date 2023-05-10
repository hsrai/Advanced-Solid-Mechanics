# Advanced Solid Mechanics - Unit 4
## Two-Dimensional Problems of Elasticity

---
## CONTENT
 - Plane Stress and Plane Strain 
 - Airy’s stress Function
 - Use of Airy’s function in beam analysis
 - Two-Dimensional Problems in Polar Coordinates
 
---

## PLANE STRESS

A thin plate is loaded by forces applied at the boundary, parallel to the plane of the plate and distributed uniformly over the thickness. 

 \includegraphics[scale=0.35]{Plane Stress-1.png}

- Because the plate is thin in the z direction, there can be little variation in these stress components through the thickness, and thus they will be approximately zero throughout.

- The stress components, 

$$ \sigma_z = \tau_{xz} = \tau_{yz} = 0 $$

on both faces of the plate, also zero within the plate. The state of stress is then specified by $\sigma_x$, $\sigma_y$ and $\tau_{xy}$ only and is called plane stress.

So, plane stress is a stress, which acts only in a plane, which is only possible when: 

- All stress is applied in a single plane.
- Plane stress exists when one of the three principal stresses is zero.

---
## PLANE STRAIN

A long cylindrical or prismatical body is loaded by forces which are perpendicular to the longitudinal elements and do not vary along the length. 

\includegraphics[scale=0.4]{Plane Strain-1.png}
    
- Displacement in the axial direction is prevented by confining it between fixed rigid planes.

Since there is no axial displacement at the ends, and, by symmetry, at the mid-section, it may be assumed that the same holds at every cross section.

- $u$, $v$ and $w$ are the displacements in X-axis, Y-axis and Z-axis respectively.
- The displacements $u$ and $v$ are function of $x$ and $y$ and longitudinal displacement $w$ is zero.

Hence, 

$$ \gamma_{yz} = \frac{\partial v}{\partial z} + \frac{\partial w}{\partial y}  = 0 $$

$$ \gamma_{xz} = \frac{\partial u}{\partial z} + \frac{\partial w}{\partial x} = 0 $$

$$ \epsilon_z = \frac{\partial w}{\partial z} = 0 $$

The state of strain is then specified by $\epsilon_x$, $\epsilon_y$ and $\gamma_{xy}$ only and is called plane strain.

So, plain strain is a strain, which only acts in that respective plane. It is only possible when,

- Loading is done perpendicular to longitudinal axis.
- Magnitude of loading does not change with length.

---

## AIRY'S STRESS FUNCTION

- Solutions to plane strain and plane stress problems are obtained by using various stress function techniques.
- These techniques employ the Airy stress function to reduce the generalized formulation to the governing equations with solvable unknowns. 
- The method is started by reviewing the equilibrium equations for the plane problem without a body force.

From differential equations of equilibrium, 

$$ \frac{\partial \sigma_{x}}{\partial x} + \frac{\partial \tau_{xy}}{\partial y} + \frac{\partial \sigma_{xz}}{\partial z} = 0 $$ 
$$ \frac{\partial \tau_{xy}}{\partial x} + \frac{\partial \sigma_{y}}{\partial y} + \frac{\partial \tau_{yz}}{\partial z} = 0 $$
$$ \frac{\partial \tau_{xz}}{\partial x} + \frac{\partial \tau_{yz}}{\partial y} + \frac{\partial \sigma_{z}}{\partial z} = 0 $$

For plain stress condition in 2D,

$$ \sigma_z = \tau_{yz} = \tau_{xz} = 0 $$

So, Eq (1) and Eq (2) becomes,

$$ \frac{\partial \sigma_{x}}{\partial x} + \frac{\partial \tau_{xy}}{\partial y} = 0 $$

$$ \frac{\partial \tau_{xy}}{\partial x} + \frac{\partial \sigma_{y}}{\partial y} = 0 $$

It is observed that these equations will be identically satisfied by choosing a representation

$$ \sigma_x = \frac{\partial^2 \phi}{\partial y^2} $$
$$ \sigma_y = \frac{\partial^2 \phi}{\partial x^2} $$
$$ \tau_{xy} = -\frac{\partial^2 \phi}{\partial x \partial y} $$

where $\phi = \phi(x,y)$ is called the Airy stress function.

---

## USE OF AIRY'S FUNCTION IN BEAM ANALYSIS

#### Problem - $\phi = Ay^2$

#### Solution -  if the function is an Airy's Function then $\nabla^4 \phi = 0$ must be satisfied

$$ \nabla^4(Ay^2) = 0 $$ 

Using Bi- harmonic relation 

   $$ \frac{\partial (Ay^2)}{\partial x^4} + \frac{\partial^2 }{\partial x^2}.\frac{\partial^2 (Ay^2)}{\partial y^2 } + \frac{\partial^4(Ay^2)}{\partial y^4}= 0 $$

$$ 0 + 0 + 0 = 0 $$

means $\phi$ can be able to define $\sigma_{xx} , \sigma_{yy} , \tau_{xy}$

So , 

$$ \sigma_{xx} = \frac{\partial^2 \phi}{\partial y^2} = 2A $$
$$ \sigma_{yy} = \frac{\partial^2 \phi}{\partial x^2} = 0 $$
$$ \tau_{xy} = -\frac{\partial^2 \phi}{\partial x \partial y} = 0 $$

So, we have uniaxial tension .

---
### Problem - Determine the stress in Cartesian coordinate using Airy's Stress Functions for simply supported beam, such that 


  $$ x_o = \[ \int_{-b}^{+b} \sigma_{xx} .y \,dy \] $$  

  
 ### Solution - 
 
$\phi = cy^3$

 check - $\nabla^4 \phi = 0$

  $$ \frac{\partial (Cy^3)}{\partial x^4} + \frac{\partial^2 }{\partial x^2}.\frac{\partial^2 (Cy^3)}{\partial y^2 } + \frac{\partial^4(Cy^3)}{\partial y^4}= 0 $$
  
  $$ 0=0 $$

  now, 
  
  $$ \sigma_{xx} = \frac{\partial^2 \phi}{\partial y^2} =\frac{\partial^2 (Cy^3)}{\partial y^2}=6Cy $$
  $$ \sigma_{yy} = \frac{\partial^2 \phi}{\partial x^2} =\frac{\partial^2 (Cy^3)}{\partial x^2}=0 $$
  $$ \tau_{xy} = -\frac{\partial^2 \phi}{\partial x \partial y} = -\frac{\partial^2 (Cy^3)}{\partial x \partial y}=0 $$
  
  putting this value of $\sigma_x_x $ in the function 
  
$$ x_o = \[ \int_{-b}^{+b} \sigma_{xx} .y \,dy \] $$  

$$ x_o = \[ \int_{-b}^{+b} 6 Cy .y \,dy \] $$  

$$ x_o = \[ \int_{-b}^{+b} 6 Cy^2 \,dy \] $$ 

$$ x_o = 6.\frac{Cy^3}{3}|^b - b $$ 

$$ x_o = 2 Cy^3|^b - b $$  

$$ x_o = 2 C (b^3 + b^3) $$

$$ x_o = 4C b^3 $$
 
 $$x_o = 4C b^3 $$

 $$ c = \frac{x_o}{4b^3} $$

 put 
 
 $$ \sigma_{xx} = 6Cy $$

 $$ \sigma_{xx} = 6 \frac{x_o}{4b^3}. y $$

 $$ \sigma_{xx} = \frac{3}{2} \frac{x_o}{b^3} y $$

 and 
 
 $$ \phi = \frac{x_o y^3}{4b^3} $$ 
 
---

## Two dimensional Problem in Polar coordinate

(a) Plane Stress 

### (1) Equilibrium Equations 

   
$$ \frac{\partial \sigma_{r}}{\partial r} + \frac{1}{r} \frac{\partial \tau_{r \theta}}{\partial \theta}+ \frac{\sigma_{r}-\sigma{\theta}}{r}+B_r = 0 $$

$$ \frac{1}{r}\frac{\partial \sigma_{\theta}}{\partial \theta} +  \frac{\partial \tau_{r \theta}}{\partial r}+ \frac{2\tau_{r\theta}}{r}+B_\theta = 0 $$


### (2) Strain-displacement relations 

   
$$ \epsilon_r = \frac{\partial u_{r}}{\partial r} $$

$$ \epsilon_\theta = \frac{1}{r}\frac{\partial u_{\theta}}{\partial \theta} + \frac{u_r}{r},\epsilon_z =  \frac{\partial u_{z}}{\partial z} $$

$$ \gamma_{r\theta} = \frac{1}{r}\frac{\partial u_{r}}{\partial \theta} + \frac{\partial u_{\theta}}{\partial r} -\frac{u_\theta}{r} $$


### (3) Stress-strain relations 
   
   
$$ \epsilon_r = \frac{{1}}{ E} [\sigma_r-v\sigma_\theta] $$

$$ \epsilon_\theta = \frac{{1}}{ E} [\sigma_\theta-v\sigma_r] $$

$$ \epsilon_z = - \frac{{v}}{ E} [\sigma_r+\sigma_\theta] $$

$$ \gamma_{r\theta} = 2\frac{{(1+v)}}{ E} \tau_{r\theta} $$




### (4) Stress-displacement relations 


$$ \sigma_r = 2G \frac{\partial_u}{\partial_r}+\lambda[\frac{\partial u_r}{\partial_r}+\frac{1}{r}\frac{\partial u_\theta}{\partial\theta}+\frac{u_r}{r}+\frac{\partial u_z}{\partial_z} ] $$

$$ \sigma_\theta = 2G [\frac{1}{r}\frac{\partial u_\theta}{\partial_\theta}+\frac{u_r}{r}]+\lambda[\frac{\partial u_r}{\partial_r}+\frac{1}{r}\frac{\partial u_\theta}{\partial_\theta}+\frac{u_r}{r}+\frac{\partial u_z}{\partial_z} ] $$

$$ \tau_{r\theta} =G \gamma_{r\theta} = G [\frac{1}{r}\frac{\partial u_r}{\partial u_\theta}+\frac{\partial u_\theta}{\partial r}- \frac{u_\theta}{r}] $$




### (5) Strain-compatibility equation 


$$ \frac{1}{r^2}\frac{\partial(r\frac{\partial\gamma_{r\theta}}{\partial\theta})}{\partial r} = \frac{1}{r^2}\frac{\partial(r^2\frac{\partial\epsilon_\theta}{\partial r})}{\partial r} + (\frac{1}{r^2}\frac{\partial^2}{\partial \theta^2}-\frac{1}{r}\frac{\partial}{\partial r})\epsilon_r $$



### (6) Equilibrium Equations in terms of displacements 


$$ \nabla^2 u_r + (\frac{3}{(1-2v)} \frac{\partial\epsilon_m}{\partial_r}-\frac{u_r}{r^2}-\frac{2}{r^2}\frac{\partial u_\theta}{\partial\theta}+ \frac{B_r}{G}= 0 $$

$$ \nabla^2 u_\theta + (\frac{3}{(1-2v)} \frac{\partial\epsilon_m}{r\partial\theta}-\frac{u_\theta}{r^2}+\frac{2}{r^2}\frac{\partial u_r}{\partial\theta}+ \frac{B_\theta}{G}= 0 $$

where 

$$ \epsilon_m = \frac{1}{3}(\epsilon_r+\epsilon_\theta+ \epsilon_z) $$

$$ \nabla^2 = \frac{\partial^2}{\partial r^2}+ \frac{1}{r}\frac{\partial}{\partial r} + \frac{1}{r^2}\frac{\partial^2}{\partial \theta^2} $$



### (b) Plane Strain

### (1) Equilibrium Equations 

    
$$ \frac{\partial \sigma_{r}}{\partial r} + \frac{1}{r} \frac{\partial \tau_{r \theta}}{\partial \theta}+ \frac{\sigma_{r}-\sigma{\theta}}{r}+B_r = 0 $$ 

$$ \frac{1}{r}\frac{\partial \sigma_{\theta}}{\partial \theta} +  \frac{\partial \tau_{r \theta}}{\partial r}+ \frac{2\tau_{r\theta}}{r}+B_\theta = 0 $$ 

$$ \frac{\partial \sigma_z}{\partial z} = 0 $$



### (2) Strain-displacement relations 

    
$$ \epsilon_r = \frac{\partial u_{r}}{\partial r} $$ 

$$ \epsilon_\theta = \frac{1}{r}\frac{\partial u_{\theta}}{\partial \theta} + \frac{u_r}{r} $$ 

$$ \gamma_{r\theta} = \frac{1}{r}\frac{\partial u_{r}}{\partial \theta} + \frac{\partial u_{\theta}}{\partial r} -\frac{u_\theta}{r} $$ 



### (3) Stress-strain relations 


$$ \epsilon_z = \frac{{1}}{ E} [\sigma_z-v(\sigma_r+\sigma_\theta)] =0 $$ 

$$ \sigma_z = v(\sigma_r + \sigma_\theta) $$ 

$$ \epsilon_r = \frac{1+v}{E} [(1-v)\sigma_r-v\sigma_\theta] $$ 

$$ \epsilon_\theta = \frac{1+v}{E} [(1-v)\sigma_\theta-v\sigma_r] $$ 

$$ \gamma_{r\theta} = 2\frac{{(1+v)}}{ E} \tau_{r\theta} $$ 



### (4) Stress-displacement relations 


$$ \sigma_r = 2G \frac{\partial u_r}{\partial_r}+\lambda[\frac{\partial u_r}{\partial_r}+\frac{1}{r}\frac{\partial u_\theta}{\partial\theta}+\frac{u_r}{r}] $$ 

$$ \sigma_\theta = 2G [\frac{1}{r}\frac{\partial u_\theta}{\partial_r}+\frac{u_r}{r}]+\lambda[\frac{\partial u_r}{\partial_r}+\frac{1}{r}\frac{\partial u_\theta}{\partial_\theta}+\frac{u_r}{r}] $$ 

$$ \tau_{r\theta} = G [\frac{1}{r}\frac{\partial u_r}{\partial u_\theta}+\frac{\partial u_\theta}{\partial r}- \frac{u_\theta}{r}] $$ 




### (5) Strain-compatibility equation 


$$ \frac{1}{r^2}\frac{\partial(r\frac{\partial\gamma_{r\theta}}{\partial\theta})}{\partial r} = \frac{1}{r^2}\frac{\partial(r^2\frac{\partial\epsilon_\theta}{\partial r})}{\partial r} + (\frac{1}{r^2}\frac{\partial^2}{\partial \theta^2}-\frac{1}{r}\frac{\partial}{\partial r})\epsilon_r $$ 




### (6) Equilibrium Equations in terms of displacements 


$$ \nabla^2 u_r + (\frac{3}{(1-2v)} \frac{\partial\epsilon_m}{\partial_r}-\frac{u_r}{r^2}-\frac{2}{r^2}\frac{\partial u_\theta}{\partial\theta}+ \frac{B_r}{G}= 0 $$ 

$$ \nabla^2 u_\theta + (\frac{3}{(1-2v)} \frac{\partial\epsilon_m}{r\partial\theta}-\frac{u_\theta}{r^2}+\frac{2}{r^2}\frac{\partial u_r}{\partial\theta}+ \frac{B_\theta}{G}= 0 $$ 

where 

$$ \epsilon_m = \frac{1}{3}(\epsilon_r+\epsilon_\theta+ \epsilon_z) $$

$$ \nabla^2 = \frac{\partial^2}{\partial r^2}+ \frac{1}{r}\frac{\partial}{\partial r} + \frac{\partial^2}{\partial \theta^2} $$ 


