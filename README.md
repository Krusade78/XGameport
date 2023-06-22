# XGameport 2.0

 NOTE: This driver is absolutely experimental use it at your own risk. It is based on the Microsoft
     Windows Driver Kit code but it is not supported by Microsoft or myself.

 This driver is usefull for those with a gameport that is not supported by the operating system or
the manufacturer, commonly in XP 64-bit and Vista.

## Installation:

- Copy the xgameenum.sys from the folder that identify you operanting system to the folder with
 the .inf file.
- Go to device manager and locate your gameport
- Open properties and go to the details tab.
- Select the property "Hardware identifiers" and copy one of the values.
- Open the xgameport.inf and replace ###HardwareID### with the copied value. Save it.
- Go to the driver tab and click on update driver...using the xgameport.inf