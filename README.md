# 🧛‍♂️ SLiM-dracuburl

A sleek, custom SLiM (Simple Login Manager) theme featuring:

    🔤 Alternative font integration

    🌙 Dracula themed color palette

## 📸 Preview
![Login screen preview](dracuburl-demo.png)

## 📁 Files Included

    slim.theme – Main theme configuration, edit positioning as needed.

    background.png – Change this to whatever background you want

    panel.png – Contains the login field image. Colors and alpha can be edited in GIMP.

## 🐧 Installation Guide (Gentoo)

```bash
git clone https://github.com/1ch0r/dracuburl.git
cd dracuburl
sudo cp -r dracuburl /usr/share/slim/themes/dracuburl
sudo mkdir -p /usr/share/fonts/tiposka
sudo cp Tiposka.ttf /usr/share/fonts/tiposka/
sudo fc-cache -fv
```
-`Download Tiposka from BestFonts and install it`
```bash
sudo mkdir -p /usr/share/fonts/tiposka
sudo cp Tiposka.ttf /usr/share/fonts/tiposka/
sudo fc-cache -fv
```


Edit /etc/slim.conf and set: "current_theme dracuburl"
```bash
#SLiM caches themes so it won't be recognized until cache gets cleared
sudo reboot
```
