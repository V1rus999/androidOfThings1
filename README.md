# Android Things Test

# Installing android things to raspberry pi

https://developer.android.com/things/hardware/raspberrypi.html

Connect to device (get ip from router or screen): adb connect ip


Connect device to your wifi : adb shell am startservice -n com.google.wifisetup/.WifiSetupService -a WifiSetupService.Connect -e ssid said -e passphrase password


Check wifi status on device : adb logcat -d | grep Wifi


