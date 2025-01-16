# Works
## Android Studio
```
Android Studio Ladybug Feature Drop | 2024.2.2
Build #AI-242.23726.103.2422.12816248, built on December 17, 2024
Runtime version: 21.0.4+-12422083-b607.1 amd64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
Toolkit: sun.awt.X11.XToolkit
Linux 6.11.0-13-generic
GC: G1 Young Generation, G1 Concurrent GC, G1 Old Generation
Memory: 4096M
Cores: 8
Registry:
  ide.experimental.ui=true
  i18n.locale=
Current Desktop: ubuntu:GNOME
```

## AVD
```
hardware: Pixel 8 Pro
```

## android:
```
API: 31
version: Android 12.0 ("S")
architecture: x86_64
```

## rootAVD
```
commit: 613caa44371f85e1a461bc030e07ddc2d71afe32
link: https://gitlab.com/newbit/rootAVD/-/tree/613caa44371f85e1a461bc030e07ddc2d71afe32

command: ./rootAVD.sh system-images/android-31/google_apis/x86_64/ramdisk.img
```

## LSPosed
```
version: 1.9.2 (7024) - Zygisk
download: https://github.com/LSPosed/LSPosed/releases/tag/v1.9.2
```
### install with Magisk!
```
adb push LSPosed-v1.9.2-7024-zygisk-release.zip /sdcard/Download/
# Open in Magisk -> Install Module: navigate to Downloads
```

then: post install step (on Host)
```
unzip LSPosed-v1.9.2-7024-zygisk-release.zip
cd LSPosed-v1.9.2-7024-zygisk-release
adb install ./manager.apk
```
