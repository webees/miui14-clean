# miui14-clean

```
./adb.exe push boot.img /sdcard/boot.img
./adb.exe push Magisk-v26.0.apk /sdcard/Magisk-v26.0.apk
./adb.exe pull /sdcard/Download/magisk_patched-26000_m5RrF.img E:\
./fastboot.exe flash boot magisk_patched-26000_m5RrF.img

./adb.exe shell pm list packages

adb shell pm disable-user com.xiaomi.gamecenter
adb shell pm uninstall --user 0 cn.wps.moffice_eng.xiaomi.lite
adb shell pm uninstall --user 0 com.android.bips
adb shell pm uninstall --user 0 com.android.browser
adb shell pm uninstall --user 0 com.android.calendar
adb shell pm uninstall --user 0 com.android.deskclock
adb shell pm uninstall --user 0 com.android.fileexplorer
adb shell pm uninstall --user 0 com.android.providers.calendar
adb shell pm uninstall --user 0 com.android.providers.downloads
adb shell pm uninstall --user 0 com.android.providers.downloads.ui
adb shell pm uninstall --user 0 com.android.thememanager
adb shell pm uninstall --user 0 com.android.traceur
adb shell pm uninstall --user 0 com.android.wallpaper.livepicker
adb shell pm uninstall --user 0 com.android.wallpaperbackup
adb shell pm uninstall --user 0 com.android.wallpapercropper
adb shell pm uninstall --user 0 com.android.wallpaperpicker
adb shell pm uninstall --user 0 com.google.android.marvin.talkback
adb shell pm uninstall --user 0 com.goodix.gftest
adb shell pm uninstall --user 0 com.miui.accessibility
adb shell pm uninstall --user 0 com.miui.analytics
adb shell pm uninstall --user 0 com.miui.bugreport
adb shell pm uninstall --user 0 com.miui.cloudbackup
adb shell pm uninstall --user 0 com.miui.cloudservice
adb shell pm uninstall --user 0 com.miui.gallery
adb shell pm uninstall --user 0 com.miui.greenguard
adb shell pm uninstall --user 0 com.miui.huanji
adb shell pm uninstall --user 0 com.miui.hybrid
adb shell pm uninstall --user 0 com.miui.miservice
adb shell pm uninstall --user 0 com.miui.nextpay
adb shell pm uninstall --user 0 com.miui.notes
adb shell pm uninstall --user 0 com.miui.personalassistant
adb shell pm uninstall --user 0 com.miui.player
adb shell pm uninstall --user 0 com.miui.securityadd
adb shell pm uninstall --user 0 com.miui.securitycore
adb shell pm uninstall --user 0 com.miui.securityinputmethod
adb shell pm uninstall --user 0 com.miui.systemAdSolution
adb shell pm uninstall --user 0 com.miui.translation.kingsoft
adb shell pm uninstall --user 0 com.miui.translation.xmcloud
adb shell pm uninstall --user 0 com.miui.translation.youdao
adb shell pm uninstall --user 0 com.miui.video
adb shell pm uninstall --user 0 com.miui.voiceassist
adb shell pm uninstall --user 0 com.miui.weather2
adb shell pm uninstall --user 0 com.miui.yellowpage
adb shell pm uninstall --user 0 com.mobiletools.systemhelper
adb shell pm uninstall --user 0 com.sina.weibo
adb shell pm uninstall --user 0 com.sohu.inputmethod.sogou.xiaomi
adb shell pm uninstall --user 0 com.xiaomi.aiasst.service
adb shell pm uninstall --user 0 com.xiaomi.aiasst.vision
adb shell pm uninstall --user 0 com.xiaomi.gamecenter
adb shell pm uninstall --user 0 com.xiaomi.gamecenter.sdk.service
adb shell pm uninstall --user 0 com.xiaomi.gnss.p
```
