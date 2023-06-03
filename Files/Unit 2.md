
# Advanced Solid Mechanics

## Content 2

<section style="text-align: left;">
Topics

- Elementary Concept of Stress and Strain at a Point 
- Principal Axes
- Principal stresses and Strains
- Compatibility Conditions
- Stress Components on an Arbitrary Plane 
- Differential Equations of Equilibrium 

---

# Stress at a Point

<section style="text-align: justify;">

---
# Strain at a Point


<section style="text-align: justify;">


---
# Principal stresses and Strains

<section style="text-align: justify;">
  
## Principal stresses & Principal Axis

Let us assume that there is a plane n with direction cosines n<sub>x</sub>, n<sub>y</sub> and n<sub>z</sub> on which the stress is wholly normal. Let &sigma; be the magnitude of this stress vector.

</section style>
T<sup>n</sup> = &sigma; n

The components of this along the x, y and z axes are

T<sup>n</sup><sub>x</sub> = &sigma; n<sub>x</sub>

T<sup>n</sup><sub>y</sub> = &sigma; n<sub>y</sub>

T<sup>n</sup><sub>z</sub> = &sigma; n<sub>z</sub>  . . . . . (Eq. 1) 

  
From Cauchy's Equation 

T<sup>n</sup><sub>x</sub> = &sigma;<sub>x</sub> n<sub>x</sub> +  &tau;<sub>yx</sub>n<sub>y</sub> + &tau;<sub>zx</sub>n<sub>z</sub>

T<sup>n</sup><sub>y</sub> = &tau;<sub>xy</sub>n<sub>x</sub> + &sigma;<sub>y</sub> n<sub>y</sub> +  &tau;<sub>zy</sub>n<sub>z</sub>

T<sup>n</sup><sub>z</sub> = &tau;<sub>xz</sub>n<sub>x</sub> + &tau;<sub>yz</sub>n<sub>y</sub> + &sigma;<sub>z</sub> n<sub>z</sub>

Subtracting Eq (1) from above equations

T<sup>n</sup><sub>x</sub> = (&sigma;<sub>x</sub> - &sigma;)n<sub>x</sub> +  &tau;<sub>yx</sub>n<sub>y</sub> + &tau;<sub>zx</sub>n<sub>z</sub>

T<sup>n</sup><sub>y</sub> = &tau;<sub>xy</sub>n<sub>x</sub> + (&sigma;<sub>y</sub> - &sigma;) n<sub>y</sub> + &tau;<sub>zy</sub>n<sub>z</sub>

T<sup>n</sup><sub>z</sub> = &tau;<sub>xz</sub>n<sub>x</sub> + &tau;<sub>yz</sub>n<sub>y</sub> + (&sigma;<sub>z</sub> - &sigma;) n<sub>z</sub>   . . . . . (Eq 2)

The unknowns n<sub>x</sub>, n<sub>y</sub> and n<sub>z</sub> are direction cosines that define the plane on which the resultant stress is wholly normal. 

Equation last equations are a set of homogeneous equations. The trivial solution is 

n<sub>x</sub> = n<sub>y</sub> = n<sub>z</sub> = 0. 

For the existence of a non-trivial solution, the determinant of the coefficients of n<sub>x</sub>, n<sub>y</sub>, n<sub>z</sub> must be equal to zero, i.e.

![s](https://github.com/MnprtBains/Extras/blob/main/1112121.PNG?raw=true)

&sigma;<sup>3</sup> - (&sigma;<sub>x</sub> + &sigma;<sub>y</sub> + &sigma;<sub>z</sub>)&sigma;<sup>2</sup> + (&sigma;<sub>x</sub> &sigma;<sub>y</sub> + &sigma;<sub>y</sub> &sigma;<sub>z</sub> + &sigma;<sub>z</sub> &sigma;<sub>x</sub> - &tau;<sup>2</sup><sub>xy</sub> - &tau;<sup>2</sup><sub>yz</sub> - &tau;<sup>2</sup><sub>zx</sub>)&sigma; - (&sigma;<sub>x</sub> &sigma;<sub>y</sub> &sigma;<sub>z</sub> + 2 &tau;<sub>xy</sub> &tau;<sub>yz</sub> &tau;<sub>zx</sub> - &sigma;<sub>x</sub> &tau;<sup>2</sup><sub>yz</sub> - &sigma;<sub>y</sub> &tau;<sup>2</sup><sub>xz</sub> - &sigma;<sub>x</sub> &tau;<sup>2</sup><sub>xy</sub>) = 0

The three roots of the cubic equation can be designated as &sigma;<sub>1</sub>, &sigma;<sub>2</sub> and &sigma;<sub>3</sub>.

Substituting these three solutions in Eqs (Eq. 2), values n<sub>x</sub>, n<sub>y</sub> and n<sub>z</sub> can be known.  In order to avoid the trivial solution, the condition is used. 

With each &sigma; there will be an associated plane. These planes on each of which the stress vector is wholly normal are called the principal planes and the corresponding stresses are called the <u>principal stresses.</u> The normal to a principal plane is called the <u>principal stress axis</u>.

---
<section style="text-align: justify;">
  
## Principal Strains

E<sub>xx</sub> = &part;u<sub>x</sub>/&part;x + &frac12; [ (&part;u<sub>x</sub>/&part;x)<sup>2</sup> + (&part;u<sub>y</sub>/&part;x)<sup>2</sup> + (&part;u<sub>z</sub>/&part;x)<sup>2</sup> ]

E<sub>yy</sub> = &part;u<sub>y</sub>/&part;y + &frac12; [ (&part;u<sub>x</sub>/&part;y)<sup>2</sup> + (&part;u<sub>y</sub>/&part;y)<sup>2</sup> + (&part;u<sub>z</sub>/&part;y)<sup>2</sup> ]

E<sub>zz</sub> = &part;u<sub>z</sub>/&part;z + &frac12; [ (&part;u<sub>x</sub>/&part;z)<sup>2</sup> + (&part;u<sub>y</sub>/&part;z)<sup>2</sup> + (&part;u<sub>z</sub> / &part;z)<sup>2</sup> ]

E<sub>xy</sub> = &part;u<sub>x</sub>/&part;y + &part;u<sub>y</sub>/&part;x + (&part;u<sub>x</sub>/&part;x)(&part;u<sub>x</sub>/&part;y) + (&part;u<sub>y</sub>/&part;x)(&part;u<sub>y</sub>/&part;y) + (&part;u<sub>z</sub>/&part;x)(&part;u<sub>z</sub>/&part;y)

E<sub>yz</sub> = &part;u<sub>y</sub>/&part;z + &part;u<sub>z</sub>/&part;y + (&part;u<sub>x</sub>/&part;y)(&part;u<sub>x</sub>/&part;z) + (&part;u<sub>y</sub>/&part;y)(&part;u<sub>y</sub>/&part;z) + (&part;u<sub>z</sub>/&part;y)(&part;u<sub>z</sub>/&part;z)

E<sub>xz</sub> = &part;u<sub>x</sub>/&part;z + &part;u<sub>z</sub>/&part;x + (&part;u<sub>x</sub>/&part;x)(&part;u<sub>x</sub>/&part;z) + (&part;u<sub>y</sub>/&part;x)(&part;u<sub>y</sub>/&part;z) + (&part;u<sub>z</sub>/&part;x)(&part;u<sub>z</sub>/&part;z)


  If the deformation imposed on the body is small, the quantities like ∂u<sub>x</sub>/∂x, ∂u<sub>x</sub>/∂y, etc. are extremely small so that their squares and products can be neglected. Retaining only linear terms, the following equations are obtained.

&epsilon;<sub>xx</sub> = &part;u<sub>x</sub>/&part;x

&epsilon;<sub>yy</sub> = &part;u<sub>y</sub>/&part;y

&epsilon;<sub>zz</sub> = &part;u<sub>z</sub>/&part;z

&gamma;<sub>xy</sub> = &part;u<sub>x</sub>/&part;y + &part;u<sub>y</sub>/&part;x

&gamma;<sub>yz</sub> = &part;u<sub>y</sub>/&part;z + &part;u<sub>z</sub>/&part;y

&gamma;<sub>xy</sub> = &part;u<sub>x</sub>/&part;z + &part;u<sub>z</sub>/&part;x

E<sub>PQ</sub> = &epsilon;<sub>PQ</sub> = &epsilon;<sub>xx</sub>
n<sup>2</sup><sub>x</sub> + &epsilon;<sub>yy</sub>
n<sup>2</sup><sub>y</sub> + &epsilon;<sub>zz</sub>
n<sup>2</sup><sub>z</sub> + &epsilon;<sub>xy</sub>n<sub>x</sub>n<sub>y</sub> + &epsilon;<sub>yz</sub>n<sub>y</sub>n<sub>z</sub> + &epsilon;<sub>xz</sub>n<sub>x</sub>n<sub>z</sub>  . . . . .(Eq. 4)

<br>
n<sup>2</sup><sub>x</sub> + n<sup>2</sup><sub>y</sub> + n<sup>2</sup><sub>z</sub> = 1

Taking n<sub>x</sub> and n<sub>y</sub> as independent and differentiating Eq. (4) with respect to n<sub>x</sub> and n<sub>y</sub> we get, 

2n<sub>x</sub> + 2n<sub>z</sub>(&part;n<sub>z</sub>/&part;n<sub>x</sub>) = 0

2n<sub>y</sub> + 2n<sub>z</sub>(&part;n<sub>z</sub>/&part;n<sub>y</sub>) = 0  . . . . . (Eq. 5)

Differentiating eq. (4) with respect to n<sub>x</sub> and n<sub>y</sub> and then equating them to zero.

0 = 2&epsilon;<sub>xx</sub>
n<sub>x</sub> + &gamma;<sub>xy</sub>
n<sub>y</sub> + &gamma;<sub>zx</sub> n<sub>z</sub> + (&part;n<sub>z</sub>/&part;n<sub>x</sub>)(n<sub>x</sub>&gamma;<sub>zx</sub> +  n<sub>y</sub>&gamma;<sub>zy</sub> + 2 n<sub>z</sub>&gamma;<sub>zx</sub>) 

0 = 2&epsilon;<sub>yy</sub>
n<sub>y</sub> + &gamma;<sub>xy</sub>
n<sub>x</sub> + &gamma;<sub>yz</sub> n<sub>z</sub> + (&part;n<sub>z</sub>/&part;n<sub>y</sub>)(n<sub>x</sub>&gamma;<sub>zx</sub> +  n<sub>y</sub>&gamma;<sub>zy</sub> + 2 n<sub>z</sub>&gamma;<sub>zx</sub>) 

<br>
Substituting for ∂n<sub>z</sub>/∂n<sub>x</sub> and ∂n<sub>z</sub>/∂n<sub>y</sub> from eq. (5)

(2&epsilon;<sub>xx</sub>
n<sub>x</sub> + &gamma;<sub>xy</sub>
n<sub>y</sub> + &gamma;<sub>zx</sub> n<sub>z</sub>) / n<sub>x</sub> = (n<sub>x</sub>&gamma;<sub>zx</sub> +  n<sub>y</sub>&gamma;<sub>zy</sub> + 2 n<sub>z</sub>&gamma;<sub>zx</sub>) / n<sub>z</sub> 

(2&epsilon;<sub>yy</sub>
n<sub>y</sub> + &gamma;<sub>xy</sub>
n<sub>x</sub> + &gamma;<sub>yz</sub> n<sub>z</sub>) / n<sub>x</sub> =  (n<sub>x</sub>&gamma;<sub>zx</sub> +  n<sub>y</sub>&gamma;<sub>zy</sub> + 2 n<sub>z</sub>&gamma;<sub>zx</sub>) / n<sub>z</sub> 

<br>
Denoting right hand side of the above equations by 2&epsilon; and rearranging.

2&epsilon;<sub>xx</sub>
n<sub>x</sub> + &gamma;<sub>xy</sub>
n<sub>y</sub> + &gamma;<sub>yz</sub> n<sub>z</sub> - 2&epsilon;n<sub>x</sub> = 0 

&gamma;<sub>xy</sub>
n<sub>x</sub> + 2&epsilon;<sub>yy</sub>
n<sub>y</sub>  + &gamma;<sub>yz</sub> n<sub>z</sub> - 2&epsilon;n<sub>y</sub> = 0 

&gamma;<sub>zx</sub>
n<sub>x</sub> + &gamma;<sub>zy</sub> n<sub>y</sub> + 2&epsilon;<sub>zz</sub>
n<sub>z</sub> - 2&epsilon;n<sub>z</sub> = 0  . . . . .. (Eq. 6)

Multiplying the first equation of eq. (6) by n<sub>x</sub>, first equation by n<sub>y</sub> and third equation by n<sub>z</sub> and adding them all.

2&epsilon;<sub>xx</sub>n<sup>2</sup><sub>x</sub> + 2&epsilon;<sub>yy</sub>
n<sup>2</sup><sub>y</sub> + 2&epsilon;n<sup>2</sup><sub>z</sub> + 2&epsilon;<sub>zz</sub>
n<sub>z</sub> + &gamma;<sub>xy</sub> n<sub>x</sub> n<sub>y</sub> + &gamma;<sub>yz</sub> n<sub>y</sub> n<sub>z</sub> + &gamma;<sub>zx</sub> n<sub>z</sub>
n<sub>x</sub> = 2 &epsilon; (n<sup>2</sup><sub>x</sub> + n<sup>2</sup><sub>y</sub> + n<sup>2</sup><sub>z</sub>)

If we impose condition n<sup>2</sup><sub>x</sub> + n<sup>2</sup><sub>y</sub> + n<sup>2</sup><sub>z</sub> = 1

The eq. (6) can be represented as:

(&epsilon;<sub>xx</sub> - &epsilon;)
n<sub>x</sub> + &frac12; &gamma;<sub>xy</sub>
n<sub>y</sub> + &frac12; &gamma;<sub>xz</sub> n<sub>z</sub> = 0

&frac12; &gamma;<sub>yx</sub>
n<sub>y</sub> + (&epsilon;<sub>yy</sub> - &epsilon;)
n<sub>x</sub> + &frac12; &gamma;<sub>yz</sub> n<sub>z</sub> = 0

&frac12; &gamma;<sub>zx</sub>
n<sub>y</sub> + &frac12; &gamma;<sub>zy</sub> n<sub>y</sub> + (&epsilon;<sub>zz</sub> - &epsilon;)
n<sub>z</sub> = 0 . . . . . . (Eq. 7)

Putting 

&frac12; &gamma;<sub>xy</sub> = e<sub>xy</sub>

&frac12; &gamma;<sub>yz</sub> = e<sub>yz</sub>

&frac12; &gamma;<sub>zx</sub> = e<sub>zx</sub>

Now eq. (7) can be written as:

(&epsilon;<sub>xx</sub> - &epsilon;)
n<sub>x</sub> +  e<sub>xy</sub>
n<sub>y</sub> + e<sub>xz</sub> n<sub>z</sub> = 0

e<sub>yx</sub>
n<sub>y</sub> + (&epsilon;<sub>yy</sub> - &epsilon;)
n<sub>x</sub> + e<sub>yz</sub> n<sub>z</sub> = 0

e<sub>zx</sub>
n<sub>y</sub> + e<sub>zy</sub> n<sub>y</sub> + (&epsilon;<sub>zz</sub> - &epsilon;)
n<sub>z</sub> = 0

The above set of equations is homogeneous in n<sub>x</sub>, n<sub>y</sub>, n<sub>z</sub>. For the existence of
a non-trivial solution, the determinant of its coefficient must be equal to zero, i.e.

![](https://github.com/MnprtBains/Extras/blob/main/HHAG.PNG?raw=true)

Expanding the determinant, we get

&epsilon;<sup>3</sup> – J<sub>1</sub> &epsilon;<sup>2</sup> + J<sub>2</sub> &epsilon; – J<sub>3</sub> = 0

Where, 

J<sub>1</sub> = &epsilon;<sub>xx</sub> + &epsilon;<sub>yy</sub> + &epsilon;<sub>zz</sub>

![](https://github.com/MnprtBains/Extras/blob/main/J2.PNG?raw=true)

![](https://github.com/MnprtBains/Extras/blob/main/j3.PNG?raw=true)

For a given state of strain at point P, if the relative extension (i.e. strain) &epsilon; is extremum in a direction ;n', then ) &epsilon; is the <u>principal strain</u> at P and n is the principal
strain direction associated with e

---
## Stress Components on an Arbitrary Plane 
  
  <img src="https://github.com/MnprtBains/Extras/blob/main/WhatsApp%20Image%202023-03-28%20at%2011.58.23%20PM.jpeg?raw=true " alt="Your image title" width="600"/> 
  
  
<section style="text-align: justify;">

- Let the three mutually perpendicular planes be the x, y and z planes and let the arbitrary plane be identified by its outward drawn normal 'n' whose direction cosines are n<sub>x</sub>, n<sub>y</sub> and n<sub>z</sub>.

- Consider a small tetrahedron at P with three of its faces normal to the coordinate axes, and the inclined face having its normal parallel to 'n'. 
- Let 'h' be the perpendicular distance from P to the inclined face. 
- If the tetrahedron is isolated from the body and a free-body diagram is drawn, then it will be in equilibrium under the action of the surface forces and the body forces. 
- Since the size of the tetrahedron considered is very small and in the limit as we are going to make 'h' tend to zero, we shall talk in terms of the average stresses over the faces.
- Let T<sup>n </sup> be the resultant stress vector on face ABC. This can be resolved into components T<sup>n</sup><sub>x</sub>, 
  T<sup>n</sup><sub>y</sub>, T<sup>n</sup><sub>z</sub> parallel to the three axes x, y and z. 
- On the three faces, the rectangular stress components are &sigma;<sub>x</sub>, &tau;<sub>xy</sub>, &tau;<sub>xz</sub>, &sigma;<sub>y</sub>, &tau;<sub>yz</sub>, &tau;<sub>yx</sub>, &sigma;<sub>z</sub>, &tau;<sub>xz</sub>, &tau;<sub>zy</sub>.

If A is the area of the inclined face then,

<br> 
Area of BPC = projection of area ABC on the yz plane

 = An

Area of CPA = projection of area ABC on the xz plane

= An<sub>y</sub>

Area of APB = projection of area ABC on the xy plane

= An<sub>z</sub>

Let the body force components in x, y and z directions be &gamma;<sub>x</sub>, &gamma;<sub>y</sub>, &gamma;<sub>z</sub> respectively, per unit volume. The volume of the tetrahedron is equal to &frac13; Ah where 'h' is the perpendicular distance from 'P' to the inclined face. For equilibrium of the tetrahedron, the sum of the forces in x, y and z directions must individually vanish. 

<u>Thus, for equilibrium in x direction</u>

<br>
T<sup>n</sup><sub>x</sub> A - &sigma;<sub>x</sub> An<sub>x</sub> -  &tau;<sub>yx</sub>An<sub>y</sub> - &tau;<sub>zx</sub>An<sub>z</sub> + &frac13; Ah&gamma;<sub>x</sub> = 0

Cancelling A,

T<sup>n</sup><sub>x</sub> = &sigma;<sub>x</sub> n<sub>x</sub> +  &tau;<sub>yx</sub>n<sub>y</sub> + &tau;<sub>zx</sub>n<sub>z</sub> - &frac13; h&gamma;<sub>x</sub>

<u>For equilibrium in y direction</u>

T<sup>n</sup><sub>y</sub> A - &tau;<sub>xy</sub>An<sub>x</sub> - &sigma;<sub>y</sub> An<sub>y</sub> -  &tau;<sub>zy</sub>An<sub>z</sub> + &frac13; Ah&gamma;<sub>y</sub> = 0

Cancelling A,

T<sup>n</sup><sub>y</sub> = &tau;<sub>xy</sub>n<sub>x</sub> + &sigma;<sub>y</sub> n<sub>y</sub> +  &tau;<sub>zy</sub>n<sub>z</sub> - &frac13; h&gamma;<sub>y</sub>

<br>

<u>For equilibrium in z direction</u>

T<sup>n</sup><sub>z</sub> A - &tau;<sub>xz</sub>An<sub>x</sub> -
&tau;<sub>yz</sub>An<sub>y</sub> - 
&sigma;<sub>z</sub> An<sub>z</sub> +   &frac13; Ah&gamma;<sub>z</sub> = 0

Cancelling A,

T<sup>n</sup><sub>z</sub> = &tau;<sub>xz</sub>n<sub>x</sub> + &tau;<sub>yz</sub>n<sub>y</sub> + &sigma;<sub>z</sub> n<sub>z</sub> - &frac13; h&gamma;<sub>z</sub>

In the limit as h tends to zero, the equation becomes,

T<sup>n</sup><sub>x</sub> = &sigma;<sub>x</sub> n<sub>x</sub> +  &tau;<sub>yx</sub>n<sub>y</sub> + &tau;<sub>zx</sub>n<sub>z</sub>

T<sup>n</sup><sub>y</sub> = &tau;<sub>xy</sub>n<sub>x</sub> + &sigma;<sub>y</sub> n<sub>y</sub> +  &tau;<sub>zy</sub>n<sub>z</sub>

T<sup>n</sup><sub>z</sub> = &tau;<sub>xz</sub>n<sub>x</sub> + &tau;<sub>yz</sub>n<sub>y</sub> + &sigma;<sub>z</sub> n<sub>z</sub>   . . . . (3)

<br>
This is known as Cauchy’s stress formula.

If T<sup>n</sup> is the resultant stress vector on plane ABC, we have

|T<sup>n</sup>|<sup>2</sup> = T<sup>n</sup><sup>2</sup><sub>x</sub> + T<sup>n</sup><sup>2</sup><sub>y</sub> + T<sup>n</sup><sup>2</sup><sub>z</sub> 

<br>
If &sigma;<sub>n</sub> and &tau;<sub>n</sub> are the normal and shear stress components,

|T<sup>n</sup>|<sup>2</sup> = &sigma;<sub>n</sub><sup>2</sup> + &tau;<sub>n</sub><sup>2</sup>

Since the normal stress is equal to the projection of T<sup>n</sup> along the normal, it is
also equal to the sum of the projections of its components n
T<sup>n</sup><sub>x</sub>, T<sup>n</sup><sub>y</sub>, T<sup>n</sup><sub>z</sub> along 'n'.

&sigma;<sub>n</sub> = n<sub>x</sub> T<sup>n</sup><sub>x</sub> + n<sub>y</sub> T<sup>n</sup><sub>y</sub> + n<sub>z</sub> T<sup>n</sup><sub>z</sub>

Substituting for T<sup>n</sup><sub>x</sub>,  T<sup>n</sup><sub>y</sub>,  T<sup>n</sup><sub>z</sub> from Eq. (3)

&sigma;<sub>n</sub> = n<sup>2</sup><sub>x</sub> &sigma;<sub>x</sub> + n<sup>2</sup><sub>y</sub> &sigma;<sub>y</sub> + n<sup>2</sup><sub>z</sub> &sigma;<sub>z</sub> + 2 n<sub>x</sub> n<sub>y</sub> &tau;<sub>xy</sub> + 2 n<sub>y</sub> n<sub>z</sub> &tau;<sub>yz</sub> + 2 n<sub>z</sub> n<sub>x</sub> &tau;<sub>zx</sub> 

---
# DIFFERENTIAL EQUATIONS OF EQUILIBRIUM

 So far, attention has been focussed on the state of stress at a point.
 
 But the
state of stress in a body varies from point to point.

The important sets of equations used in the analysis of body to determine the state of the stress at every point or at any desired point in a body

(when stress vary from point to point)

(&part; &sigma;<sub>x</sub> /&part;x)  + (&part; &tau; <sub>xy</sub> /&part;y) + (&part;&tau;<sub>zx</sub> /&part;z) + &gamma;<sub>x</sub>=0

(&part; &sigma;<sub>y</sub> /&part;x)  + (&part; &tau; <sub>xy</sub> /&part;x) + (&part;&tau;<sub>yz</sub> /&part;z) + &gamma;<sub>y</sub>=0

(&part; &sigma;<sub>z</sub> /&part;z)  + (&part; &tau; <sub>xz</sub> /&part;x) + (&part;&tau;<sub>yz</sub> /&part;y) + &gamma;<sub>z</sub>=0
  
## derivation

Consider a small rectangular element with sides &#916;x, &#916;y
and &#916;z isolated from its parent body. 

Since in the limit, we
are going to make &#916;x, &#916;y and &#916;z
tend to zero, we shall deal with
average values of the stress
components on each face.


<img src="https://github.com/MnprtBains/Extras/blob/main/vvg.jpeg?raw=true " alt="Your image title" width="400"/> 
<img src="https://github.com/MnprtBains/Extras/blob/main/ygy.jpeg?raw=true " alt="Your image title" width="450"/>
  
<img src="https://github.com/MnprtBains/Extras/blob/main/WhatsApp%20Image%202023-03-28%20at%2011.55.15%20PM.jpeg?raw=true " alt="Your image title" width="400"/>

 Fig. Variation of stresses
 
The faces are marked as 1, 2, 3 etc. 

On the left hand face, i.e. face No. 1, the average stress components are &sigma;<sub>x</sub>, &tau;<sub>xy</sub> and &tau;<sub>xz</sub>.

On the right hand face i.e, face No.2, the average stress components are -

&sigma;<sub>x</sub>+ (&part;&sigma;<sub>x</sub>/&part;x)&#916;x  ,  &tau;<sub>xy</sub>+ (&part;&tau;<sub>xy</sub>/&part;x)&#916;x , &tau;<sub>xz</sub>+ (&part;&tau;<sub>xz</sub>/&part;x)&#916;x 

This is because the right hand face is Dx distance away from the left hand face.

Following a similar procedure, the stress components on the six faces of the element are as follows:


Face 1 -  &sigma;<sub>x</sub>, &tau;<sub>xy</sub> , &tau;<sub>xz</sub> 

Face 2 -  &sigma;<sub>x</sub>+ (&part;&sigma;<sub>x</sub>/&part;x)&#916;x  ,  &tau;<sub>xy</sub>+ (&part;&tau;<sub>xy</sub>/&part;x)&#916;x , &tau;<sub>xz</sub>+ (&part;&tau;<sub>xz</sub>/&part;x)&#916;x 

Face 3 -  &sigma;<sub>y</sub>, &tau;<sub>yx</sub> , &tau;<sub>yz</sub>

Face 4 -  &sigma;<sub>y</sub>+ (&part;&sigma;<sub>y</sub>/&part;y)&#916;y  ,  &tau;<sub>yx</sub>+ (&part;&tau;<sub>yx</sub>/&part;y)&#916;y , &tau;<sub>yz</sub>+ (&part;&tau;<sub>yz</sub>/&part;y)&#916;y 

Face 5 -  &sigma;<sub>z</sub>, &tau;<sub>zx</sub> , &tau;<sub>zy</sub> 

Face 6 -  &sigma;<sub>z</sub>+ (&part;&sigma;<sub>z</sub>/&part;z)&#916;z  ,  &tau;<sub>zx</sub>+ (&part;&tau;<sub>zx</sub>/&part;z)&#916;z , &tau;<sub>zy</sub>+ (&part;&tau;<sub>zy</sub>/&part;z)&#916;z 

Let the body force components per unit volume in the x, y and z directions be &gamma;<sub>x</sub>, &gamma;<sub>y</sub>, and &gamma;<sub>z</sub>. 

For equilibrium in x direction

(&sigma;<sub>x</sub>+ (&part;&sigma;<sub>x</sub>/&part;x)&#916;x)&#916;y &#916;z - &sigma;<sub>x</sub>&#916;y &#916;z + (&tau;<sub>yx</sub>+ (&part;&tau;<sub>yx</sub>/&part;y)&#916;y)&#916;z &#916;x - &tau;<sub>yx</sub>&#916;z &#916;x + (&tau;<sub>zx</sub>+ (&part;&tau;<sub>zx</sub>/&part;z)&#916;z)&#916;x &#916;y - &tau;<sub>zx</sub>&#916;x &#916;y + &gamma;<sub>x</sub>&#916;x &#916;y&#916;z = 0 

Cancelling terms and dividing by &#916;x &#916;y&#916;z  , we get

(&part; &sigma;<sub>x</sub> /&part;x)  + (&part; &tau; <sub>xy</sub> /&part;y) + (&part;&tau;<sub>zx</sub> /&part;z) + &gamma;<sub>x</sub>=0
 
 Similarly,
 
 
(&part; &sigma;<sub>y</sub> /&part;x)  + (&part; &tau; <sub>xy</sub> /&part;x) + (&part;&tau;<sub>yz</sub> /&part;z) + &gamma;<sub>y</sub>=0

(&part; &sigma;<sub>z</sub> /&part;z)  + (&part; &tau; <sub>xz</sub> /&part;x) + (&part;&tau;<sub>yz</sub> /&part;y) + &gamma;<sub>z</sub>=0

we obtain the three differential equations of equilbirium as  

(&part; &sigma;<sub>x</sub> /&part;x)  + (&part; &tau; <sub>xy</sub> /&part;y) + (&part;&tau;<sub>zx</sub> /&part;z) + &gamma;<sub>x</sub>=0

(&part; &sigma;<sub>y</sub> /&part;x)  + (&part; &tau; <sub>xy</sub> /&part;x) + (&part;&tau;<sub>yz</sub> /&part;z) + &gamma;<sub>y</sub>=0

(&part; &sigma;<sub>z</sub> /&part;z)  + (&part; &tau; <sub>xz</sub> /&part;x) + (&part;&tau;<sub>yz</sub> /&part;y) + &gamma;<sub>z</sub>=0

---
# Compatibility conditions

It was observed that the displacement of a point in a solid body can be represented by a displacement vector u, which has components,

u<sub>x</sub>, u<sub>y</sub>, u<sub>z</sub>

along the three axes x, y and z respectively. The deformation at a point is specified by the six strain components,

&epsilon;<sub>xx</sub>, &epsilon;<sub>yy</sub>, &epsilon;<sub>zz</sub>, &epsilon;<sub>xx</sub>, &epsilon;<sub>yz</sub>,  &epsilon;<sub>zx</sub> 

The three displacement components and the six rectangular strain components are related by the six strain displacement relations of Cauchy, given by

&epsilon;<sub>xx</sub> = (&part;u<sub>x</sub>/&part;x),  &epsilon;<sub>yy</sub> = (&part;u<sub>y</sub>/&part;y), &epsilon;<sub>zz</sub> = (&part;u<sub>z</sub>/&part;z)

&gamma;<sub>xy</sub> = (&part;u<sub>x</sub>/&part;y) + (&part;u<sub>y</sub>/&part;x),

&gamma;<sub>yz</sub> = (&part;u<sub>y</sub>/&part;z) + (&part;u<sub>z</sub>/&part;y),

&gamma;<sub>xz</sub> = (&part;u<sub>x</sub>/&part;z) + (&part;u<sub>z</sub>/&part;x) 

The determination of the six strain components from the three displacement functions is straightforward since it involves only differentiation. 

However, the reverse operation, i.e. determination of the three displacement functions from the six strain components is more complicated since it involves integrating six equations to obtain three functions. 

The total number of these relations are six and they fall into two groups.
  
### first group
&epsilon;<sub>xx</sub> = (&part;u<sub>x</sub>/&part;x),

&epsilon;<sub>yy</sub> = (&part;u<sub>y</sub>/&part;y)

&gamma;<sub>xy</sub> = (&part;u<sub>x</sub>/&part;y) + (&part;u<sub>y</sub>/&part;x),

Differentiate the first two of the above equations as follows:

(&part;<sup>2</sup>&epsilon;<sub>xx</sub>/ &part;y<sup>2</sup>) = (&part;<sup>3</sup>u<sub>x</sub>/&part;x&part;y<sup>2</sup>) = (&part;<sup>2</sup>/&part;x&part;y)(&part;u<sub>x</sub>/&part;y)

(&part;<sup>2</sup>&epsilon;<sub>yy</sub>/ &part;x<sup>2</sup>) = (&part;<sup>3</sup>u<sub>y</sub>/&part;y&part;x<sup>2</sup>) = (&part;<sup>2</sup>/&part;x&part;y)(&part;u<sub>y</sub>/&part;x)

Adding these two, we get 

(&part;<sup>2</sup>/&part;x&part;y)((&part;u<sub>x</sub>/&part;y) + (&part;u<sub>y</sub>/&part;x)) = (&part;<sup>2</sup>&gamma;<sub>xy</sub>/&part;x&part;y)

i.e ,

(&part;<sup>2</sup>&epsilon;<sub>xx</sub>/&part;y<sup>2</sup>) +  (&part;<sup>2</sup>&epsilon;<sub>yy</sub>/&part;x<sup>2</sup>) = (&part;<sup>2</sup>&gamma;<sub>xy</sub>/&part;x&part;y)


Similarly, by considering &epsilon;<sub>yy</sub>, &epsilon;<sub>zz</sub> and &gamma;<sub>yy</sub>, and &epsilon;<sub>zz</sub>, &epsilon;<sub>xx</sub> and &gamma;<sub>zx</sub>, we get two more
conditions. 

This leads us to the first group of conditions.

(&part;<sup>2</sup>&epsilon;<sub>xx</sub>/&part;y<sup>2</sup>) +  (&part;<sup>2</sup>&epsilon;<sub>yy</sub>/&part;x<sup>2</sup>) = (&part;<sup>2</sup>&gamma;<sub>xy</sub>/&part;x&part;y)

(&part;<sup>2</sup>&epsilon;<sub>yy</sub>/&part;z<sup>2</sup>) +  (&part;<sup>2</sup>&epsilon;<sub>zz</sub>/&part;y<sup>2</sup>) = (&part;<sup>2</sup>&gamma;<sub>yz</sub>/&part;y&part;z)

(&part;<sup>2</sup>&epsilon;<sub>zz</sub>/&part;x<sup>2</sup>) +  (&part;<sup>2</sup>&epsilon;<sub>xx</sub>/&part;z<sup>2</sup>) = (&part;<sup>2</sup>&gamma;<sub>zx</sub>/&part;z&part;x)


### Second group:

This group establishes the conditions among the shear strains

&gamma;<sub>xy</sub> = (&part;u<sub>x</sub>/&part;y) + (&part;u<sub>y</sub>/&part;x),

&gamma;<sub>yz</sub> = (&part;u<sub>y</sub>/&part;z) + (&part;u<sub>z</sub>/&part;y),

&gamma;<sub>xz</sub> = (&part;u<sub>x</sub>/&part;z) + (&part;u<sub>z</sub>/&part;x) 


Differentiating 

(&part;&gamma;<sub>xy</sub> / &part;z)= (&part;<sup>2</sup>u<sub>x</sub>/&part;z &part;y) + (&part;<sup>2</sup>u<sub>y</sub>/&part;z &part;x),

(&part;&gamma;<sub>yz</sub> / &part;x)= (&part;<sup>2</sup>u<sub>y</sub>/&part;x &part;z) + (&part;<sup>2</sup>u<sub>z</sub>/&part;x &part;y)

(&part;&gamma;<sub>zx</sub> / &part;y)= (&part;<sup>2</sup>u<sub>z</sub>/&part;x &part;y) + (&part;<sup>2</sup>u<sub>x</sub>/&part;y &part;z)

Adding the last two equations and subtracting the first

(&part;&gamma;<sub>yz</sub> / &part;x) + 
(&part;&gamma;<sub>zx</sub> / &part;y) - (&part;&gamma;<sub>xy</sub> / &part;z) =  2 (&part;<sup>2</sup>u<sub>z</sub>/&part;x &part;y)

Differentiating the above equation once more with respect to  z and observing that 

(&part;<sup>2</sup>u<sub>z</sub>/&part;x &part;y &part;z) = (&part;<sup>2</sup>&epsilon;<sub>zz</sub>/&part;x &part;y)

we get , 

(&part;/&part;z)((&part;&gamma;<sub>yz</sub> / &part;x) + 
(&part;&gamma;<sub>zx</sub> / &part;y) - (&part;&gamma;<sub>xy</sub> / &part;z)) =  2 (&part;<sup>3</sup>u<sub>z</sub>/&part;x &part;y &part;z) = 2(&part;<sup>2</sup>&epsilon;<sub>zz</sub>/&part;x &part;y)

This is one of the required relations of the second group. By a cyclic change of
the letters we get the other two equations.

Collecting all equations, the six strain compatibility relations are


(&part;<sup>2</sup>&epsilon;<sub>xx</sub>/&part;y<sup>2</sup>) +  (&part;<sup>2</sup>&epsilon;<sub>yy</sub>/&part;x<sup>2</sup>) = (&part;<sup>2</sup>&gamma;<sub>xy</sub>/&part;x&part;y)


(&part;<sup>2</sup>&epsilon;<sub>yy</sub>/&part;z<sup>2</sup>) +  (&part;<sup>2</sup>&epsilon;<sub>zz</sub>/&part;y<sup>2</sup>) = (&part;<sup>2</sup>&gamma;<sub>yz</sub>/&part;y&part;z)


(&part;<sup>2</sup>&epsilon;<sub>zz</sub>/&part;x<sup>2</sup>) +  (&part;<sup>2</sup>&epsilon;<sub>xx</sub>/&part;z<sup>2</sup>) = (&part;<sup>2</sup>&gamma;<sub>zx</sub>/&part;z&part;x)


(&part;/&part;z)((&part;&gamma;<sub>yz</sub> / &part;x) + 
(&part;&gamma;<sub>zx</sub> / &part;y) - (&part;&gamma;<sub>xy</sub> / &part;z)) =  2(&part;<sup>2</sup>&epsilon;<sub>zz</sub>/&part;x &part;y)

(&part;/&part;x)((&part;&gamma;<sub>zx</sub> / &part;y) + (&part;&gamma;<sub>xy</sub> / &part;z) - (&part;&gamma;<sub>yz</sub> / &part;x)) =  2(&part;<sup>2</sup>&epsilon;<sub>xx</sub>/&part;y &part;z)

(&part;/&part;y)((&part;&gamma;<sub>xy</sub> / &part;z) + (&part;&gamma;<sub>yz</sub> / &part;x) - (&part;&gamma;<sub>zx</sub> / &part;y)) =  2(&part;<sup>2</sup>&epsilon;<sub>yy</sub>/&part;x &part;z)

The above six equations are called Saint-Venant’s equations of compatibility
