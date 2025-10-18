🧛‍♂️ SLiM-dracuburl

A sleek, custom SLiM (Simple Login Manager) theme featuring:

    🔤 Custom font integration

    🌙 Dracula-inspired color palette

This theme brings a modern, colorful aesthetic to your login screen while staying lightweight and fast.
📸 Preview

    Add a screenshot here if you’d like!

📁 Files Included

    slim.theme – Main theme configuration, edit positioning as needed.

    background.png – Change this to whatever background you want

    TiposkaDev.ttf – Custom font based on Tiposka with the only change being the "1" was edited for better
    differentiation between the number "1" and letter "i".

    panel.png – Contains the login field image. Colors and alpha can be edited in GIMP.

🐧 Installation Guide (Gentoo)

1. Clone this repository
git clone https://github.com/1ch0r/dracuburl.git

2. Copy theme files to SLiM themes directory
sudo cp -r slim-dracula-theme /usr/share/slim/themes/dracula

3. Set the theme in SLiM configuration (near bottom)
Edit /etc/slim.conf and set: "current_theme dracuburl"

4. Reboot (SLiM caches themes so it won't be recognized until cache gets cleared)
