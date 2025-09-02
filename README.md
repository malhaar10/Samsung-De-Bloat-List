Debloat list for Samsung phones

REQUIREMENTS-> platform tools, developermode

Install platfor-tools-> refer to this video "https://youtu.be/F_XI-w6xDkM"
Credits to the video's owner

Enable developer mode-> Settings>Software Information>Build Number
Keep talling build number rapidly until developer mode is enabled
In developer mode, enable USB debugging
Connect to computer via usb cable

Navigate to/Open platform-tools folder and open
Type "adb devices"
Once the device shows up, type "adb shell sh < debloatList.sh"

Command for manually removing items> "pm uninstall --user 0 'package_name'"
