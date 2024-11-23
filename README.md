# Molcontroller

The Molcontroller is recommended to be used with VMD version 1.9.3.

INSTALLATION
============
## **1. Download and Extract Files**<br>
Move the molcontroller1.0 folder to the **YOUR-VMD-Installation-Directory/plugins/noarch/tcl** subdirectory.<br>
## **2. Configure VMD**<br>
Locate the VMD startup configuration file and add the following lines:<br>
__vmd_install_extension molcontrol molcontroller_tk "Modeling/Molcontroller"__<br>
The configuration file paths are:<br>
Windows: YOUR-VMD-Installation-Directory\vmd.rc<br>
Linux: YOUR-VMD-Installation-Directory/lib/vmd/.vmdrc<br>
macOS: YOUR-VMD-Installation-Directory/Contents/vmd/.vmdrc<br>
## 3. Launch VMD<br>
After starting VMD, you can access the Molcontroller via the Extensions -> Modeling -> Molcontroller submenu in the VMD Main menu.

# Citaion
Wu, C. C.; Liu, S. T.; Zhang, S. T.; Yang, Z. X., Molcontroller: A VMD Graphical User Interface Featuring Molecule Manipulation. J. Chem. Inf. Model. 2020, 60, 5126-5131.
