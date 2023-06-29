# Install Visual Studio Code Insiders
1. Clone visual studio code insiders

```bash
git clone https://aur.archlinux.org/visual-studio-code-insiders-bin.git
```

2. Update your system's package repositories by running the following command:

```bash
sudo pacman -Syu
```

3. Install the `fakeroot` package by executing the following command:

```bash
sudo pacman -S fakeroot
```

4. Change directory to visual-studio-code-insiders-bin

```bash
cd visual-studio-code-insiders-bin/
```

5. Compile the visual-studio-code-insiders-bin package and install
```
makepkg -si
```
