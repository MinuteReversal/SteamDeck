# Install Flutter
1. Clone the flutter
```bash
git clone https://github.com/flutter/flutter.git
```
2. Install reference libs
```bash
sudo pacman -S cmake
sudo pacman -S jsoncpp
sudo pacman -S libuv
sudo pacman -S rhash
sudo pacman -S clang
sudo pacman -S pango
sudo pacman -s glib2
sudo pacman -S sysprof
sudo pacman -S ninja
sudo pacman -S gtk3
sudo pacman -S linux-api-headers
sudo pacman -S glibc
sudo pacman -S harfbuzz
sudo pacman -S freetype2
sudo pacman -S libpng
sudo pacman -S util-linux-libs
sudo pacman -S util-linux
sudo pacman -S fribidi
sudo pacman -S cairo
sudo pacman -S lzo
sudo pacman -S pixman
sudo pacman -S gdk-pixbuf2
sudo pacman -S libcloudproviders
sudo pacman -S atk
sudo pacman -S dbus
sudo pacman -S gdk3
sudo pacman -S libx11
sudo pacman -S xorgproto
```
3. Flutter doctor
```
cd flutter/bin
flutter doctor -v
```
4. Flutter run
Change Director to project folder
```bash
flutter run
```
5. add flutter to path
```bash
vim ~/.bashrc
```
`.bashrc`
```.bashrc
export PATH=~/Documents/flutter/bin:$PATH
```

* [https://archlinux.org/packages/](https://archlinux.org/packages/)
