# SLICE-DLC-Firmware-Upgrade
Firmware for SLICE DLC models

## Requires 
  Vescent SLICE_Firmware_Upgrade_Utility available at:
  
  https://github.com/Vescent/SLICE-FFC_Firmware_Upgrade_Utility
## Instructions
 
  Left click on SLICE_Firmware_Update_Instructions.pdf and then click 'Download' to download the instructions for use.

  The V1.42 firmware upgrader automatically retrieves the upgrade files from this repository. However, if your system does not allow this,  
  You may need to perform the following steps:  
  
       Left click on the upgrade package (SLICE-DLC_Sx.xx_DCx.xx_QTx.xx.zip) and then click 'Download' to download the firmware package to your  
       hard drive.
  
       The 3 files in the .zip file need to be placed in the folder described in the instructions. DO NOT RENAME THEM!  

## Configuration S1.240_DC1.37_QT2.69 
	1.Removes all front panel A and B Temperature Related Input Modes
	Removes all Temperature Related Input Triggers.
	Blocks access to both these features through the API as well.
	2. Limits Temperature Control current output to 5A for DLC applications 

## Configuration S1.239_DC1.37_QT2.68 
  Initial Release
