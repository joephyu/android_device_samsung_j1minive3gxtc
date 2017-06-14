## TWRP device tree for Galaxy J1 prime mini (SM-J106B)

Add to `.repo/local_manifests/j1minive3gxtc.xml`:


<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/j1minive3gxtc" name="android_device_samsung_aj1minive3gxtc" remote="TeamWin" revision="android-7.1" />
</manifest>


Then run `repo sync` to check it out.

To build:

` . build/en* `
` lunch omni_j1minive3gxtc-eng `
` make -j5 recoveryimage `
