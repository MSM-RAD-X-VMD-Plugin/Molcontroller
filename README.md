# Molcontroller

The Molcontroller is recommended to be used with VMD version 1.9.3.

INSTALLATION
============
## **1. Download and Extract Files**<br>
Define $VMD_HOME as your VMD installation path. Move the molcontroller1.0 folder to the **$VMD_HOME/plugins/noarch/tcl** subdirectory.<br>
## **2. Configure VMD**<br>
Locate the VMD startup configuration file and add the following lines:<br>
__vmd_install_extension molcontrol molcontroller_tk "Modeling/Molcontroller"__<br>
The configuration file paths are:<br>
Windows: $VMD_HOME\vmd.rc<br>
Linux: $VMD_HOME/lib/vmd/.vmdrc<br>
macOS: $VMD_HOME/Contents/vmd/.vmdrc<br>
## 3. Launch VMD<br>
After starting VMD, you can access the PACKMOL-GUI via the Extensions -> Modeling -> Molcontroller submenu in the VMD Main menu.

# Citaion
J. Chem. Inf. Model. 2020, 60, 10, 5126–5131
