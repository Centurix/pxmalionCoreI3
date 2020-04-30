**MODIFIED FOR A CUSTOMISED PRINTER**

This is my copy of the original Pxmalion Core I3 Marlin software with the following adjustments:

* Disabled filament feed detector (my Pxmalion Core I3 didn't have one)
* Reversed the filament feed motor direction (for a right side mounted Bowden tube)
* Removed excessive exclamation marks in some source files (more than two caused avrdude to complain and not upload, see [StackOverflow](https://stackoverflow.com/a/29135050) )

Bowden tube modification is based on this: [Thingiverse](https://www.thingiverse.com/thing:3842298)

Note that the Amazon link for the quick release is actually a mirror of the one used in the project, hence the reversed filament feeder motor direction.


# **Firmware CoreI3**

This Firmware is for the [Corei3](http://www.pxmalion.com/2017/11/16/corei3/) and is base on the [Marlin](https://github.com/MarlinFirmware/Marlin) .
