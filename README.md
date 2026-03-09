# Robotic-Linkage-Joint-Structural-Analysis
Structural analysis of a pinned mechanical joint using CAD and finite element analysis to study stress concentration, load transfer, and deformation behavior. The project evaluates how joint geometry influences structural durability and reliability, drawing parallels to pinned linkage interfaces commonly used in robotic systems.

Pinned joints are widely used in mechanical systems to transfer loads between moving components. In robotics, similar joint architectures appear in actuator linkages, hinge mechanisms, and structural interfaces that must sustain repeated loads without failure.
This project analyzes a knuckle-style pinned joint to understand:
- Stress distribution under load
- Stress concentration near geometric transitions
- Structural deformation under lateral loading
- Design modifications that improve load transfer and durability

Design Model
The joint consists of three main components:
- Eye / Lug: Load-bearing structural element
- Pin: Transfers shear load between members
- Forked clevis: Supports the pinned connection

The geometry was modeled in SolidWorks and exported as a STEP file for analysis.

Key geometric features evaluated:
- Lug thickness
- Pin diameter
- Fillet radius at transition regions
- Edge distance from pin center to outer boundary
  
These parameters strongly influence stress concentration and structural reliability.

<img width="962" height="648" alt="simple knuckle joint" src="https://github.com/user-attachments/assets/3fd14758-b0e8-4d7b-9e1a-4d8150bd2cb2" />

Stress Distribution

Maximum stress occurred near the lug-pin interface and transition fillet, which is consistent with expected stress concentration behavior in pinned joints.


Euivalent Stress Image
<img width="1266" height="497" alt="Equivalent Stress" src="https://github.com/user-attachments/assets/1c190317-d70e-419a-af39-06863b4ce391" />

Frictional Stress
<img width="1310" height="483" alt="Frictional Stress" src="https://github.com/user-attachments/assets/2429d7ce-a46c-470d-b997-6576b1ada958" />

Gap
<img width="1266" height="520" alt="Gap" src="https://github.com/user-attachments/assets/97d8065a-c6e4-4564-91dd-ad35ffd36d8e" />


Key observations:
- Peak stress located near inner surface of the eye
- Stress gradients concentrated around fillet transitions
- Shear load distributed through pin interface

Deformation
Total deformation remained within acceptable limits for the applied load case, with displacement primarily occurring along the load direction.
<img width="1256" height="419" alt="Total Deformation" src="https://github.com/user-attachments/assets/76dfae1a-536b-4eba-aaab-97e28cbae30a" />
The joint exhibited expected elastic deformation without global instability.


Future Work

Potential extensions to this project include:
- Fatigue life estimation under cyclic loading
- Contact analysis between pin and lug surfaces
- Material comparison for lightweight joint design
- Parametric optimization of joint geometry

