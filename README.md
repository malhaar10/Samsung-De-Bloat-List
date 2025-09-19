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

#########################################################

Apps that will be removed
(edit list if you wish to keep some of them)

| Package Name                                                | App Name / Function                       | Safe to Uninstall?                        |
| ----------------------------------------------------------- | ----------------------------------------- | ----------------------------------------- |
| com.google.android.adservices.api                           | Google Ads / Ad Services                  | Yes                                       |
| com.samsung.android.mapsagent                               | Samsung Maps Agent (location services)    | Yes                                       |
| com.samsung.android.app.camera.sticker.facearavatar.preload | AR Emoji Stickers (preloaded)             | Yes                                       |
| com.google.android.gms.location.history                     | Google Location History                   | Yes                                       |
| com.android.hotwordenrollment.xgoogle                       | Hotword Enrollment (Google Assistant)     | Yes                                       |
| com.android.hotwordenrollment.okgoogle                      | Hotword Enrollment (OK Google detection)  | Yes                                       |
| com.google.android.apps.tachyon                             | Google Duo (now Google Meet)              | Yes                                       |
| com.swiftkey.swiftkeyconfigurator                           | SwiftKey Configurator                     | Yes                                       |
| com.touchtype.swiftkey                                      | SwiftKey Keyboard                         | Yes                                       |
| com.microsoft.skydrive                                      | Microsoft OneDrive                        | Yes                                       |
| com.samsung.android.mdx                                     | Samung MAX                                | Yes                                       |
| com.microsoft.appmanager                                    | Microsoft Phone Link                      | Yes                                       |
| com.google.android.feedback                                 | Google Feedback                           | Yes                                       |
| com.google.android.googlequicksearchbox                     | Google App (Search + Discover)            | Risky (affects search & assistant)        |
| com.google.android.apps.messaging                           | Google Messages (SMS/RCS)                 | Risky (affects SMS)                       |
| com.facebook.appmanager                                     | Facebook App Manager                      | Yes                                       |
| com.facebook.system                                         | Facebook System Service                   | Yes                                       |
| com.facebook.services                                       | Facebook Services                         | Yes                                       |
| com.mygalaxy                                                | My Galaxy app (India)                     | Yes                                       |
| com.mygalaxy.service                                        | My Galaxy background services             | Yes                                       |
| com.samsung.android.aremojieditor                           | AR Emoji Editor                           | Yes                                       |
| com.sec.android.mimage.avatarstickers                       | Samsung Avatar Stickers                   | Yes                                       |
| com.samsung.android.app.omcagent                            | OMC Agent (carrier customization updater) | Yes                                       |
| com.samsung.android.kidsinstaller                           | Samsung Kids installer                    | Yes                                       |
| com.samsung.android.ipsgeofence                             | Samsung Geofencing service                | Yes                                       |
| com.samsung.SMT.lang\_pt\_br\_f00                           | Samsung Keyboard – Portuguese (Brazil)    | Yes (if not needed)                       |
| com.samsung.SMT.lang\_fr\_fr\_f00                           | Samsung Keyboard – French                 | Yes (if not needed)                       |
| com.samsung.SMT.lang\_de\_de\_f00                           | Samsung Keyboard – German                 | Yes (if not needed)                       |
| com.samsung.SMT.lang\_hi\_in\_f00                           | Samsung Keyboard – Hindi                  | Yes (if not needed)                       |
| com.samsung.SMT.lang\_id\_id\_f00                           | Samsung Keyboard – Indonesian             | Yes (if not needed)                       |
| com.samsung.SMT.lang\_it\_it\_f00                           | Samsung Keyboard – Italian                | Yes (if not needed)                       |
| com.samsung.SMT.lang\_es\_mx\_f00                           | Samsung Keyboard – Spanish (Mexico)       | Yes (if not needed)                       |
| com.samsung.SMT.lang\_ar\_ae\_m00                           | Samsung Keyboard – Arabic (UAE)           | Yes (if not needed)                       |
| com.samsung.SMT.lang\_pl\_pl\_f00                           | Samsung Keyboard – Polish                 | Yes (if not needed)                       |
| com.samsung.SMT.lang\_ru\_ru\_f00                           | Samsung Keyboard – Russian                | Yes (if not needed)                       |
| com.samsung.SMT.lang\_ru\_ru\_m00                           | Samsung Keyboard – Russian (Alt pack)     | Yes (if not needed)                       |
| com.samsung.SMT.lang\_ja\_jp\_m00                           | Samsung Keyboard – Japanese (Alt pack)    | Yes (if not needed)                       |
| com.samsung.SMT.lang\_es\_es\_f00                           | Samsung Keyboard – Spanish (Spain)        | Yes (if not needed)                       |
| com.samsung.SMT.lang\_ja\_jp\_f00                           | Samsung Keyboard – Japanese               | Yes (if not needed)                       |
| com.samsung.SMT.lang\_th\_th\_f00                           | Samsung Keyboard – Thai                   | Yes (if not needed)                       |
| com.samsung.SMT.lang\_es\_us\_f00                           | Samsung Keyboard – Spanish (US)           | Yes (if not needed)                       |
| com.samsung.SMT.lang\_vi\_vn\_f00                           | Samsung Keyboard – Vietnamese             | Yes (if not needed)                       |
| com.samsung.SMT.lang\_tr\_tr\_f00                           | Samsung Keyboard – Turkish                | Yes (if not needed)                       |
| com.google.android.tts                                      | Google Text-to-Speech                     | Risky (used by accessibility, maps, etc.) |
| com.google.android.gms.supervision                          | Google Family Link / Supervision          | Yes                                       |
| com.opera.max.oem                                           | Opera Max / Samsung Max (VPN, Data saver) | Yes                                       |
| com.samsung.ecomm.global.in                                 | Samsung Shop (India)                      | Yes                                       |
| com.samsung.android.mfi                                     | Samsung MFI (bloat/service)               | Yes                                       |
| com.facebook.katana                                         | Facebook main app                         | Yes                                       |
| com.sallysoft.srpol.edge.calendar                           | Edge Calendar (Sallysoft bloat app)       | Yes                                       |
| com.samsung.android.aremoji                                 | Samsung AR Emoji                          | Yes                                       |
| com.google.android.healthconnect.controller                 | Google Health Connect                     | Yes                                       |
