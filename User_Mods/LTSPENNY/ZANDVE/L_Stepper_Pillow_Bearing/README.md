**Purpose:** Using the standard NEMA17 stepper motor 17HE19-2004S from Mercury 1.1 BOM with ZANDVE Build, found that the Left Stepper Mount toothed gear was on the far edge of the stepper shaft. This can cause issues with the shaft receiving side loads and leading to bending the shaft, breaking or early failure of stepper. After discussing with jellybob and Vprince099, the solution to be implemented is a new stepper mount configuration being added to the ZANDVE BOM. New steppers will have longer shafts with a bearing on the bottom stepper mount. Interim, I modded the files to add a pillow block with items you should have readily available from the Ender 5/plus teardown. I've also modified the slots for the bearing stacks to accomodate the extra shims in the new Merc. 1.1 release that aliviates possible belt wear issues experienced with previous versions.

Printing Instructions:
* All ZANDVE STL Slicer settings Apply. ASA/ABS
* Print with supports on build plate. 
* Locate old V-Slot wheel, use a 5mm shaft or similar to push or pull one of the bearings out.
* Press fit bearing on the side the Toothed Gear will go into.
* Assemble steppers onto top stepper mount, install toothed gear. 
* Assemble rest as normal.


* **Version Changes**
* **V.0** - Original Pillow Block addition to Left Stepper Mount
* **V.1** - Added space to allow full Mercury 1.1 Bearing Stack install. (**CURRENT UPLOADED VERSION**)
