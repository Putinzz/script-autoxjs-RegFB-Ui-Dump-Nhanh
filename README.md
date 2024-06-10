# script-autoxjs
js này chạy thẳng trên android 


memuc -i 0 adb shell settings put secure enabled_accessibility_services org.autojs.autoxjs.v6/com.stardust.autojs.core.accessibility.AccessibilityService

memuc -i 0 execcmd "am start -n org.autojs.autoxjs.v6/org.autojs.autojs.external.open.RunIntentActivity -d file:///storage/emulated/0/Download/regfb.js -t text/javascript"

adb -s ce06171628a2071c02 "am start -n org.autojs.autojs/.external.open.RunIntentActivity -d file://sdcard/Downloads/regfb.js -t text/javascript"

Bác copy script vào download\memu download , sau đó chạy 2 cmd trên là chạy , à phải cái autoxjs bản 6.5.9 nhé .
