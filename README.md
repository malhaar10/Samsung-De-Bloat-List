::Debloat list for Samsung phones

::REQUIREMENTS-> platform tools, developermode

::Install platfor-tools-> refer to this video "https://youtu.be/F_XI-w6xDkM"
::Credits to the video's owner

::Enable developer mode-> Settings>Software Information>Build Number
::Keep talling build number rapidly until developer mode is enabled
::In developer mode, enable USB debugging
::Connect to computer via usb cable

::Navigate to/Open platform-tools folder and open amd there
::Type "adb devices"
::Once the device shows up, type "adb shell"
::Copy and paste this list in adb shell
::Press enter once to remove the last item
::Remember to exit adb shell

::Command for manually removing items> "pm uninstall --user 0 'package_name'"

pm uninstall --user 0 com.google.android.adservices.api
pm uninstall --user 0 com.samsung.android.mapsagent
pm uninstall -- user 0 com.samsung.android.app.camera.sticker.facearavatar.preload
pm uninstall --user 0 com.google.android.gms.location.history
pm uninstall --user 0 com.android.hotwordenrollment.xgoogle
pm uninstall --user 0 com.android.hotwordenrollment.okgoogle
pm uninstall --user 0 com.google.android.apps.tachyon
pm uninstall --user 0 com.swiftkey.swiftkeyconfigurator
pm uninstall --user 0 com.touchtype.swiftkey
pm uninstall --user 0 com.microsoft.skydrive
pm uninstall --user 0 com.samsung.android.mdx
pm uninstall --user 0 com.microsoft.appmanager
pm uninstall --user 0 com.google.android.feedback
pm uninstall --user 0 com.google.android.googlequicksearchbox
pm uninstall --user 0 com.google.android.apps.messaging
pm uninstall --user 0 com.facebook.appmanager
pm uninstall --user 0 com.facebook.system
pm uninstall --user 0 com.facebook.services
pm uninstall --user 0 com.mygalaxy
pm uninstall --user 0 com.mygalaxy.service
pm uninstall --user 0 com.samsung.android.app.omcagent
pm uninstall --user 0 com.samsung.android.kidsinstaller
pm uninstall --user 0 com.samsung.android.ipsgeofence
pm uninstall --user 0 com.samsung.SMT.lang_pt_br_f00
pm uninstall --user 0 com.samsung.SMT.lang_fr_fr_f00
pm uninstall --user 0 com.samsung.SMT.lang_de_de_f00
pm uninstall --user 0 com.samsung.SMT.lang_hi_in_f00
pm uninstall --user 0 com.samsung.SMT.lang_id_id_f00
pm uninstall --user 0 com.samsung.SMT.lang_it_it_f00
pm uninstall --user 0 com.samsung.SMT.lang_es_mx_f00
pm uninstall --user 0 com.samsung.SMT.lang_ar_ae_m00
pm uninstall --user 0 com.samsung.SMT.lang_pl_pl_f00
pm uninstall --user 0 com.samsung.SMT.lang_ru_ru_f00
pm uninstall --user 0 com.samsung.SMT.lang_es_es_f00
pm uninstall --user 0 com.samsung.SMT.lang_th_th_f00
pm uninstall --user 0 com.samsung.SMT.lang_es_us_f00
pm uninstall --user 0 com.samsung.SMT.lang_vi_vn_f00
pm uninstall --user 0 com.google.android.tts
pm uninstall --user 0 com.google.android.gms.supervision
