# [youtube-dl-gui](https://github.com/jely2002/youtube-dl-gui)

see the [releases](https://github.com/ryanfortner/youtube-dl-gui_arm/releases/latest) tab for binaries in the form of AppImage.

### Compile instructions
Install npm using [pi apps](https://github.com/Botspot/pi-apps)
```
git clone https://github.com/jely2002/youtube-dl-gui
cd youtube-dl-gui

npm install
npx electron-builder --linux --armv7l #32bit compile command
npx electron-builder --linux --arm64 #64bit compile command
```
