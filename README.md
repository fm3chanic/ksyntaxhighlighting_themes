## fm3chanic Themes for KSyntaxhighlighting

This repository contains all color themes for KSyntaxhighlighting I've created. 
KSyntaxhighlighting supports Kate and KWrite from the KDE desktop project and all other applications which are using KSyntaxhighlighting.

Themes which have been created during my project of color theming Vtubers are in the folder "vtuber_project". The folder "other" contains all color themes which where created outside of the project.

HTML-scheme files for all color themes: https://github.com/fm3chanic/color_schemes

Further information regarding the Vtuber project: https://github.com/fm3chanic/vtuber_project

**Please note** that all color themes have been originally created for Notepad++, which has the tendency to show colors lighter as they are in other applications. Therefore it might occur that the color theme is slighly darker in Kate, KWrite, etc.

### Installation:

There are two installation options.

**Option 1:**

1. Open Kate / KWrite.
2. Go to Settings.
3. Go to Configure Kate / KWrite.
4. Go to Color Themes and in there to the tab "Theme Editor". You can import the theme file via the "Import" button.
5. The theme is now selectable in the settings.

*To remove a theme select the theme in the "Theme Editor" and click on "Delete"*

**Option 2:**

Put the `.theme` file in the directory `~/org.kde.syntax-highlighting/themes/` and it will load the next time you open the application.
The usual directory where the themes are deployed is

`$HOME/.local/share/org.kde.syntax-highlighting/themes/` for local installation

**OR**

`/usr/share/org.kde.syntax-highlighting/themes/` for machine-wide installation.

Depending on installation (Flatpak, Snap, Windows) you might find the directory in different locations.

|Installation Method|Location|
|:---:|:---|
|Flatpak packages|`$HOME/.var/app/flatpak-package-name/data/org.kde.syntax-highlighting/themes/`|
|Snap packages|`$HOME/snap/snap-package-name/current/.local/share/org.kde.syntax-highlighting/themes/`|
|Windows®|`%USERPROFILE%\AppData\Local\org.kde.syntax-highlighting\themes`|

*To remove the theme remove the theme file from the according directory.*

***For local installation or deinstallation both options can be used interchangably.***

### Contribution:

If you want to help maintaining the themes, please use colors from the according color scheme. You can find the scheme files in the repo linked above.