Week of 21 - 25.10.2022

 Monday
 - Created some OpenSim simulation examples of a pendulum and bouncing ball
 - Had trouble getting the contact to work for the bouncing ball example

 Tuesday
 - Figured out the issue because of which the contact for the bouncing ball example did not work
 - The orientation of the contact plane is important in OpenSim: Contact can be detected only if a body proceeds to travel from +ve to -ve along Y-axis

 Wednesday
 - Started out with a block model to represent the foot of a robot. 
 - Tried to find any contact models that are available in OpenSim for flat plane to plance contact, but none readily available
 - As a first step, I added very small spherical contact surfaces at the vertices of the block and used the buit-in hunt-crossley force models for the spheres at the corner vertices to make the block contact work

 Thursday
 - Started building out the legs using simple geometries, ie block, cylinders, spheres etc. with representative dimensions (The dimensions can be modified easily after I build up the model).

 Friday
