# LTR507-LTR553-LTR556_Ardunio
This is an [LTR507-LTR553-LTR556_Arduino](https://github.com/chenhonglin/LTR507-LTR553-LTR556_Arduino) library for [LTR507](https://optoelectronics.liteon.com/upload/download/DS86-2013-0014/LTR-507ALS-01_FINAL%20DS.pdf) /[LTR553](http://img.cecport.com/product/product/files/201507/ff8080814e8a6b06014e9502b57a0024.pdf) /[LTR556](https://optoelectronics.liteon.com/upload/download/DS86-2015-0015/LTR-556ALS-01_DS_V1.pdf) drive.
The LTR-507/LTR-553/LTR-556 is an integrated low voltage I2C digital light sensor [ALS] and proximity sensor [PS] with built-in emitter, in a single miniature chipled lead-free surface mount package.This is the arduino library for LTR507, LTR553, LTR556 .


## Installation

- Click on the `Download ZIP` button in the top right corner.
- Uncompress it.
- Rename the uncompressed folder to `LTR507_LTR553_LTR556`.
- Check that the LTR507_LTR553_LTR556 folder contains ltr_5xx.cpp and ltr_5xx.h files.
- Choose a different macro definition for your device type in ltr_5xx.h, '#define LTR507' if you are using LTR-507 or '#define LTR55X' if you are using LTR-553 or LTR-556. Then save the ltr_5xx.h file. For examples of how to use the library, refer to the example directory.
- Place the `LTR507_LTR553_LTR556` folder in your `<arduinosketchfolder>/libraries/` folder - you may need to create the `libraries` subfolder if it is your first library.
- Restart the IDE.
