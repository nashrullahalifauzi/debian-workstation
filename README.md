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
### The Table of Debian Sofware

| Name | Description |
| ---------- | ---- |
| `atril` |  |
| `audacious` |  |
| `audacity` |  |
| `blender` |  |
| `btop` |  |
| `calibre` |  |
| `chromium` |  |
| `cpu-x` |  |
| `curl`     |      |
| `ebook-speaker` | |
| `filezilla` | |
| `font-manager` | |
| `font-viewer` | |
| `freecad` | |
| `freeplane` | |
| `geany` | |
| `gdebi` | |
| `gimp` | |
| `git`      |      |
| `gnome-power-manager` | |
| `gnucash` | |
| `gparted`  |      |
| `gscan2pdf` | |
| gsmartcontrol | |
| `gthumb` | |
| `hardinfo` | |
| `htop` | |
| `inkscape` | |
| `img2pdf` | |
| `kdenlive` | |
| `kicad` | `apt install kicad/bookworm-backports` |
| `kraft` |  |
| `krita` | |
| `librecad` | |
| `neovim` | |
| `ocrmypdf` | |
| `obsstudio` | |
| `openscad` | |
| `partitionmanager` | |
| `pdfarranger` | |
| `pdfsam` | |
| `pdftk` | |
| `photocollage` | |
| `poppler-utils` | |
| `signal` | |
| `scribus` | |
| `slic3r` | |
| `sweethome3d` | |
| `tesseract-ocr` | |
| `terminator` | |
| `thunar` | |
| `usbview` | |
| `vlc` | |
| `wifi-qr` | |
| `wget`     |      |
|            |                                        |
|                       |                                        |

## Non-Debian Software Repositories

| Name               | Description |
| ------------------ | ----------- |
| `chrome`           |             |
| `odafileconverter` |             |
| `pandoc`           |             |
| `typora`           |             |
| `via`              |             |
| `vscode`           |             |
| `zotero`           |             |
|                    |             |
|                    |             |
|                    |             |



## Notes

Delete Gnome game:

```bash
apt purge gnome-games
```





