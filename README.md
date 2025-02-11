# termux-windows-11
Install windows 11 using termux in android

# Requirements 
- Rootless
- Arm64 only
- 4GB RAM
- 20GB internal storage
- [Termux](https://github.com/termux/termux-app/releases/download/v0.119.0-beta.1/termux-app_v0.119.0-beta.1+apt-android-7-github-debug_universal.apk)
- [Termux Widget](https://github.com/termux/termux-widget/releases/download/v0.14.0/termux-widget-app_v0.14.0+github.debug.apk)
- [VNC Viewer](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android)

# Installation 
```
termux-setup-storage && pkg update && pkg upgrade -y && pkg install proot p7zip pulseaudio wget -y
```
```
cd storage/downloads
```
```
wget https://github.com/Android-PowerUser/Windroid_11/releases/download/2023.07.29/Win11.7z.001 https://github.com/Android-PowerUser/Windroid_11/releases/download/2023.07.29/Win11.7z.002 https://github.com/Android-PowerUser/Windroid_11/releases/download/2023.07.29/Win11.7z.003
```
```
7z x ./Win11.7z.001 -o$HOME/
cd $HOME/
chmod +x ./Win11
./Win11
```

# Documentation
Visit: [https://github.com/Android-PowerUser/Windroid_11](https://github.com/Android-PowerUser/Windroid_11)

Credits => [Android-PowerUser](https://github.com/Android-PowerUser/Windroid_11)
