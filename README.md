# Debian Workstation

My personal computer desktop and/or laptop designed for technical or scientific applications.

Visit `https://cdimage.debian.org/debian-cd/current/amd64/bt-dvd/`. Download [the image](https://cdimage.debian.org/debian-cd/current/amd64/bt-dvd/debian-12.7.0-amd64-DVD-1.iso.torrent).

```bash
root@syenasweta:/home/naf/Downloads/debian# ls
debian-12.7.0-amd64-DVD-1.iso  SHA256SUMS	SHA256SUMS.sign  SHA512SUMS  SHA512SUMS.sign
```

## Verify the Image

```bash
root@syenasweta:/home/naf/Downloads/debian# gpg --keyserver keyring.debian.org --recv-keys DA87E80D6294BE9B
root@syenasweta:/home/naf/Downloads/debian# gpg --list-keys | less
root@syenasweta:/home/naf/Downloads/debian# gpg --list-keys DA87E80D6294BE9B
root@syenasweta:/home/naf/Downloads/debian# gpg --verify SHA512SUMS.sign SHA512SUMS
root@syenasweta:/home/naf/Downloads/debian# sha512sum --check --ignore-missing SHA512SUMS
```



## Write a USB/CD/DVD/BD Image to a USB Flash Drive

```bash
root@syenasweta:/home/naf/Downloads/debian# dd if=debian-12.7.0-amd64-DVD-1.iso of=/dev/sdb bs=1M status=progress oflag=sync
```



> [!WARNING]
> This setup under construction!

## Debian Software Repositories

As `root`, add to `/etc/apt/sources.list`.

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

#### `apache2` ![apache2](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![apache2](https://img.shields.io/debian/v/apache2/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=apache2&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/apache2)

```bash
apt install apache2
```

#### `apache2-doc` ![apache2](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![apache2](https://img.shields.io/debian/v/apache2-doc/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=apache2-doc&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/apache2-doc)

```bash
apt install apache2-doc
```

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
#### `btop`  ![btop](https://img.shields.io/badge/office_application-system_monitor-blue?style=flat-square)
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
#### `cocpit`

[![cockpit](https://img.shields.io/debian/v/chromium/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=cockpit&color=c70036 "Web Console for Linux servers")](https://packages.debian.org/bookworm-backports/cockpit)

```bash
apt install cockpit/bookworm-backports
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

#### `dconf-editor`

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
apt install inkscape
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
apt install kicad-footprints/bookworm-backports
apt install kicad-libraries/bookworm-backports
apt install kicad-packages3d/bookworm-backports
apt install kicad-symbols/bookworm-backports
apt install kicad-templates/bookworm-backports
apt install kicad-doc-en/bookworm-backports
apt install kicad-demos/bookworm-backports
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
#### `libxcb-xtest0`

[![libxcb-xtest0](https://img.shields.io/debian/v/librecad/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=libxcb-xtest0&color=c70036 "libxcb-xtest0")](https://packages.debian.org/bookworm/libxcb-xtest0)

```bash
apt install libxcb-xtest0
```

#### `lshw` ![lshw](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)

[![lshw](https://img.shields.io/debian/v/lshw/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=lshw&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/lshw)

```bash
apt install lshw
```
#### `nautilus-admin` 

[![nautilus-admin](https://img.shields.io/debian/v/nautilus-admin/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=nautilus-admin&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/nautilus-admin)

```bash
apt install nautilus-admin
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
#### `nvidia-tesla-470-driver` ![nvidia-driver](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)

Read the docs:

1. [https://wiki.debian.org/NvidiaGraphicsDrivers](https://wiki.debian.org/NvidiaGraphicsDrivers)
2. [https://wiki.debian.org/NVIDIA%20Optimus#Using_NVIDIA_GPU_as_the_primary_GPU](https://wiki.debian.org/NVIDIA%20Optimus#Using_NVIDIA_GPU_as_the_primary_GPU)
3. [https://www.nvidia.com/en-us/geforce/gaming-laptops/geforce-920m/](https://www.nvidia.com/en-us/geforce/gaming-laptops/geforce-920m/)
4. [https://wiki.archlinux.org/title/NVIDIA_Optimus](https://wiki.archlinux.org/title/NVIDIA_Optimus)

[![nvidia-tesla-470-driver](https://img.shields.io/debian/v/nvidia-tesla-470-driver/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=nvidia-tesla-470-driver&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/nvidia-tesla-470-driver)

```bash
apt install nvidia-tesla-470-driver
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
#### `obs-studio` ![obs-studio](https://img.shields.io/badge/screencast_apss-video_recorder-blue?style=flat-square)
[![obsstudio](https://img.shields.io/debian/v/obs-studio/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=obs-studio&color=c70036 "screen-recording program")](https://packages.debian.org/bookworm/obsstudio)

```bash
apt install obs-studio
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
#### `photocollage` ![photocollage](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![photocollage](https://img.shields.io/debian/v/photocollage/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=photocollage&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/photocollage)
```bash
apt install photocollage
```

#### `php` ![php](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![photocollage](https://img.shields.io/debian/v/php/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=php&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/php)
```bash
apt install php
```
#### `poppler-utils` ![poppler-utils](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![poppler-utils](https://img.shields.io/debian/v/poppler-utils/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=poppler-utils&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/poppler-utils)
```bash
apt install poppler-utils
```
#### `printer-driver-all`  ![printer-driver-all](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![printer-driver-all](https://img.shields.io/debian/v/printer-driver-all/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=printer-driver-all&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/printer-driver-all)
```bash
apt install printer-driver-all
```
#### `rar` ![rar](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![rar](https://img.shields.io/debian/v/rar/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=rar&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/rar)
```bash
apt install rar
```
#### `scribus` ![scribus](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![scribus](https://img.shields.io/debian/v/scribus/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=scribus&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/scribus)
```bash
apt install scribus
```
#### `slic3r` ![slic3r](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![slic3r](https://img.shields.io/debian/v/slic3r/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=slic3r&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/slic3r)
```bash
apt install slic3r
```
#### `sweethome3d` ![sweethome3d](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![sweethome3d](https://img.shields.io/debian/v/sweethome3d/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=sweethome3d&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/sweethome3d)
```bash
apt install sweethome3d
```
#### `tesseract-ocr` ![tesseract-ocr](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![tesseract-ocr](https://img.shields.io/debian/v/tesseract-ocr/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=tesseract-ocr&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/tesseract-ocr)
```bash
apt install tesseract-ocr
```
#### `terminator` ![terminator](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![terminator](https://img.shields.io/debian/v/terminator/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=terminator&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/terminator)
```bash
apt install terminator
```

#### `texlive` ![texlive](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![texlive](https://img.shields.io/debian/v/texlive/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=texlive&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/texlive)
```bash
apt install texlive
```

#### `thunar` ![thunar](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![thunar](https://img.shields.io/debian/v/thunar/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=thunar&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/thunar)
```bash
apt install thunar
```
#### `thunderbird` ![thunderbird](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![thunderbird](https://img.shields.io/debian/v/thunderbird/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=thunderbird&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/thunderbird)
```bash
apt install thunderbird
```
#### `ttf-mscorefonts-installer` ![ttf-mscorefonts-installer](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![ttf-mscorefonts-installer](https://img.shields.io/debian/v/ttf-mscorefonts-installer/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=ttf-mscorefonts-installer&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/ttf-mscorefonts-installer)
```bash
apt install ttf-mscorefonts-installer
```
#### `ufw` ![ufw](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![ufw](https://img.shields.io/debian/v/ufw/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=ufw&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/ufw)
```bash
apt install ufw
```
#### `unrar` ![unrar](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![unrar](https://img.shields.io/debian/v/unrar/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=unrar&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/unrar)
```bash
apt install unrar
```
#### `usbview` ![usbview](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![usbview](https://img.shields.io/debian/v/usbview/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=usbview&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/usbview)
```bash
apt install usbview
```
#### `vlc` ![vlc](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![vlc](https://img.shields.io/debian/v/vlc/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=vlc&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/vlc)
```bash
apt install vlc
```
#### `wget` ![wget](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![wget](https://img.shields.io/debian/v/wget/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=wget&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/wget)
```bash
apt install wget
```
#### `wifi-qr` ![wifi-qr](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)
[![wifi-qr](https://img.shields.io/debian/v/wifi-qr/bookworm?style=for-the-badge&logo=debian&logoColor=c70036&label=wifi-qr&color=c70036 "vector-based drawing program")](https://packages.debian.org/bookworm/wifi-qr)
```bash
apt install wifi-qr
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

Download the latest release of Pandoc via `https://github.com/jgm/pandoc/releases/latest`.

```bash
wget https://github.com/jgm/pandoc/releases/download/3.3/pandoc-3.3-1-amd64.deb
```

Install `pandoc-3.3-1-amd64.deb` via Gdebi.

#### `qmk-firmware`

Visit `https://github.com/qmk/qmk_fpm`

```bash
echo "deb https://linux.qmk.fm/ $(lsb_release --codename --short) main" | tee /etc/apt/sources.list.d/qmk.list
wget -qO - https://linux.qmk.fm/gpg_pubkey.txt | gpg --dearmor | tee /etc/apt/trusted.gpg.d/qmk-gpg-pubkey.gpg > /dev/null
apt update && upgrade
apt install qmk
```

#### `signal` ![signal](https://img.shields.io/badge/office_application-document_viewer-blue?style=flat-square)

```bash
wget -O- https://updates.signal.org/desktop/apt/keys.asc | gpg --dearmor > signal-desktop-keyring.gpg
cat signal-desktop-keyring.gpg | tee /usr/share/keyrings/signal-desktop-keyring.gpg > /dev/null

echo 'deb [arch=amd64 signed-by=/usr/share/keyrings/signal-desktop-keyring.gpg] https://updates.signal.org/desktop/apt xenial main' |\
  tee /etc/apt/sources.list.d/signal-xenial.list
  
apt update
apt install signal
```

#### `typora`
```bash
wget -qO - https://typora.io/linux/public-key.asc | tee /etc/apt/trusted.gpg.d/typora.asc
add-apt-repository 'deb https://typora.io/linux ./'
apt update && apt upgrade
apt install typora
```
#### `vscode`

```bash
wget -qO- https://packages.microsoft.com/keys/microsoft.asc
gpg --dearmor > packages.microsoft.gpg
install -D -o root -g root -m 644 packages.microsoft.gpg /etc/apt/keyrings/packages.microsoft.gpg
echo "deb [arch=amd64,arm64,armhf signed-by=/etc/apt/keyrings/packages.microsoft.gpg] https://packages.microsoft.com/repos/code stable main" | tee /etc/apt/sources.list.d/vscode.list > /dev/null
rm -f packages.microsoft.gpg
apt update && apt upgrade
apt install code
```

#### `zotero`

Visit [https://www.zotero.org/download/](https://www.zotero.org/download/) and download the latest version of Zotero. As `root`:

```bash
cd /opt
wget https://download.zotero.org/client/release/7.0.8/Zotero-7.0.8_linux-x86_64.tar.bz2
tar -xjvf Zotero-6.0.35_linux-x86_64.tar.bz2
rm -rf Zotero-6.0.35_linux-x86_64.tar.bz2
mkdir zotero
cd Zotero_linux-x86_64
mv * /opt/zotero/
cd /opt
rm -rf Zotero_linux-x86_64
cd zotero
chmod +x set_launcher_icon
./set_launcher_icon # or bash set_launcher_icon
ln -s zotero.desktop /home/naf/.local/share/applications/zotero.desktop
```

##### `zotero-better-bibtex`

Visit `https://github.com/retorquere/zotero-better-bibtex/releases/latest` and download:

```bash
wget https://github.com/retorquere/zotero-better-bibtex/releases/download/v6.7.214/zotero-better-bibtex-6.7.214.xpi
```

1. In the main menu go to Tools > Add-ons
2. Select ‘Extensions’
3. Click on the gear in the top-right corner and choose ‘Install Add-on From File…’
4. Choose .xpi that you’ve just downloaded, click ‘Install’
5. Restart Zotero if you’re using Zotero 6


## Notes

### Delete Gnome games.

```bash
apt purge gnome-games
```

### Change Background Grub

Set `grub` background image `/etc/default/grub`.

```bash
GRUB_BACKGROUND=""
```

```bash
update-grub
```

### Change GDM Background

Copy image to `/usr/share/images/vendor-logos/`:

```bash
cp syenasweta-logo-text-version-64.svg /usr/share/images/vendor-logos/
```

Edit file in ` /etc/gdm3/greeter.dconf-defaults`. Add this:

```bash
# Login manager options
# =====================
[org/gnome/login-screen]
#logo='/usr/share/images/vendor-logos/logo-text-version-64.png'
logo='/usr/share/images/vendor-logos/syenasweta-logo-text-version-64.svg'
```

And:

```bash
dpkg-reconfigure gdm3
```

- `https://wiki.debian.org/GDM#Customizing_the_GDM_appearance`

### Disable the user list


Edit file in ` /etc/gdm3/greeter.dconf-defaults`. Uncomment `disable-user-list=true`:

```bash
# - Disable user list
# disable-user-list=true
disable-user-list=true
```

And:

```bash
dpkg-reconfigure gdm3
```

## Add on

- https://extensions.gnome.org/extension/4269/alphabetical-app-grid/

- https://cockpit-project.org/running.html#debian
- Zoom
- Bibtex

### Configure LAMP

- https://wiki.debian.org/LaMp


## Flathub

- https://flathub.org/apps/org.kde.kdenlive
- https://flathub.org/apps/com.obsproject.Studio
- https://flathub.org/apps/dev.storyapps.starc

## Credits

