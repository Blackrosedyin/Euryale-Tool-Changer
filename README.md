# Euryale ToolChanger
Quasi-kinematic (Line-contact) Coupling based on MedusaHC by Irbis3D

Euryale ToolChanger is an open-source Toolchanger project that uses the extruder on the MedusaHC Toolchanger by Irbis3D with minor inspiration from CXChanger by cx330-TXY. 

This project is in its beta stage, where it is currently being developed.

<img width="1920" height="1080" alt="Assembly" src="https://github.com/user-attachments/assets/ec746d09-b1e0-408b-a9c6-6fccc8bfdf2b" />
<img width="1920" height="1080" alt="Printhead" src="https://github.com/user-attachments/assets/113fa20a-4968-4d20-bfd2-92863bd32124" />
<img width="1920" height="1080" alt="Tool (Front)" src="https://github.com/user-attachments/assets/87152016-6792-4937-9f1a-a83bb9c2b506" />
<img width="1920" height="1080" alt="Tool (Back)" src="https://github.com/user-attachments/assets/90775adc-689d-4b70-8c7f-fa1421e60c33" />



# Kinematic Overview
Quasi-kinematic coupling based on a modified Maxwell layout. This design replaces standard point-contact spheres with floating 6mm dowel barrel bolts resting on parallel 3mm dowel pins at an contact angle of 35 degrees, thus maximizing shear and transverse load capacity while maintaining reasonable positional repeatability.

By using floating dowel barrel bolts instead of rigid dowel barrel bolts, the design achieves 6-degree-of-freedom ($X, Y, Z$ and $\theta_x, \theta_y, \theta_z$) constraint, thus avoiding the 12 DOF overconstraint of a rigid system

However, this coupling would have a lower accuracy than an traditional Maxwell layout, but should have an accuracy that is good enough for a 3d printer (Approx 10 microns)

<img width="1920" height="1080" alt="Maxwell Plate R2" src="https://github.com/user-attachments/assets/088fd247-f6c2-460a-8911-697fb3985996" />
<img width="1920" height="1080" alt="Hotend Mount R2" src="https://github.com/user-attachments/assets/1222d248-f3db-40a3-a349-0e99556271a1" />
<img width="1920" height="1080" alt="Transverse" src="https://github.com/user-attachments/assets/f6c72675-ab26-4f34-9495-1dc4e052dc89" />


# Tool Power Delivery
Tools on this toolchanger are natively designed to receive power through standard USB A or Type C cables.

Direct wiring (without usb) to electronics bay will also be supported

# CAD Files
At this time, source files are view only via Fusion as the project is currently under active development:

Fusion 360 Project Link: https://a360.co/46orMO9 

(Note: Downloadable STEP, STL, and repository files will be released after physical testing confirms the toolchanger operates reliably and maintains target repeatability.)

# Credits
This project is based on the MedusaHC Toolchanger by Irbis3D
https://github.com/Irbis3D/MedusaHC/tree/main

With some minor inspiration from CXChanger by cx330-TXY
https://github.com/cx330-TXY/CxChanger

# License
The project will maintain same licensing as MedusaHC by Irbis3d, licensed under the GNU General Public License v3.0 (GPLv3).

You are free to copy, distribute, and modify the design files and documentation.
Any modifications or derivative works must also be shared under the same GPLv3 license terms.
If you distribute hardware derived from these source files, you must provide access to the CAD files and complete source code.
See the LICENSE file for the full text of the GNU General Public License v3.0.
