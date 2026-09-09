# Euryale ToolChanger
Line-Contact Kinematic Coupling fork of MedusaHC by Irbis3D

Euryale Tool Changer is an open-source Toolchanger project based on the MedusaHC Toolchanger by Irbis3D with minor inspiration from CXChanger by cx330-TXY. 

This project is in its beta stage, where it is currently being developed.

<img width="1920" height="1080" alt="Full Picture" src="https://github.com/user-attachments/assets/da86499b-792d-4dee-ab9c-63b9d3df01d7" />

# Kinematic Overview
Kinematic coupling based on a modified Maxwell layout. This design replaces standard point-contact spheres with floating 6mm barrel bolts resting on parallel 3mm dowel pins, thus maximizing shear and transverse load capacity while maintaining reasonable positional repeatability.

By using floating dowel barrel bolts instead of rigid dowel barrel bolts, the design achieves an exact 6-degree-of-freedom ($X, Y, Z$ and $\theta_x, \theta_y, \theta_z$) constraint, avoiding the 12-DOF over-constraint of a rigid system

<img width="1920" height="1080" alt="Maxwell Plate R2" src="https://github.com/user-attachments/assets/088fd247-f6c2-460a-8911-697fb3985996" />
<img width="1920" height="1080" alt="Hotend Mount R2" src="https://github.com/user-attachments/assets/1222d248-f3db-40a3-a349-0e99556271a1" />
<img width="1920" height="1080" alt="Assembly" src="https://github.com/user-attachments/assets/4490907c-39f4-4209-ba25-7918877021d2" />

# Tool Power Delivery
Tools on this toolchanger are planned and designed to receive power through standard USB A or Type C cables.

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
