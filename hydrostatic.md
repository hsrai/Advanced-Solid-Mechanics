# Hydrostatic And Deviatoric Components

### Hydrostatic  State  And  Pure  Shear State (Deviatoric  State):

The state of stress at a point can be characterised by the six rectangular stress components referred to a coordinate frame of reference. The magnitudes of these components depend on the choice of the coordinate system. If, for at least one particular choice of the frame of reference, we find that σx =σy = σz = 0, then a state of pure shear is said to exist at point P. For such a state, with that particular choice of coordinate system, the stress matrix will be                 

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/53a4640b-9539-448a-90e4-26effd0f4ee1)

For this coordinate system, l₁= σx + σy+ σz = 0. Since l₁ is an invariant, this must be true for any choice of coordinate system selected at P. Hence, the necessary condition for a state of pure shear to exist is that l₁ = 0.

When l₁=0, an octahedral plane is subjected to pure shear with no normal stress. Hence, for a pure shear stress state, the octahedral plane ( this plane is defined with respect to the principal axes and not with respect to an arbitrary set of axes) is free from normal stress.

It will be shown in the present section that an arbitrary state of stress can be resolved into a hydrostatic state and a state of pure shear. Let the given state referred to a coordinate system be

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/1df41209-d804-4e38-b4dc-618b5e2cbf43)

Let            P = 𝟏⁄𝟑 (σx + σy + σz ) = 𝟏⁄𝟑  l₁                  (1)

The given state can be resolved into two different states, as shown:
![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/ffe0b899-95de-474a-82e7-576303e5f574)

The first state on the right-hand side of the above equation is a hydrostatic state. 

The second state is a state of pure shear since the first  invariant for this state is 

                 l’₁= (σx – P) + (σy – P) + (σz – P)
                      = σx + σy + σz – 3P
                      =  0 from eq(1)

If the given state is referred to the principal axes, the decomposition into a hydrostatic state and a pure shear state
can once again be done as above, i.e.

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/dfc201d9-8f41-48c5-80c7-43e80a708b3c)

 where, as before, p = 𝟏⁄𝟑 (σ₁ + σ₂ + σ₃) = 𝟏⁄𝟑 l₁.

 The pure shear state of stress is also known as the deviatoric state of stress or simply as stress deviator.

### Octahedral  Stresses:

Let  the  frame of reference be again chosen along σ₁, σ₂ and σ₃ axes. A  plane  that  is  equally  inclined  to  these  three  axes  is  called  an octahedral  plane.  Such  a  plane 
will have nx = ny = nz. Since n²x + n²y + n²z
= 1, an octahedral plane will be defined by
nx = ny = nz = ± 1/√3. There are eight such
planes, as shown in diagram.

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/70baa833-c8c4-4cd6-a316-58ff79feccf7)

The normal and shearing stresses on these planes are called the octahedral normal stress and octahedral shearing stress respectively. Substituting nx = ny = nz = ±1/√ 3 

      σoct = 1/3  (σ₁ + σ₂ + σ₃) = 1/3 l₁               (2)

and            τ²oct = 1/9 [( σ₁ - σ₂)² +( σ₂ - σ₃)² + ( σ₃ - σ₁ )²]                   
or             9τ²oct = 2( σ₁ + σ₂ + σ₃)² - 6( σ₁σ₂ + σ₂σ₃ + σ₃σ₁ )                          
 or              τoct = (√𝟐)/𝟑 (l²₁ - 3l₂)½             (3)
  
It is important to remember that the octahedral planes are defined with respect to the principal axes and not with reference to an arbitrary frame of reference. Since σoct and τoct have been expressed in terms of the stress invariants, one can express these in terms of σx, σy, σz, τxy, τyz and τzx also.

 σoct  = 1/3 (σx + σy + σz)
 
 9τ²oct  = (σx - σy )²+ (σy – σz )² + 6(τ²xy+ τ²yz+ τ²zx      
 
The octahedral normal stress being equal to 1/3 l₁, it may be interpreted as the mean normal stress at a given point in a body. If in a state of stress, the first invariant (σ₁ + σ₂ + σ₃) is zero, then the normal stresses on the octahedral planes will be zero and only the shear stresses will act.
         
### Numericals:

1.) The state of stress characterised by τij is given below. Resolve the given state into a hydrostatic state and a pure shear state. Determine the normal and shearing stresses on an octahedral plane. Compare these with the σoct and τoct calculated for the hydrostatic and the pure shear states. Are the octahedral planes for the given state, the hydrostatic state and the pure shear state the same or are they different? Explain why.
![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/7ab657ee-b874-4e82-acd0-fee4f1a41535)

Solution :            l₁ = 10 + 2 + 6 = 18, 𝟏⁄𝟑 l₁ = 6 

Resolving into hydrostatic and pure shear state,   

![image](https://github.com/Navneetk675/Advanced-Solid-Mechanics/assets/126227667/0a5e71de-b737-4870-b999-10102b0837fd)

 For the given state, the octahedral normal and shear stresses are:    

                        σoct = 1/3 l₁ = 6

From eq (3)            

 τoct  = (√𝟐)/𝟑 (l²₁ - 3l₂)½ 
 
       = (√𝟐)/𝟑  [18²- 3(20 -16+12 – 64 + 60 -36)]½
  
       = (√𝟐)/𝟑 "(" 396)½ = 2 √22

 For the hydrostatic state, σoct = 6, since every plane is a principal plane with σ = 6 and consequently, τoct = 0.

For the pure shear state, σoct = 0 since the first invariant of stress for the pure shear state is zero. The value of the second invariant of stress for the pure shear state is 

              l’₂ = ( -16 – 16 + 0 – 64 + 0 – 36 ) = - 132 

Hence, the value of τoct for the pure shear state is 

               τoct  = (√𝟐)/𝟑 (396)½ = 2 √22     

Hence, the value of σoct for the given state is equal to the value of σoct for the hydrostatic state, and τoct for the given state is equal to τoct for the pure shear state.      

The octahedral planes for the given state (which are identified after determining the principal stress directions), the hydrostatic state and the pure shear state are all identical. For 
the hydrostatic state, every direction is a principal direction, and hence, the principal stress directions for the given state and the pure shear state are identical. 
