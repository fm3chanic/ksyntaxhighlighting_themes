## fm3chanic Themes for KSyntaxhighlighting

This repository contains all color themes for KSyntaxhighlighting I've created so far.<br> 
KSyntaxhighlighting supports Kate and KWrite from the KDE desktop project and all other applications which are using KSyntaxhighlighting.

Themes which have been created during my project of color theming Vtubers are in the directory "vtuber_project". The directory "other" contains all color themes which where created outside of the project.

**[HTML Reference Sheets & Galery Non-Project Themes](https://github.com/fm3chanic/color_schemes)**<br>
**[Vtuber Project | Information & Galery](https://github.com/fm3chanic/vtuber_project)**

> [!IMPORTANT]
> Please note that all color themes have been originally created for Notepad++, which has the tendency to show colors lighter as they are in other applications. Therefore it might occur that the color theme is slighly darker in Kate, KWrite, etc.

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

Depending on installation (Flatpak, Snap, Windows) you might find the directory in a different location on your machine:

|Installation Method|Location|
|:---:|:---|
|Flatpak packages|`$HOME/.var/app/flatpak-package-name/data/org.kde.syntax-highlighting/themes/`|
|Snap packages|`$HOME/snap/snap-package-name/current/.local/share/org.kde.syntax-highlighting/themes/`|
|Windows®|`%USERPROFILE%\AppData\Local\org.kde.syntax-highlighting\themes`|

*To remove the theme remove the theme file from the according directory.*

> [!NOTE]
> For local installation or deinstallation both options can be used interchangably.

### Contribution:

The themes are based on the mapped template in directory **/tools**.<br>
The python script (_\[...\]\_load_colors.py_) reads the colors from a html file from [color_schemes](https://github.com/fm3chanic/color_schemes) and uses replace to fill in the colors.<br>

If you want to work on colors it makes the most sense to change the colors in repository [color_schemes](https://github.com/fm3chanic/color_schemes) so the changes can be applied to all applications using the theme.<br>
If you want to work on the mapping of the colors it might make sense to change the base template, so changes can be applied to all themes of this application.<br>

The only exception of this is the gruber-darker theme, which does not follow this standard.<br><br>
Neverless, **I also welcome contribution not following this standard**. The standard was made to keep it maintainable for one person, not to block community ideas.<br>