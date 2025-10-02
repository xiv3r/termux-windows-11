# termux-windows-11
Install windows 11 using termux on android

<div align="center">
  
<img width="90%" height="30%" src="https://github.com/xiv3r/termux-windows-11/blob/main/src/landscape.jpg">
<img height="90%" width="30%" src="https://github.com/xiv3r/termux-windows-11/blob/main/src/portrait.jpg">
</div>

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
apt update && pkg upgrade -y && pkg install axel proot p7zip pulseaudio -y
```
> download the file
```
axel https://github.com/xiv3r/termux-windows-11/releases/download/windows-11/Win11.7z.001
axel https://github.com/xiv3r/termux-windows-11/releases/download/windows-11/Win11.7z.002
axel https://github.com/xiv3r/termux-windows-11/releases/download/windows-11/Win11.7z.003

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
