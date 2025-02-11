# termux-windows-11
Install windows 11 using termux in android

# Requirements 
- 15 GB storage

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
