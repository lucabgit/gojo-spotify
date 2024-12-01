# Gojo Spotify Theme

![oie_zToc1P6A6etD](https://github.com/user-attachments/assets/dd6b9e2a-0ecd-416f-b074-86d7ccf5d259)

Dependencies: Spotify, Spicetify, notepad++ (or any other notepad/text editing software)

Sources: 
https://spicetify.app/docs/getting-started#windows
https://www.spotify.com/download/windows/

Disclaimer: This is an edit of https://github.com/Motschen/Retroblur

The color.ini and theme.js have been edited and customized.

# Step by step installation guide - Windows



Open Powershell

Run the following command:

```
iwr -useb https://raw.githubusercontent.com/spicetify/cli/main/install.ps1 | iex
```

When prompted with a marketplace option type Y and hit enter

Leave Powershell open

# Using the Theme

Download the theme by clicking on the green "code" button (Sroll upwards on this website) and hit "Download Zip"

Extract the folder and put it on your desktop

Press Windows + R

Type in "appdata" 

Hit enter

Go to Roaming

Go to Spicetify

Put the .zip folder you downloaded into the "themes" folder 

!!If you use winrar, dont extract the folder. Go into the winrar archive and drag the zip folder thats inside onto your desktop.!!

Edit config-xpui.ini with notepad++ or any other text editing software of your choice. 
(You can get notepad++ here) https://notepad-plus-plus.org/downloads/

Inside config-xpui.ini, set "current_theme" "from marketplace" to the same name as the .zip folder

Go back to powershell. Type "spicetify apply" and hit enter.

# Enjoy
![111111111](https://github.com/user-attachments/assets/90d59b26-209c-4727-b39c-404351919dd0)


# How to uninstall

Open Powershell

Run
```spicetify restore
rmdir -r -fo $env:APPDATA\spicetify
rmdir -r -fo $env:LOCALAPPDATA\spicetify
```
