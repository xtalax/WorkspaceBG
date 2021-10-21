# WorkspaceBG

Allows different desktop backgrounds per virtual desktop in KDE.

Add the paths to your desired backgrounds to the corresponding variable in the `.workspace_bgs` file that will be added to your home folder

To remove the KDE fade effect when changing wallpapers, run
```
sudo sed -i 's/<default>1000<\/default>/<default>1<\/default>/g' /usr/share/plasma/wallpapers/org.kde.image/contents/config/main.xml

sudo sed -i 's/<default>10<\/default>/<default>1<\/default>/g' /usr/share/plasma/wallpapers/org.kde.image/contents/config/main.xml
```
