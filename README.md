# Debian Workstation

My special computer designed for technical or scientific applications.

## Debian Software Repositories

Add to `/etc/apt/sources.list`:

```bash
# deb cdrom:[Debian GNU/Linux 12.6.0 _Bookworm_ - Official amd64 DVD Binary-1 with firmware 20240629-10:19]/ bo>

deb http://deb.debian.org/debian/ bookworm main non-free-firmware contrib non-free
deb-src http://deb.debian.org/debian/ bookworm main non-free-firmware contrib non-free

deb http://security.debian.org/debian-security bookworm-security main non-free-firmware contrib non-free
deb-src http://security.debian.org/debian-security bookworm-security main non-free-firmware contrib non-free

# bookworm-updates, to get updates before a point release is made;
# see https://www.debian.org/doc/manuals/debian-reference/ch02.en.html#_updates_and_backports
deb http://deb.debian.org/debian/ bookworm-updates main non-free-firmware contrib non-free
deb-src http://deb.debian.org/debian/ bookworm-updates main non-free-firmware contrib non-free

# debian-backports
deb http://deb.debian.org/debian bookworm-backports main non-free-firmware contrib non-free
deb-src http://deb.debian.org/debian bookworm-backports main non-free-firmware contrib non-free
```
### List of Debian Sofware

`atril`
: 
`audacious`
:
`audacity`
:
`blender`
:
`btop`
:
`calibre`
:
`chromium`
:
`color-picker`
:
`cpu-x`
:
`curl`            
:
`ebook-speaker`
:
`ffmpeg`
:
`filezilla`
:
`fonts-crosextra-caladea`
:
`fonts-crosextra-carlito`
:
`fonts-jetbrains-mono`
:
`font-manager`
:
`font-viewer`
:
`freecad`
:
`freeplane`
:
`geany`
:
`gdebi`
:
`gimp`
:
`git`             
:
`gnome-power-manager`
:
`gnucash`
:
`gparted`         
:
`gscan2pdf`
:
`gsmartcontrol`
:
`gstreamer1.0-vaapi`
:
`gthumb`
:
`hardinfo`
:
`htop`
:
`inkscape`
: [![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=inkscape&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/inkscape) 
`img2pdf` 
:
`kdenlive`
:
`kicad`
: [![kicad](https://img.shields.io/debian/v/kicad/bookworm-backports?style=for-the-badge&logo=debian&logoColor=c70036&label=kicad&color=c70036 "Electronic schematic and PCB design software.")](https://packages.debian.org/bookworm-backports/kicad)

```bash
apt install kicad/bookworm-backports
```
`kraft`
:
`krita`
:
`libavcodec-extra`
:
`librecad`
:
`neofetch`
:
`neovim`
:
`nvidia-driver`
:
`nvidia-detect`
:
`ocrmypdf`
:
`obsstudio`
:
`openscad`
:
`papirus-icon-theme`
:
`partitionmanager`
:
`pdfarranger`
:
`pdfsam`
:
`pdftk`
:
`photocollage`
:
`poppler-utils`
:
`rar`
:
`signal`
:
`scribus`
:
`slic3r`
:
`sweethome3d`
:
`tesseract-ocr`
:
`terminator`
:
`thunar`
:
`thunderbird`
:
` ttf-mscorefonts-installer`
:
`ufw`
:
`unrar`
:
`usbview`
:
`vlc`
:
`wifi-qr`
:
`wget`
:

## Non-Debian Software Repositories


`chrome`
:
`odafileconverter`
:
`pandoc`
:
`typora`
:
`via`
:
`vscode`
:
`zotero`
:

## Notes

Delete Gnome game:

```bash
apt purge gnome-games
```

## Credits

