🛠️ Description  
This project focuses on designing a scaffold for large bone defects, specifically targeting the humerus bone, using advanced computational methods. The goal was to create a FCCZ (Face-Centered Cubic Z) structure that can be used as a potential solution for bone defect treatment through 3D printing and biomaterial scaffolding.

🧮 Project Workflow
- Fracture Replacement Design: The fractured portion of the humerus bone was initially modeled using SOLIDWORKS 2023. The model served as the base for defining the coordinates of the nodes and elements uaing ANSYS.
- Organizing Nodes for FCCZ Structure: Using MATLAB, the coordinates of the nodes were organized into a FCCZ structure. This structure was achieved through an optimization algorithm that arranges the nodes into a lattice configuration suitable for bone replacement.
- 3D Model Generation: The coordinates and elements of the FCCZ scaffold were then processed using a modified version of the code from the [3D-printed splints demo tutorial](https://github.com/sim3DMedLab/3D-printed-splints-demo-tutorial). This step converted the nodes and elements into a 3D mesh model using BLENDER.
- Finite Element Analysis: The final FCCZ scaffold design was subjected to a Finite Element Analysis (FEA) using ANSYS to assess its mechanical properties and suitability for bone replacement.

📌 Attribution  
This project contains a *modified version* of `MeshToTruss.py` from:  
[3D-printed splints demo tutorial](https://github.com/sim3DMedLab/3D-printed-splints-demo-tutorial/blob/main/3%20Create%203D%20splint%20model/MeshToTruss.py)  
Original copyright (c) 2021 maxSIMhealth  
Used under a non-commercial license (see `LICENSE-MAXSIM.txt`).  
All other files in this repository are my original work and are licensed under the Apache License 2.0.  

📜 License  
- My Work: Licensed under the Apache License, Version 2.0 (see `LICENSE`)  
- MeshToTruss.py: Licensed under the terms set by maxSIMhealth (see `LICENSE-MAXSIM.txt`)  

🏗️ How to use  
This information will be made available on request.
E-mail: sepehrsohrabi47@gmail.com / sepehr_sohrabi@iust.ac.ir

🙌 Contributions  
Contributions are welcome! However, any modifications to `MeshToTruss.py` must comply with its non-commercial license.  

⚖️ Legal Disclaimer  
By using this software, you agree to the terms of the Apache License 2.0 for all original work in this repository. This software is provided "as is", without warranty of any kind.  
