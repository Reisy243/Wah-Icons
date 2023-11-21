# Wah Icons theme
## Requisites
- [Teko fonts](https://fonts.google.com/specimen/Teko) or from [my deb package](https://panwah.sourceforge.io/repo/apt/pool/main/f/fonts-teko/fonts-teko-1.1_all.deb)
- (Optional) the repositorie
## Installation
- Debian based
```
sudo sh -c "$(curl -fsSL https://panwah.sourceforge.io/repo/apt/install.sh)"
sudo apt install icons-wah
```
- Manually in Debian based.
  * [Download lasted .deb](https://github.com/Reisy243/Wah-Icons/tags).
  * [Download teko deb](https://panwah.sourceforge.io/repo/apt/pool/main/f/fonts-teko/fonts-teko-1.1_all.deb).
```
cd (Directory with debs)
sudo apt install ./fonts-teko-(version)_all.deb
sudo apt install ./icons-wah-(version)_all.deb
```
- Other linux
## Download the files
[Download Teko fonts](https://fonts.google.com/specimen/Teko) (Click on download familly)
[Download the lasted icon theme](https://github.com/Reisy243/Wah-Icons/tags) (named "sourcecode"), dowload (Code/Download ZIP) or clone this repository
in the folder with the files
## Installing Teko fonts
extracting the font
```
mkdir teko
cd teko
mv ../Teko.zip .
unzip Teko.zip
cd ..
```
Installing in the system
```
mv teko /usr/share/fonts
```
## Intalling the icons theme
- for .tar.gz
```
tar -xvf Wah-Icons-(version).tar.gz
sudo cp -r Wah-Icons-(version) /usr/share/icons/Wah
```
- for .zip
```
unzip Wah-Icons-(version).zip
sudo cp -r Wah-Icons-(version) /usr/share/icons/Wah
```
- for the other .zip (Code/Download ZIP)
```
unzip Wah-Icons-main
sudo cp -r Wah-Icons-main /usr/share/icons/Wah
```
- for only one user and skip sudo
You can skip "sudo" in commands replacing /usr/share/icons/Wah an /usr/share/fonts by ~/.icons/wah and ~/.fonts respectively, if this folders don't exist you can create with:
```
mkdir ~/.icons ~/.fonts
```
