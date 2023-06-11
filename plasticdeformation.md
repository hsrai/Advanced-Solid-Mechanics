# Plastic Deformation

## Index
1. Strain Hardening
2. Idealized Stress- Strain curve
3. Yield Criteria
4. Von-Mises Yield Criterion 
5. Tresca Yield Criterion
6. Plastic Stress- Strain Relations
7. Principle of Normality and plastic Potential
8. Isotropic hardening

## Plastic Deformation
Plastic deformation is defined as a process in which the object due to applied force changes its size or shape in a way that is not reversible. Plastic deformation is seen in many objects, including:
1. Plastics
2. Metals
3. Soils
4. Rocks
5. Concrete

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/d1f141b2-4eef-424c-84d6-98a882e205b0)
## Strain Hardeninig
Strain hardening (also called work-hardening or cold-working) is the process of making a metal harder and stronger through plastic deformation.
In the plastic region, the true stress increases continuously i.e when a metal is strained beyond the yield point, more and more stress is required to produce additional plastic deformation and the metal is becoming stronger as the strain increases. Hence, it is called "Strain Hardening".

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/e27a8e19-d727-4fbb-91e8-ad00efa33773)

The plastic portion of the true stress-strain (or flow stress curve) plotted on a log-log scale gives the n value as the slope and the K value as the value of true stress at true strain of one.
 
 log($\phi$) = log(K) + n x log(e)
 
 For materials following the power law, the true strain at the Ultimate Tensile Strength is equal to n. When you plot the log-log plot, use data points after the yield point (to avoid elastic points) and before instability (necking).
 
 A material that does not show any strain hardening (n=0) is classed as perfectly plastic.Such a material show a constant flow stress irrespective of strain. K can be found by substituting n and a data point (from the plastic region) in the power law or from the y-intercept.
 
 Strain hardening reduces ductility and increases brittleness.e.g. Cold working can be easily demonstrated with piece of wire or a paper clip. Bend a straight section back and forth several times. Notice that it is more difficult to bend the metal at the same place. In the strain hardening area dislocations have formed and become tangled, increasing the strength of material. continued bending will eventually cause the wire to break at the bend due to fatigue cracking.

## Idealized Stress- Strain Curve

If a rod of a ductile metal, such as mild steel, is tested under a simple uniaxial tension, the stress-strain diagram would be like the one shown in Fig.

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/2a1b7085-2167-4cf4-9c50-025833caebc1)

As can be observed, the curve has several distinct regions. Part OA is linear, signifying that in this region, the strain is proportional to stress. if a specimen is loaded within this limit and gradually unloaded, it returns to its original length without any permanent deformation. This is the linear elastic region and point A denotes the limit of proportionality.Beyond A, the curve becomes slightly non-linear. However, the strain upto point B is still elastic. Point B, therefore, represents the elastic limit.
If the specimen is strained further, the strain drops suddenly (represented by point C) and thereafter the material yields at constant stress. After D, further straining is accompanied by increased stress, indicating work hardening. In the figure, the elastic region is shown exaggerated for clarity. 

Most metals and alloys do not have a distinct yield point. The change from the purely elastic to the elastic-plastic state is gradual. Brittle materials, such as cast iron, titanium carbide or rock materials, allow very little plastic deformation before reaching the breaking point. The stress-strain diagram for such a material would look like the one shown in Fig.(b)
In order to develop stress-strain relations during plastic deformation, the actual stress-strain diagrams are replaced by less complicated ones. These are shown in Fig.

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/32288b63-eba8-4ffa-8e16-138eb4cb729c)

Fig. Ideal stress-strain diagram for a material that is (a) Linearly elastic (b) Rigid-perfectly plastic (c) Rigid-linear work hardening (d) Linearly elastic-perfectly plastic (e) Linearly elastic-linear work hardening
In these, Fig.(a) represented a linearly elastic material, while Fig.(b) represents a material which is rigid (i.e. has no deformation) for stresses below $\sigma_{y}$ and yields without limit when the stress value reaches the value $\sigma_{y}$. Such a material is called a rigid perfectly plastic material. Figure(c) shows the behaviour of a material which is rigid for stresses below $\sigma_{y}$ and for stress levels above $\sigma_{y}$ a linear work hardening characteristics is exhibited. A material exhibiting this characteristics behaviour is designated as rigid linear work hardening. Figure(d) and (e) represent respectively linearly elastic, perfectly plastic and linearly elastic-linear work hardening. 

## Yield Creation

The general behaviour of an elastic-plastic material at the time of failure, under uniaxial state of stress can be related to its behaviour under multi-axial state of stress by some 'Laws'. Such laws collectively form the basis of classical plasticity and provide the necessary information for establishing some plastic stress-strain relations.   

## Yield Criteria of Tresca and Von Mises

Maximum Shear Stress Criteria, or TRESCA Condition : It has been 
shown earlier for a two-dimensional case, that if $\sigma_1$ and $\sigma_2$ are the principal stresses, maximum shear stress $\tau_{max}$ = $\cfrac{1}{2}$($\sigma_1$ - $\sigma_2$). For a general case, if the principal stresses are $\sigma_1$, $\sigma_2$, $\sigma_3$ and $\sigma_1$ greater than $\sigma_2$ greater than $\sigma_3$,
 $\tau_{max}$ = $\cfrac{1}{2}$($\sigma_1$ - $\sigma_2$)

According to Tresca, (1864), yielding occurs when the greatest absolute value of any one of the three maximum shear stresses reaches a certain value, i.e. ($\sigma_i$ - $\sigma_j$) = $\sigma_o$ . For uniaxial stresses, $\sigma_1$ = $\sigma_o$ and $\sigma_2$ = $\sigma_3$ = 0, hence according to Tresca's condition,

$\tau_{max}$ = $\cfrac{1}{2}$($\sigma_1$ - 0) = $\cfrac{1}{2}$ $\sigma_o$

where $\sigma_o$ is the yield stress in a uniaxial tension test. It can be noted that the intermediate principal stress σ, has no effect on yielding according to Tresca and this constitutes a slight defect in this theory, to be corrected in the next one.
Octohedra Shear Stress Criterion, or Von-Mises Condition : This yield criterion is based on the argument that energy of distortion must reach a certain value to cause failure. Energy of distortion can be written as

U' = $\cfrac{1}{12G}$[($\sigma_1$ - $\sigma_2$)^2 +  ($\sigma_2$ -  $\sigma_3$)^2 +   ($\sigma_3$ -  $\sigma_1$)^2]
But $\tau_{oct.}$ = $\cfrac{1}{3}$ $\sqrt($ $\sigma_1$ - $\sigma_2$)^2 + ($\sigma_2$ - $\sigma_3$)^2 + ($\sigma_3$ - $\sigma_1$)^2

giving, U' = $\cfrac{3}{4}$($\tau_{oct.}$^2/G)

Therefore, more conveniently, it can be stated that 'yielding occurs when the numerical value of octohedral shear stress reaches a certain value'.
For uniaxial stress, $\sigma_1$ = $\sigma_o$ ,

and, $\tau_{oct.}$ = $\cfrac{\sqrt{2}}{3}$ $\sigma_o$

Therefore, more conveniently, it can be stated that 'yielding occurs when the numerical value of octohedral shear stress reaches a certain value'.
For uniaxial stress, $\sigma_1$ = $\sigma_o$,

and, $\tau_{oct.}$ = $\cfrac{\sqrt{2}}{3}$ $\sigma_o$

NUMERICAL: Consider the following case of plane stress, $\sigma_{x}$ = 2/3 x 10^3 kg/cm^2, $\sigma_{y}$ = 4/3 x 10^3 kg/cm^2 and $\sigma_{xy}$ = 1/3 x 10^3 kg/cm^2.
If the yield stress is  4/3 x 10^3 kg/cm  determine  whether there is yielding according to Tresca's and Von-Mises' conditions or not.

Soluton : First we have to find the principal stresses. As all the stresses, including the yield stress are in a certain ratio we can write them as :

$\sigma_{x}$ = 2C

$\sigma_{y}$ = 4C

$\tau_{xy}$ = C

where C = $\cfrac{1000}{3}$ $kg/cm^2$, $\sigma_o$ = 4C

Now the calculations will become very simple,

$\sigma_{1,2}$ = C  [ $\cfrac{4 + 2}{2}$ + $\cfrac{1}{2}$ $\sqrt($ 4 - 2)^2 + 4 x 1^2  ]

= (3 + $\sqrt($ 2) C

So the three principal stresses will be,

(3 + $\sqrt($ 2) C, (3 - $\sqrt($ 2) C, 0

and $\tau_{oct.}$ = $\cfrac{1}{3}$  $\sqrt($ $\sigma_1$ - $\sigma_2$)^2 + ($\sigma_2$ -  $\sigma_3$)^2 + ( $\sigma_3$ -  $\sigma_1$)^2

= $\cfrac{1}{3}$ $\sqrt($ 2 $\sqrt($ 2)^2 + (3 - $\sqrt($ 2)^2 +  (3 + $\sqrt($ 2)^2 x C

= $\cfrac{1}{3}$ $\sqrt($ 30) x C

= 1.825 C

$\tau_{max}$ = $$\cfrac{(3 + \sqrt( 2)C - 0}{2}$$ = $\cfrac{(3 + 1.141) C}{2}$

= 2.207 C

Again as $\sigma_o$ = 4C

($\tau_{oct.}$)_yield = $\sqrt($ 2/3 $\sigma_o$} = 1.885 C


($\tau_{max}$)_yield = $\sigma_o$/2 = 2.0 C

Therefore, actual $\tau_{max}$ is less than $\tau_{oct.}$ at yield and yielding does not occur according to Von-Mises condition. But actual $\tau_{max}$ is more than $\tau_{max}$ at yield, so yielding does occur according to Tresca condition.

## Plastic Stress-Strain Relations
The stress–strain relations for plastic flow relate the strain increments.The process of plastic flow is irreversible; that most of the deformation work is transformed into heat and that the stresses in the final state depend on the strain path. Consequently,the equations governing plastic deformation cannot,in principle,be finite
relations concerning stress and strain components as in the case of Hooke’s law,but must be differential relations.

For elastic deformation, the stress-strain relations are expressed by Hooke’s law:

$\epsilon_{1}=\frac{1}{E}[\sigma_{1}-v(\sigma_{2}+\sigma_{3})]$

By analogy, plastic stress-strain relations may be written (noting that $v=\frac{1}{2}$ for constant-volume plastic deformation) as

 $d\epsilon_{1}^p= d\lambda[\sigma_{1}- \frac{1}{2}(\sigma_{2}+\sigma_{3})]$

 $d\epsilon_{2}^p= d\lambda[\sigma_{2}- \frac{1}{2}(\sigma_{1}+\sigma_{3})]$

 $d\epsilon_{3}^p= d\lambda[\sigma_{3}- \frac{1}{2}(\sigma_{1}+\sigma_{2})]$ 

The plastic strain increment $d\epsilon^{2}$ is related to the stresses by a proportionality factor $d\lambda$ replacing $1/E$ in Hooke’s law. The factor $d\lambda$ is not a material constant as Young’s modulus. $d\lambda$ is a positive quantity. These equations may be further expressed by using the deviatoric stresses $\sigma_{1}^{'}$, $\sigma_{2}^{'}$ and $\sigma_{3}^{'}$.

$d\epsilon_{1}^p= d\lambda[(\sigma_{1}- \sigma_{m})-\frac{1}{2}(\sigma_{2}+\sigma_{3})+\sigma_{m}]$

= $d\lambda[\sigma_{1}^{'}-\frac{1}{2}(\sigma_{2}^{'}+ \sigma_{3}^{'})]$

= $d\lambda[\sigma_{1}^{'}-\frac{1}{2}(\sigma_{2}^{'}+ \sigma_{3}^{'}+ \sigma_{1}^{'}-\sigma_{1}^{'})]$

= $d\lambda[\frac{3}{2}\sigma_{1}^{'}-\frac{1}{2}(\sigma_{1}^{'}+ \sigma_{2}^{'}+ \sigma_{3}^{'})]$

Since by definition $\sigma_{1}^{'}$+ $\sigma_{2}^{'}$ + $\sigma_{3}^{'}$ = 0, this reduces to;

$d\epsilon_{1}^p = \frac{3}{2}d\lambda\sigma_{1}^{'}$

Equations thus take the form:

$\frac{d\epsilon_{1}^p}{\sigma_{1}^{'}}$ = $\frac{d\epsilon_{2}^p}{\sigma_{2}^{'}}$ = $\frac{d\epsilon_{3}^p}{\sigma_{3}^{'}}$ = $\frac{3}{2} d\lambda$ 

which implies that the plastic-strain increments are proportionally related to the deviatoric stress components and not to the total stresses. This is consistent with the assumption that plastic deformation is independent of the hydrostatic stress component $\sigma_{m}$.The plastic stress-strain increment
relations as given by equations are often called the Levy-Mises "plastic" flow rule. Such relations are not complete since the proportionality factor $d\lambda$ is yet to be determined.

Equations can be integrated to give 

$\frac{\epsilon_{1}^p}{\sigma_{1}^{'}}$ = $\frac{\epsilon_{2}^p}{\sigma_{2}^{'}}$ = $\frac{\epsilon_{3}^p}{\sigma_{3}^{'}}$ = $\frac{3}{2} \lambda$

 where the total plastic strains are used instead of their increments. 

Some approximations for the plastic part are:

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/f70d116b-91a4-45d2-a62f-0f46e716ac13)

1. By a straight line as shown in fig (b) when the relation is, $\sigma$ = A + B $\epsilon$, where A = $\sigma_{o}(1-B/E)$ and A and B are constants.

2. By a power curve expression, only for the plastic part, $\sigma= k \epsilon^m$, where k and m are strain hardening components shown in fig.(c).

3. By two straight lines for ideal elastic-plastic materials without any strain hardening. Shown in fig.(d).

4. By a single straight line parallel to x-axis for an ideal rigid-plastic material.This shown in fig.(e) and can be used for large plastic deformation where in the elastic part of the deformation $\epsilon_{E}$ can be neglected compared to the plastic portion $\epsilon_{p}$. 

# Numerical

In sheet metal stretching, a grid o f circles is often printed on the sheet metal surface to investigate the zones of heavy deformation, as shown in fig. A circle of such a grid o f 5 mm diameter has changed after a stretching process into an ellipse whose major and minor axes are 6.5 and 5.5 mm, respectively. If the stresses are proportionally such that $\sigma_{1} > \sigma_{2}$,where the final value of
$\sigma_{2}$ is 300 MPa. Determine the value of the applied load $P_{1}$ (at the end of the process), which causes this deformation in a uniformly stretched square sheet metal o f initial dimensions 100 x 100 x 2mm. Also determine the yield strength at the end of this stretching process.

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/5e849e70-b05c-4b75-94a7-9e5f3fa6874a)

Solution: The plastic strain components are given by 

 $\epsilon_{1}^p = In (\frac{6.5}{5}) = 0.262$

and  $\epsilon_{2}^p = In (\frac{5.5}{5}) = 0.095$

 For homogeneous strains constancy of volume is expressed by

$\epsilon_{1}^p + \epsilon_{2}^p + \epsilon_{3}^p = 0$

giving    

 $\epsilon_{3}^p = -(\epsilon_{1}^p + \epsilon_{2}^p) = - 0.357$

Applying the Levy-Mises flow rule,Equations, this is a plane stress process $(\sigma_{3} = 0)$ results in

$\frac{\epsilon_{1}^p}{\sigma_{1}^{'}}$= $\frac{\epsilon_{2}^p}{\sigma_{2}^{'}}$= $\frac{\epsilon_{3}^p}{\sigma_{3}^{'}}$ = $\frac{3}{2}\lambda$

 hence,  $\frac{\epsilon_{2}^p}{\epsilon_{3}^p}$= $\frac{\sigma_{2}^{'}}{\sigma_{3}^{'}}$ = $\frac{\sigma_{2}-\sigma_{m}}{0-\sigma_{m}}$ = $\frac{300 - \sigma_{m}}{-\sigma_{m}}$

This gives $\sigma_{m} = 236.95 MPa$. Similarly,

 $\frac{\epsilon_{1}^p}{\epsilon_{2}^p}$= $\frac{\sigma_{1}^{'}}{\sigma_{2}^{'}}$ = $\frac{\sigma_{1}-\sigma_{m}}{\sigma_{2}-\sigma_{m}}$

hence, $\sigma_{1} = 410.83 MPa$. To determine the load P at the end of the stretching process, the final overall sheet dimensions must be calculated according to    

$\epsilon_{1}^p = In \frac{L_{1}}{L_{o}}$ giving $L_{1} = L_{o}  exp(0.262) = 129.95 mm$

$\epsilon_{2}^p = In \frac{L_{2}}{L_{o}}$ giving $L_{2} = L_{o}  exp(0.095) = 109.96 mm$

$\epsilon_{3}^p = In \frac{h}{h_{o}}$ giving $h = h_{o}  exp(-0.357) = 1.44 mm$

Hence, the load at the end of the stretching process is 

$P_{1} = \sigma_{1}L_{2}h$ = $410.83$ x $109.96$ x $1.399$  =  $63.224 kN$ 

The yield strength at the end of the process is obtained by applying either von Mises or Tresca criteria for plane stress $\sigma_{1}>\sigma_{2}>(\sigma_{3} = 0).$ 

von Mises: $Y = (\sigma_{1}^2 + \sigma_{2}^2 - \sigma_{1}\sigma_{2})^\frac{1}{2}$

giving $Y = 368.15 MPa$

Tresca $Y = \sigma_{1} - \sigma_{3}$

 giving  $Y = 410.83 MPa$    

### Isotropic Hardening

 The effective stress Equation,The von Mises yield criterion has been stated as:

$\Bar{\sigma} = Y = \frac{1}{\sqrt{2}}[(\sigma_{1}-\sigma_{2})^2 + (\sigma_{2}-\sigma_{3})^2 +  (\sigma_{3}-\sigma_{1})^2]^\frac{1}{2}$

The true stress-strain curve for a strain-hardening material is looked upon as a locus of successive yield points. Hence, at any plastic strain value $\Bar{\epsilon}^ p$, the stress $\Bar{\sigma}$ corresponds to a yield stress Y, which should be applied to cause further plastic deformation. This means that the yield locus (e.g., von Mises ellipse in plane stress) expands during plastic flow with its center and axes remaining fixed as shown in fig.

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/546d124a-eebc-4c3f-b732-0f98e17c58dc)

The size of the yield ellipse is simply determined from the simple tensile $\Bar{\sigma}- \Bar{\epsilon}$ curve at the specified value of $\int d\epsilon^p$. Note that for each ellipse $\Bar{\sigma}$ =constant.In fig. shows Expansion of the von Mises yield locus according to the isotropic-hardening rule.

 This representation of yield surfaces for strain-hardening materials is known as the isotropic hardening rule.

### Principle of Normality and Plastic Potential

 Consider for simplicity, the von Mises yield criterion in plane stress condition ($\sigma_{2}$ = 0),

i.e, Equation 

$\sigma_{1}^2  + \sigma_{3}^{2} -\sigma_{1}\sigma_3 = Y^2$

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/0fd8d395-6f6a-431c-a752-f367d6425881)

 It has been shown that this equation is represented by an ellipse in fig.\\ The slope at any point on this ellipse is $\frac{d\sigma_{3}}{d\sigma_{1}}$ obtained by differentiation of Equation as 

 $\frac{d\sigma_{3}}{d\sigma_{1}} = \frac{2\sigma_{1}-\sigma_{3}}{2\sigma_{3}-\sigma_{1}} = - \frac{\sigma_{1}^{'}}{\sigma_{3}^{'}}$

 Hence, the slope of the outward normal is $\frac{\sigma_{3}^{'}}{\sigma_{1}^{'}}$.

This result means that the vector drawn perpendicular to the tangent at any point on the yield surface will have projections proportional to $\sigma_{1}^{'}$ and $\sigma_{3}^{'}$ at this point. In view of the Levy-Mises flow rule, which state that the plastic strain increments $d\epsilon_{1}^p$ and $d\epsilon_{3}^p$ are proportional to  $\sigma_{1}^{'}$ and $\sigma_{3}^{'}$ respectively, the plastic strain increment vector is thus normal to the yield
surface.

Such a property is a general one and is not restricted to isotropic materials. It is also very useful in constructing experimental yield loci as shown in Figure. This figure only the projection of the strain vector appears in the  $\sigma_{1}$ - $\sigma_{3}$ plane; but it is still perpendicular to the yield locus line. Now, let the von Mises yield criterion (again for simplicity in plane stress conditions) be considered as a function $f$.

$f = \sigma_{1}^2 + \sigma_{3}^2 - \sigma_{1}\sigma_{3}-Y^2$    

Upon differentiation with respect to \vspace{6}$\sigma_{1}$ and $\sigma_{3}$,

$\frac{\partial f}{\partial\sigma_{1}}= 2\sigma_{1}-\sigma_{3}= 3\sigma_{1}^{'}$ and $\frac{\partial f}{\partial\sigma_{3}}= 2\sigma_{3}-\sigma_{1}= 3\sigma_{3}^{'}$

and in view of the Levy-Mises flow rule,it is concluded that 

$\frac{\partial f}{\partial\sigma_{1}}$: $\frac{\partial f}{\partial\sigma_{3}}$= $\sigma_{1}^{'}$ : $\sigma_{3}^{'}$= $d\epsilon_{1}^p : d\epsilon_{3}^p$

which establishes the concept of “plastic potential.” If the von Mises yield criterion is used for $f$,the “associated flow rule,” which is the Levy-Mises rule, results upon differentiation with respect to the stresses.

### Previous Year Questions

1.Ques: What are the yield surfaces of Tresca and Von mises?

2.Ques: What do you mean by Strain Hardening?

3.Ques: Define Isotropic Hardening?

4.Ques: The stress components at a point in a steel member is a tensile stress $\sigma_{x}$ and a shear stress $\tau$. The tensile elastic limit is 400 MPa. If the shear stress at the point is 200 MPa when yielding starts, what is the tensile  stress $\sigma$ at the point according to both the Tresca and the von Mises criterion? 

5.Ques: A cube of metal having a constant yield stress Y of 300 MPa experiences a stress state of $\sigma_{1}$, $\sigma_{2}$= 0.4 $\sigma_{1}$ ,and $\sigma_{3}$ = -0.6 $\sigma_{1}$ .If the stresses are gradually increased in these constant ratios, find $\sigma_{1}$ at yielding using both  the von Mises and Tresca criteria.

6.Ques: A thin-walled tube with closed ends is made from a metal whose Y = 300 MPa. The tube is 250 mm long, has a wall thickness of 1.25 mm, and a mean diameter of 75 mm. In service, the tube will be subjected to a maximum axial tensile load of 10 kN, a maximum twisting moment of 250 N.m, and will also be pressurized internally. What minimum internal pressure will cause yielding according to the von Mises criterion?

7.Ques: A thin-walled tube, with closed ends, is made of a metal whose yield strength is 300 MPa. The tube has an outer diameter of 75 mm and a wall thickness of 7 mm. After applying an axial compressive load of 3 kN to the ends, the tube is pressurized internally. What pressure p would cause yielding according to the Tresca criterion?

8.Ques: A solid, soft aluminum cylinder, 100 mm in diameter and 150 mm long is closely fitted inside a thick-walled cylinder. An axial load P is transmitted to the aluminum cylinder by means of two frictionless pistons. Aluminum possesses the following elastic constants: E = 10 GPa,v = 0.3, and yield strength of F = 80 MPa. Calculate the axial force P required to initiate yielding in aluminum.(Assume the steel cylinder to be completely rigid and apply the von Mises yield criterion.)

Navneet Kaur (2245006)

Vishal Kumar (2245010)

 Sushil Garg  (2245008)

