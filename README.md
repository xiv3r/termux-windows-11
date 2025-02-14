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
> install dependencies
```
termux-setup-storage && pkg update && pkg upgrade -y && pkg install axel proot p7zip pulseaudio -y
```
> download the file
```
axel -a -n 1 https://github.com/Android-PowerUser/Windroid_11/releases/download/2023.07.29/Win11.7z.001
axel -a -n 1 https://github.com/Android-PowerUser/Windroid_11/releases/download/2023.07.29/Win11.7z.002
axel -a -n 1 https://github.com/Android-PowerUser/Windroid_11/releases/download/2023.07.29/Win11.7z.003
```
> extract the file
```
7z x Win11.7z.001 -o$HOME
```
> add permission
```
chmod +x Win11
cp Win11 $PREFIX/bin/win11
chmod +x $PREFIX/bin/win11
```
> run
```
bash Win11
```
or
```
win11
```

# Documentation
Visit: [https://github.com/Android-PowerUser/Windroid_11](https://github.com/Android-PowerUser/Windroid_11)

Credits => [Android-PowerUser](https://github.com/Android-PowerUser/Windroid_11)
