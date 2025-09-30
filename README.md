# Zen macOS window controls
If you installed Zen Browser via flatpak and want to use macOS window controls on Ubuntu, follow these steps:

1. Type **about:config** in the Zen address bar
2. Search for **toolkit.legacyUserProfileCustomizations.stylesheets** and set it to true
3. Clone this repository to any folder
4. Go to the **~/.var/app/app.zen_browser.zen/.zen** directory and then enter the folder that contains '**(release)**' in its name
5. If a **chrome** directory doesn't exist in your release folder, create it
6. Copy the icon **svg files** and the **userChrome.css** file into this folder
7. Close and reopen Zen Browser

<div align="center">
    <img src="screenshots/controls.png" alt="Gameboard"/>
</div>

