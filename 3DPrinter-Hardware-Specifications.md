# Heavily Modified Creality Ender 5 Plus

## Unchanged Stock Components

* Heated bed
* Frame
* Stepper motors
* Lead screws for Z axis
* Chassis/Housing
* Solid State relay that drives heating of the heated bed

## Updated/Added Components

* Replaced stock board with Big Tree Tech Manta M8P V2.0 board
* Added 5 BIGTREETECH TMC2209 V1.3 Stepper Motor Drivers to the Manta M8P board that drive:
  * The extruder.
  * 2 Z-Axis stepper motors (each one is driven independently via a separate driver).
  * The Y axis stepper motor.
  * The X axis stepper motor.
* Installed a Raspberry Pi Compute Module 4, Wireless, 8GB, 32GB - CM4108032 onto the Manta M8P with:
  * CM4 Cooler, 55x40x13.5 mm, Black
  * 2.4GHz/5.8GHz Antenna kit for Compute Module
* Cut a rectangular opening in the case and fitted this mount shield and face plate: https://www.thingiverse.com/thing:5880034
*  BIGTREETECH PI TFT50 V2.1 for Raspberry Pi
* 3D printed and installed this mount for the TFT50: https://www.printables.com/model/189121-ender-5-plus-btt-pitft50-mount
* Installed Klipper version v0.12.0-413-ga0cadccee
* Made a number of pull requests to improve heating stability during bed mesh probing and homing accuracy. PRs are visible on the klipper github repository under my name (Nick Weedon) and also on the Klipper Discourse.
* Added spider coupling to the Z Axis lead screws
* Replaced the standard lead screw threads on the bed with POM anti-backlash nuts.
* Removed the stock boweden extruder and replaced the stock toolhead with a Microswiss Revo NG Direct Drive
* Replaced the stock Microswiss Revo NG Direct Drive shroud with a custom shroud that integrated two Sunon Maglev 12VDC fans (MF50151VX-1B00U-A99) and also holds a ADXL345 accelerometer.
* Replaced the standard power supply with a RSP-500-24 AC-DC Switching Enclosed Power Supply.
* Replaced the stock BLTouch probe with a BIQU MicroProbe V2.0.
* Installed a BIGTREETECH Relay V1.2 Automatic Shutdown Module.
* Added 16 aluminum support brackets to each corner (4 faces of the frame, excluding the top and bottom frame) of the frame to increase rigidity.
* Installed a Logitech HD Pro Webcam C920 via the Manta M8P USB port.


