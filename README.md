# miui14-clean

```
adb install Edge.apk
adb install Gboard.apk
adb install SDmaid.apk
adb install Magisk-v26.1.apk
adb push boot.img /sdcard/boot.img
adb pull /sdcard/Download/magisk_patched-26000_m5RrF.img E:\
fastboot flash boot magisk_patched-26000_m5RrF.img
```

```
# adb.exe shell pm list packages
# adb shell pm disable-user com.xiaomi.gamecenter

adb shell pm uninstall --user 0 cn.wps.moffice_eng.xiaomi.lite
adb shell pm uninstall --user 0 com.Qunar
adb shell pm uninstall --user 0 com.UCMobile
adb shell pm uninstall --user 0 com.achievo.vipshop
adb shell pm uninstall --user 0 com.android.bips
adb shell pm uninstall --user 0 com.android.browser
adb shell pm uninstall --user 0 com.android.calendar
adb shell pm uninstall --user 0 com.android.cellbroadcastreceiver
adb shell pm uninstall --user 0 com.android.deskclock
adb shell pm uninstall --user 0 com.android.email
adb shell pm uninstall --user 0 com.android.fileexplorer
adb shell pm uninstall --user 0 com.android.midrive
adb shell pm uninstall --user 0 com.android.printspooler
adb shell pm uninstall --user 0 com.android.providers.calendar
adb shell pm uninstall --user 0 com.android.providers.downloads
adb shell pm uninstall --user 0 com.android.providers.downloads.ui
adb shell pm uninstall --user 0 com.android.quicksearchbox
adb shell pm uninstall --user 0 com.android.soundrecorder
adb shell pm uninstall --user 0 com.android.thememanager
adb shell pm uninstall --user 0 com.android.traceur
adb shell pm uninstall --user 0 com.android.wallpaper
adb shell pm uninstall --user 0 com.android.wallpaper.livepicker
adb shell pm uninstall --user 0 com.android.wallpapercropper
adb shell pm uninstall --user 0 com.android.wallpaperpicker
adb shell pm uninstall --user 0 com.baidu.BaiduMap
adb shell pm uninstall --user 0 com.baidu.input_mi
adb shell pm uninstall --user 0 com.baidu.searchbox
adb shell pm uninstall --user 0 com.dragon.read
adb shell pm uninstall --user 0 com.duokan.phone.remotecontroller
adb shell pm uninstall --user 0 com.duokan.reader
adb shell pm uninstall --user 0 com.eg.android.AlipayGphone
adb shell pm uninstall --user 0 com.fingerprints.sensortesttool
adb shell pm uninstall --user 0 com.goodix.gftest
adb shell pm uninstall --user 0 com.google.android.marvin.talkback
adb shell pm uninstall --user 0 com.huaqin.factory
adb shell pm uninstall --user 0 com.iflytek.inputmethod.miui
adb shell pm uninstall --user 0 com.mfashiongallery.emag
adb shell pm uninstall --user 0 com.mi.AutoTest
adb shell pm uninstall --user 0 com.mi.android.globalminusscreen
adb shell pm uninstall --user 0 com.mi.health
adb shell pm uninstall --user 0 com.mi.liveassistant
adb shell pm uninstall --user 0 com.milink.service
adb shell pm uninstall --user 0 com.mipay.wallet
adb shell pm uninstall --user 0 com.miui.accessibility
adb shell pm uninstall --user 0 com.miui.analytics
adb shell pm uninstall --user 0 com.miui.audioeffect
adb shell pm uninstall --user 0 com.miui.audiomonitor
adb shell pm uninstall --user 0 com.miui.bugreport
adb shell pm uninstall --user 0 com.miui.calculator
adb shell pm uninstall --user 0 com.miui.carlink
adb shell pm uninstall --user 0 com.miui.cit
adb shell pm uninstall --user 0 com.miui.cleanmaster
adb shell pm uninstall --user 0 com.miui.cloudbackup
adb shell pm uninstall --user 0 com.miui.cloudservice
adb shell pm uninstall --user 0 com.miui.cloudservice.sysbase
adb shell pm uninstall --user 0 com.miui.compass
adb shell pm uninstall --user 0 com.miui.contentcatcher
adb shell pm uninstall --user 0 com.miui.contentextension
adb shell pm uninstall --user 0 com.miui.daemon
adb shell pm uninstall --user 0 com.miui.fm
adb shell pm uninstall --user 0 com.miui.fmservice
adb shell pm uninstall --user 0 com.miui.gallery
adb shell pm uninstall --user 0 com.miui.greenguard
adb shell pm uninstall --user 0 com.miui.health
adb shell pm uninstall --user 0 com.miui.huanji
adb shell pm uninstall --user 0 com.miui.huanjicom.miui.huanji
adb shell pm uninstall --user 0 com.miui.hybrid
adb shell pm uninstall --user 0 com.miui.hybrid.accessory
adb shell pm uninstall --user 0 com.miui.klo.bugreport
adb shell pm uninstall --user 0 com.miui.maintenancemode
adb shell pm uninstall --user 0 com.miui.micloudsync
adb shell pm uninstall --user 0 com.miui.miservice
adb shell pm uninstall --user 0 com.miui.mishare.connectivity
adb shell pm uninstall --user 0 com.miui.misound
adb shell pm uninstall --user 0 com.miui.miwallpaper
adb shell pm uninstall --user 0 com.miui.newhome
adb shell pm uninstall --user 0 com.miui.newmidrive
adb shell pm uninstall --user 0 com.miui.nextpay
adb shell pm uninstall --user 0 com.miui.notes
adb shell pm uninstall --user 0 com.miui.personalassistant
adb shell pm uninstall --user 0 com.miui.phrase
adb shell pm uninstall --user 0 com.miui.player
adb shell pm uninstall --user 0 com.miui.screenrecorder
adb shell pm uninstall --user 0 com.miui.securityadd
adb shell pm uninstall --user 0 com.miui.securitycore
adb shell pm uninstall --user 0 com.miui.securityinputmethod
adb shell pm uninstall --user 0 com.miui.smarttravel
adb shell pm uninstall --user 0 com.miui.smsextra
adb shell pm uninstall --user 0 com.miui.systemAdSolution
adb shell pm uninstall --user 0 com.miui.touchassistant
adb shell pm uninstall --user 0 com.miui.translation.kingsoft
adb shell pm uninstall --user 0 com.miui.translation.xmcloud
adb shell pm uninstall --user 0 com.miui.translation.youdao
adb shell pm uninstall --user 0 com.miui.translationservice
adb shell pm uninstall --user 0 com.miui.userguide
adb shell pm uninstall --user 0 com.miui.video
adb shell pm uninstall --user 0 com.miui.virtualsim
adb shell pm uninstall --user 0 com.miui.voiceassist
adb shell pm uninstall --user 0 com.miui.voicetrigger
adb shell pm uninstall --user 0 com.miui.vsimcore
adb shell pm uninstall --user 0 com.miui.weather2
adb shell pm uninstall --user 0 com.miui.wmsvc
adb shell pm uninstall --user 0 com.miui.xiaomi.payment
adb shell pm uninstall --user 0 com.miui.yellowpage
adb shell pm uninstall --user 0 com.mobiletools.systemhelper
adb shell pm uninstall --user 0 com.modemdebug
adb shell pm uninstall --user 0 com.qiyi.video
adb shell pm uninstall --user 0 com.sina.weibo
adb shell pm uninstall --user 0 com.smile.gifmaker
adb shell pm uninstall --user 0 com.sohu.inputmethod.sogou.xiaomi
adb shell pm uninstall --user 0 com.ss.android.article.news
adb shell pm uninstall --user 0 com.ss.android.ugc.aweme
adb shell pm uninstall --user 0 com.tencent.mtt
adb shell pm uninstall --user 0 com.tencent.qqlive
adb shell pm uninstall --user 0 com.tencent.soter.soterserver
adb shell pm uninstall --user 0 com.unionpay.tsmservice.mi
adb shell pm uninstall --user 0 com.xiaomi.ab
adb shell pm uninstall --user 0 com.xiaomi.aiasst.service
adb shell pm uninstall --user 0 com.xiaomi.aiasst.vision
adb shell pm uninstall --user 0 com.xiaomi.bluetooth
adb shell pm uninstall --user 0 com.xiaomi.gamecenter
adb shell pm uninstall --user 0 com.xiaomi.gamecenter.sdk.service
adb shell pm uninstall --user 0 com.xiaomi.gnss.polaris
adb shell pm uninstall --user 0 com.xiaomi.joyose
adb shell pm uninstall --user 0 com.xiaomi.jr
adb shell pm uninstall --user 0 com.xiaomi.macro
adb shell pm uninstall --user 0 com.xiaomi.mi_connect_service
adb shell pm uninstall --user 0 com.xiaomi.micloud.sdk
adb shell pm uninstall --user 0 com.xiaomi.midrop
adb shell pm uninstall --user 0 com.xiaomi.migameservice
adb shell pm uninstall --user 0 com.xiaomi.miplay_client
adb shell pm uninstall --user 0 com.xiaomi.mircs
adb shell pm uninstall --user 0 com.xiaomi.mirror
adb shell pm uninstall --user 0 com.xiaomi.mitunes
adb shell pm uninstall --user 0 com.xiaomi.pass
adb shell pm uninstall --user 0 com.xiaomi.payment
adb shell pm uninstall --user 0 com.xiaomi.powerchecker
adb shell pm uninstall --user 0 com.xiaomi.scanner
adb shell pm uninstall --user 0 com.xiaomi.shop
adb shell pm uninstall --user 0 com.xiaomi.simactivate.service
adb shell pm uninstall --user 0 com.xiaomi.smarthome
adb shell pm uninstall --user 0 com.xiaomi.vipaccount
adb shell pm uninstall --user 0 com.xiaomi.xmsf
adb shell pm uninstall --user 0 com.xiaomi.xmsfkeeper
adb shell pm uninstall --user 0 com.xiaomi.youpin
adb shell pm uninstall --user 0 com.ximalaya.ting.android
adb shell pm uninstall --user 0 com.xunmeng.pinduoduo
adb shell pm uninstall --user 0 com.zhihu.android
adb shell pm uninstall --user 0 tv.danmaku.bili

pause
```
