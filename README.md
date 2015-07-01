# Modbus-RTU-Serial-for-Android
This repository includes Android code that is needed to communicate modbus RTU serial through the microUSB port. 

For this code to work,there are specific android system files that need to be changed. There area few tablets out 
there that already include this change, but most do not.  To change any system files an Android device needs to be rooted.

The two files that need to be changed are:
  - android.hardware.usb.host.xml
  - tablet_core_hardware.xml
  
These files are located in the permissions folder. The file path to this folder is  "/etc/permissions/". 
  
These files examples are loaded within this repository.

Once verified that these files are correct your android device will be ready to use. 



   
   
