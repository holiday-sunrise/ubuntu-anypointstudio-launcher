# ubuntu-anypointstudio-launcher
How to add a Desktop Item/ Task Favorites Item for "Mule Anypoint Studio"  7.x

## create file:
sudo vim /usr/share/applications/AnypointStudio.desktop

```
[Desktop Entry]
Version=7.10
Type=Application
Terminal=true
Exec=[installation-directory]/AnypointStudio/AnypointStudio
Name=AnypointStudio
Icon=[installation-directory]/AnypointStudio/icon.xpm
```

## mod permissions

sudo chmod 644 /usr/share/applications/AnypointStudio.desktop

sudo chown root:root /usr/share/applications/AnypointStudio.desktop

