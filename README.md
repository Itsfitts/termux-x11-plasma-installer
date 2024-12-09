# About this project
Run KDE Plasma 5.26 smoothly in termux-x11
! [](https://ghproxy.com/github.com/kde-yyds/termux-x11-plasma-installer/raw/master/1.jpg)
FPS stabilizes 60 frames
KDE Plasma is running in archlinux.
But Kwin is another debian11 old Kwin
Also retained is the xrender mixer backend
So the software rendering is still very smooth.
# changelog
2023/2/12 Updated the LD_PRELOAD environment variable emptying method, fixed the old version of Android can not start proot issue
If it has been installed before, you can fix it with this instruction.
```
sed -i 's/env LD_PRELOAD=/env -u LD_PRELOAD/g' /data/data/com.termux/files/home/containers/scripts/*
```
# Use tutorials
## Install termux and termux-x11
termux：<https://ghproxy.com/github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_arm64-v8a.apk>
termux-x11：<https://ghproxy.com/github.com/kde-yyds/termux-x11-plasma-installer/raw/master/termux-x11.apk>
## Other
1. It is recommended to lower the screen resolution of the mobile phone to ensure smooth software rendering and not drop frames
2. Open termux-x11, press Preferences in the notification bar, and remove the Show additional keyboard tick
## Installation
Enter termux
Run first if you don't change the source.
```
termux-change-repo
```
Then run
```
curl -L https://ghproxy.com/github.com/kde-yyds/termux-x11-plasma-installer/raw/master/install.sh | bash
```

Note: If the installation process is interrupted, you can rerun it, and support the installation from the interrupted place.
! [](https://ghproxy.com/github.com/kde-yyds/termux-x11-plasma-installer/raw/master/2.jpg)

# About this project
Running KDE Plasma 5.26 smoothly in termux-x11
![](https://ghproxy.com/github.com/kde-yyds/termux-x11-plasma-installer/raw/master/1.jpg)
FPS stabilized at 60 fps  
Because KDE Plasma is running in archlinux.  
But kwin is another old kwin for debian11.  
It still has the xrender mixer backend.  
so the software rendering is still very smooth and fluid.
# changelog
2023/2/12 Updated the LD_PRELOAD environment variable clearing method, fixed the problem that old android versions can't start proot.  
If you have already installed it, you can use this command to fix it.
```
sed -i 's/env LD_PRELOAD=/env -u LD_PRELOAD/g' /data/data/com.termux/files/home/containers/scripts/*
```
## Tutorial on usage
## Installing termux and termux-x11
termux: <https://ghproxy.com/github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_arm64-v8a.apk>  
termux-x11: <https://ghproxy.com/github.com/kde-yyds/termux-x11-plasma-installer/raw/master/termux-x11.apk>
## Other
1. It is recommended to turn down the screen resolution of your phone to ensure smooth rendering of the software without dropping frames  
2. Open termux-x11, press Preferences in the notification bar, and remove the Show additional keyboard checkbox.
## Installation
Enter termux  
If you haven't changed the source, run it first.
``
termux-change-repo
``
Then run
``
curl -L https://ghproxy.com/github.com/kde-yyds/termux-x11-plasma-installer/raw/master/install.sh | bash
```

Note: If the installation process is interrupted, just re-run it, it is supported to continue the installation from where it was interrupted
![](https://ghproxy.com/github.com/kde-yyds/termux-x11-plasma-installer/raw/master/2.jpg)

Translated with DeepL https://www.deepl.com/app/?utm_source=android&utm_medium=app&utm_campaign=share-translation