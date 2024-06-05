# debloat_samsung

- USB driver
- change USB settings to "USB tethering"

adb devices
adb shell
adb shell pm uninstall --user 0 com.android.apps.x  


- Once in your device's shell, you can use the following command to list installed packages by name.

pm list package | grep '<package name>'
