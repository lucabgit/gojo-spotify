# Gojo Spotify Theme

![oie_zToc1P6A6etD](https://github.com/user-attachments/assets/dd6b9e2a-0ecd-416f-b074-86d7ccf5d259)

Dependencies: Spotify, Spicetify, notepad++ (or any other notepad/text editing software)

Sources: 
https://spicetify.app/docs/getting-started#windows
https://www.spotify.com/download/windows/

Disclaimer: This is an edit of https://github.com/Motschen/Retroblur

The color.ini user.css and theme.js have been edited and customized.

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

!!If you use winrar, dont extract the folder. Go into the winrar archive and drag the zip folder thats inside into the themes folder.!!

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

# What is Spicetify?

Spicetify is a tool used to customize and modify the appearance and functionality of the Spotify client. It allows users to tweak the Spotify desktop app or web player by applying themes, installing extensions, and adjusting settings that are not natively available through Spotify itself.

Here are some of the key features of Spicetify:

Themes: Users can change the visual style of Spotify, choosing from pre-made themes or creating their own. This can modify elements like colors, fonts, and layout.

Extensions: Spicetify supports extensions that add additional functionality to Spotify, such as additional features, enhanced controls, or integration with other services.

Custom Scripts: Advanced users can write custom JavaScript scripts to further enhance or alter the behavior of Spotify, giving complete control over the experience.

Configuration Tweaks: It also allows for advanced settings adjustments, like hiding or rearranging UI elements, or enabling certain features that are not officially supported.

Installation and Usage:

Spicetify is open-source and typically requires some technical knowledge to install, as it often involves working with command-line interfaces or installing dependencies like Node.js.
It's mainly available for users who use Spotify on Windows, macOS, and Linux.
Overall, Spicetify is a powerful tool for users who want to fully personalize and enhance their Spotify experience. However, it’s important to note that using Spicetify requires caution, as modifying Spotify’s functionality can sometimes result in issues or may not be officially supported by Spotify.

Documentation: https://github.com/spicetify/docs
Developement: https://spicetify.app/docs/development

- ChatGPT

![EEEEE](https://github.com/user-attachments/assets/42e31714-76fd-43f0-81b4-8026a6efcb09)
