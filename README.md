# Debian Workstation

My special computer designed for technical or scientific applications.

> [!WARNING]
> This setup under construction!

## Debian Software Repositories

Add to `/etc/apt/sources.list`.
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

#### `apt-transport-https` ![apt-transport-https](https://img.shields.io/badge/debian-apt_transport_https-blue?style=flat-square)
[![apt-transport-https](https://img.shields.io/debian/v/apt-transport-https/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=apt-transport-https&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/apt-transport-https)

```bash
apt install apt-transport-https
```

#### `atril` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![atril](https://img.shields.io/debian/v/atril/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)

```bash
apt install atril
```
#### `audacious`  ![audacious](https://img.shields.io/badge/multimedia-audio-blue?style=flat-square)
[![audacious](https://img.shields.io/debian/v/audacious/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=audacious&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/audacious)

```bash
apt install audacious
```
#### `audacity`  ![audacity](https://img.shields.io/badge/multimedia-audio-blue?style=flat-square)
[![audacity](https://img.shields.io/debian/v/audacity/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=audacity&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/audacity)

```bash
apt install audacity
```
#### `blender`  ![blender](https://img.shields.io/badge/multimedia-3d-blue?style=flat-square)
[![blender](https://img.shields.io/debian/v/blender/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=blender&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/blender)

```bash
apt install blender
```
#### `btop`  ![btop](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![btop](https://img.shields.io/debian/v/btop/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=btop&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/btop)
```bash
apt install btop
```
#### `calibre`  ![calibre](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![calibre](https://img.shields.io/debian/v/calibre/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=calibre&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/calibre)
```bash
apt install calibre
```
#### `chromium`  ![chromium](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![chromium](https://img.shields.io/debian/v/chromium/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=chromium&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/chromium)
```bash
apt install chromium
```
#### `color-picker`  ![color-picker](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![color-picker](https://img.shields.io/debian/v/color-picker/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=color-picker&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/color-picker)
```bash
apt install color-picker
```
#### `cpu-x`  ![cpu-x](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![cpu-x](https://img.shields.io/debian/v/cpu-x/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=cpu-x&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/cpu-x)
```bash
apt install cpu-x
```
#### `curl`  ![curl](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![curl](https://img.shields.io/debian/v/curl/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=curl&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/curl)
```bash
apt install curl
```
#### `ebook-speaker`  ![ebook-speaker](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![ebook-speaker](https://img.shields.io/debian/v/ebook-speaker/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=ebook-speaker&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/ebook-speaker)
```bash
apt install ebook-speaker
```
#### `ffmpeg`  ![ffmpeg](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![ffmpeg](https://img.shields.io/debian/v/ffmpeg/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=ffmpeg&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/ffmpeg)
```bash
apt install ffmpeg
```
#### `filezilla`  ![filezilla](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![filezilla](https://img.shields.io/debian/v/filezilla/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=filezilla&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/filezilla)
```bash
apt install filezilla
```
#### `fonts-crosextra-caladea`  ![fonts-crosextra-caladea](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![fonts-crosextra-caladea](https://img.shields.io/debian/v/fonts-crosextra-caladea/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=fonts-crosextra-caladea&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/fonts-crosextra-caladea)
```bash
apt install fonts-crosextra-caladea
```
#### `fonts-inter` ![fonts-inter](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![fonts-inter](https://img.shields.io/debian/v/fonts-inter/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=fonts-inter&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/fonts-inter)
```bash
apt install fonts-inter
```
#### `fonts-crosextra-carlito`  ![fonts-crosextra-carlito](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![fonts-crosextra-carlito](https://img.shields.io/debian/v/fonts-crosextra-carlito/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=fonts-crosextra-carlito&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/fonts-crosextra-carlito)
```bash
apt install fonts-crosextra-carlito
```
#### `fonts-jetbrains-mono`  ![fonts-jetbrains-mono](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![fonts-jetbrains-mono](https://img.shields.io/debian/v/fonts-jetbrains-mono/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=fonts-jetbrains-mono&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/fonts-jetbrains-mono)
```bash
apt install fonts-jetbrains-mono
```
#### `font-manager`  ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![font-manager](https://img.shields.io/debian/v/font-manager/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=font-manager&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/font-manager)
```bash
apt install font-manager
```
#### `font-viewer` ![font-viewer](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![font-viewer](https://img.shields.io/debian/v/font-viewer/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=font-viewer&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/font-viewer)
```bash
apt install font-viewer
```
#### `freecad` ![freecad](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![freecad](https://img.shields.io/debian/v/freecad/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=freecad&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/freecad)
```bash
apt install freecad
```
#### `freeplane` ![freeplane](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![freeplane](https://img.shields.io/debian/v/freeplane/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=freeplane&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/freeplane)
```bash
apt install freeplane
```
#### `geany` ![geany](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![geany](https://img.shields.io/debian/v/geany/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=geany&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/geany)
```bash
apt install geany
```
#### `gdebi` ![gdebi](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![gdebi](https://img.shields.io/debian/v/gdebi/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=gdebi&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/gdebi)
```bash
apt install gdebi
```
#### `gimp` ![gimp](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![gimp](https://img.shields.io/debian/v/gimp/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=gimp&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/gimp)
```bash
apt install gimp
```
#### `git` ![git](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![git](https://img.shields.io/debian/v/git/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=git&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/git)
```bash
apt install git
```
#### `gnome-power-manager` ![gnome-power-manager](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![gnome-power-manager](https://img.shields.io/debian/v/gnome-power-manager/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=gnome-power-manager&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/gnome-power-manager)
```bash
apt install gnome-power-manager
```
#### `gnucash` ![gnucash](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![gnucash](https://img.shields.io/debian/v/gnucash/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=gnucash&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/gnucash)
```bash
apt install gnucash
```
#### `gparted` ![gparted](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![gparted](https://img.shields.io/debian/v/gparted/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=gparted&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/gparted)
```bash
apt install gparted
```
#### `gscan2pdf` ![gscan2pdf](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![gscan2pdf](https://img.shields.io/debian/v/gscan2pdf/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=gscan2pdf&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/gscan2pdf)
```bash
apt install gscan2pdf
```
#### `gsmartcontrol` ![gsmartcontrol](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![gsmartcontrol](https://img.shields.io/debian/v/gsmartcontrol/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=gsmartcontrol&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/gsmartcontrol)
```bash
apt install gsmartcontrol
```
#### `gstreamer1.0-vaapi` ![gstreamer1.0-vaapi](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![gstreamer1.0-vaapi](https://img.shields.io/debian/v/gstreamer1.0-vaapi/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=gstreamer1.0-vaapi&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/gstreamer1.0-vaapi)
```bash
apt install gstreamer1.0-vaapi
```
#### `gthumb` ![gthumb](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![gthumb](https://img.shields.io/debian/v/gthumb/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=gthumb&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/gthumb)
```bash
apt install gthumb
```
#### `hardinfo` ![hardinfo](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![hardinfo](https://img.shields.io/debian/v/hardinfo/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=hardinfo&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/hardinfo)
```bash
apt install hardinfo
```
#### `htop` ![htop](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![htop](https://img.shields.io/debian/v/htop/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=htop&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/htop)
```bash
apt install htop
```
#### `inkscape` ![inkscape](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=inkscape&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/inkscape)
```bash
apt install htop
```
#### `img2pdf` 
[![img2pdf](https://img.shields.io/debian/v/img2pdf/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=img2pdf&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/img2pdf)
```bash
apt install img2pdf
```
#### `kdenlive` ![kdenlive](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![kdenlive](https://img.shields.io/debian/v/kdenlive/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=kdenlive&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/kdenlive)
```bash
apt install kdenlive
```
#### `kicad` ![kicad](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![kicad](https://img.shields.io/debian/v/kicad/bookworm-backports?style=for-the-badge&logo=debian&logoColor=c70036&label=kicad&color=c70036 "Electronic schematic and PCB design software.")](https://packages.debian.org/bookworm-backports/kicad)
```bash
apt install kicad/bookworm-backports
```
#### `kraft` ![kraft](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![kraft](https://img.shields.io/debian/v/kraft/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=kraft&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/kraft)
```bash
apt install kraft
```
#### `krita` ![krita](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![krita](https://img.shields.io/debian/v/krita/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=krita&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/krita)
```bash
apt install krita
```
#### `libavcodec-extra` ![libavcodec-extra](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![libavcodec-extra](https://img.shields.io/debian/v/libavcodec-extra/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=libavcodec-extra&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/libavcodec-extra)
```bash
apt install libavcodec-extra
```
#### `librecad` ![librecad](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![librecad](https://img.shields.io/debian/v/librecad/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=librecad&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/librecad)
```bash
apt install librecad
```
#### `lshw` ![lshw](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![lshw](https://img.shields.io/debian/v/lshw/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=lshw&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/lshw)
```bash
apt install lshw
```
#### `neofetch` ![neofetch](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![neofetch](https://img.shields.io/debian/v/neofetch/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=neofetch&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/neofetch)
```bash
apt install neofetch
```
#### `neovim` ![neovim](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![neovim](https://img.shields.io/debian/v/neovim/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=neovim&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/neovim)
```bash
apt install neovim
```
#### `nvidia-driver` ![nvidia-driver](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![nvidia-driver](https://img.shields.io/debian/v/nvidia-driver/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=nvidia-driver&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/nvidia-driver)
```bash
apt install nvidia-driver
```
#### `nvidia-detect` ![nvidia-detect](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![nvidia-detect](https://img.shields.io/debian/v/nvidia-detect/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=nvidia-detect&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/nvidia-detect)
```bash
apt install nvidia-detect
```
#### `ocrmypdf` ![ocrmypdf](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![ocrmypdf](https://img.shields.io/debian/v/ocrmypdf/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=ocrmypdf&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/ocrmypdf)
```bash
apt install ocrmypdf
```
#### `obsstudio` ![obsstudio](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![obsstudio](https://img.shields.io/debian/v/obsstudio/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=obsstudio&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/obsstudio)
```bash
apt install obsstudio
```
#### `openscad` ![openscad](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![openscad](https://img.shields.io/debian/v/openscad/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=openscad&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/openscad)
```bash
apt install openscad
```
#### `papirus-icon-theme` ![papirus-icon-theme](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![papirus-icon-theme](https://img.shields.io/debian/v/papirus-icon-theme/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=papirus-icon-theme&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/papirus-icon-theme)
```bash
apt install papirus-icon-theme
```
#### `partitionmanager` ![partitionmanager](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![partitionmanager](https://img.shields.io/debian/v/partitionmanager/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=partitionmanager&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/partitionmanager)
```bash
apt install partitionmanager
```
#### `pdfarranger` ![pdfarranger](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![pdfarranger](https://img.shields.io/debian/v/pdfarranger/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=pdfarranger&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/pdfarranger)
```bash
apt install pdfarranger
```
#### `pdfsam` ![pdfsam](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![pdfsam](https://img.shields.io/debian/v/pdfsam/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=pdfsam&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/pdfsam)
```bash
apt install pdfsam
```
#### `pdftk` ![pdftk](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![pdftk](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=pdftk&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/pdftk)
```bash
apt install pdftk
```
#### `photocollage` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `poppler-utils` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `printer-driver-all`  ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```

#### `rar` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)

[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `signal` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `scribus` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `slic3r` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `sweethome3d` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `tesseract-ocr` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `terminator` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `thunar` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `thunderbird` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### ` ttf-mscorefonts-installer` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `ufw` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `unrar` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `usbview` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `vlc` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `wifi-qr` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```
#### `wget` ![atril](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![inkscape](https://img.shields.io/debian/v/inkscape/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=atril&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/atril)
```bash
apt install atril
```

## Non-Debian Software Repositories

#### `chrome`
#### `gh` ![atril](https://img.shields.io/badge/github_cli-git?style=flat-square)
```bash
wget -qO- https://cli.github.com/packages/githubcli-archive-keyring.gpg | tee /etc/apt/keyrings/githubcli-archive-keyring.gpg > /dev/null \
&& chmod go+r /etc/apt/keyrings/githubcli-archive-keyring.gpg \
&& echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | tee /etc/apt/sources.list.d/github-cli.list > /dev/null
&& apt update
&& apt install gh
```
#### `odafileconverter`
#### `pandoc`
#### `typora`
```bash
curl https://typora.io/linux/public-key.asc | gpg --dearmor > /etc/apt/keyrings/typora.gpg > /dev/null

chmod go+r /etc/apt/keyrings/typora.gpg

echo "deb [arch=amd64 signed-by=/usr/share/keyrings/typora.gpg] https://typora.io/linux ./" | tee /etc/apt/sources.list.d/typora.list > /dev/null

apt update
apt install typora
```
#### `via`
#### `vscode`
#### `zotero`

## Notes

Delete Gnome games.

```bash
apt purge gnome-games
```

## Credits

