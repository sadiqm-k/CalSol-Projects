# CalSol-Projects
Showcasing my main projects and contributions to UC Berkeley's solar vehicle racing team CalSol.
***
# Array Support Structural ribs
<img width="1117" height="623" alt="image" src="https://github.com/user-attachments/assets/7a8e6fa8-dade-435a-9290-714d8880270c" />

**Fig. 1. Current iteration of structural ribs depicted as the light grey panels.**
***
#Introduction
My main project during my time at CalSol was the design of array support ribs that line the top half of our next generation solar race car. For reference, the car's body is split into two halves, respectively called the "top" and "bottom" shells. The ribs are designed to attach to the top shell using epoxy, and the support they provide is to resist bending moment caused by top shell movement during driving and/or lifting. The point of the ribs are to make sure that the top shell doesn't bend and damage the fragile solar panels that lie across its surface. 
***
#Design Consdierations
Throughout my design, I incorporated some general solid mechanic ideas. As depicted in Fig. 2, single panels of the ribs follow the curve of the top shell and use straight edges at the bottom. This maximizes the axial and vertical stiffness of the ribs because the curved section is entirely epoxied to the shell, creating a uniform built in support along the length of the rib with some thickness. The straight edge further reduces bending strain by utilizing the same geometric concept of a truss. If similar loads were to be placed on either/both ends to create the most bending moment with respect to the center of the car, the material strain would want the straight edge to stretch/compress which resists the strain. Further combined with carbon fibers incredible stiffness, the top shell resists bending. This specific consideration is displayed all throughout the design but is severely limited by other desing constraints.
<img width="1123" height="143" alt="image" src="https://github.com/user-attachments/assets/2bc79b89-b81f-40bd-8eea-eadf7f8e6bcf" />

**Fig. 2. Side isometric view of structural ribs depicting curved and straight edges.**

The ribs are limited in size due to the clearance that they need to make with the rollcage (see Fig. 1). As such, they are designed to provide stiffness to the top shell in a compact formfactor. Due to manufacturing constraints, the ribs cannot be manufactured as one piece. I am currently working as designs finalize to determine optimal locations to split the ribs into multiple, manufacturable parts. Currently, I am planning on using the areas where separate ribs meet to streamline manufacturing and integration and to evenly distribute loads. I also aim to use finger-joints at these connections to provide some resistance to vertical bending combined with epoxy.
***
Future Considerations

It has been determined that the bottom shell is also in some need of ribs to support its own bending, so I plan to work on designing similar ribs on the bottom shell using the same design considerations as top shell ribs. The bottom shell ribs will also help with the integration of an internal array-tilting mechanism which latch both halves of the car together and will use the top and bottom shell ribs as fixtures.

As I complete these designs, I hope to run these models through Ansys composites and mechanical to provide FEA data. I also need to determine a factor of safety and safe deformation limit before the cells get damaged. I do know at the moment that cells around the center ring up to the canopy of the car are at most risk of damage from forces being applied to the edge of the top shell.

One more consideration I have to make is a way to reduce torsion across top shell. Currently, the way I would like to implement this are hollow carbon fiber cross tubes which in theory should reduce cost and manufacturing time. These will connect across opposing ribs such as the two on the driver left and right sides of the car and should prevent couple forces from creating torsion on the ribs.
***
Older design(s):

<img width="332" height="712" alt="image" src="https://github.com/user-attachments/assets/0f2d80d8-a5f3-4a18-99a6-636c36e5a923" />
