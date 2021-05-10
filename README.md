# [Night Hacker Dark Theme](https://marketplace.visualstudio.com/items?itemName=ddh4r4m.night-hacker-dark-theme)


[![Version](https://vsmarketplacebadge.apphb.com/version/ddh4r4m.night-hacker-dark-theme)](https://marketplace.visualstudio.com/items?itemName=ddh4r4m.night-hacker-dark-theme)
[![Rating](https://vsmarketplacebadge.apphb.com/rating-star/ddh4r4m.night-hacker-dark-theme)](https://marketplace.visualstudio.com/items?itemName=ddh4r4m.night-hacker-dark-theme)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/ddh4r4m.night-hacker-dark-theme)](https://marketplace.visualstudio.com/items?itemName=ddh4r4m.night-hacker-dark-theme)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads/ddh4r4m.night-hacker-dark-theme)](https://marketplace.visualstudio.com/items?itemName=ddh4r4m.night-hacker-dark-theme)
[![Issues](https://img.shields.io/github/issues/rkstrdee/night-hacker-dark-theme)](https://github.com/rkstrdee/night-hacker-dark-theme/issues)



> A dark theme for [Visual Studio Code](http://code.visualstudio.com).


# Default Theme
![Screenshott](https://raw.githubusercontent.com/rkstrdee/night-hacker-dark-theme/main/screenshots/NightHacker_default_Theme_banner.png)


![Screenshot](https://raw.githubusercontent.com/rkstrdee/night-hacker-dark-theme/a3b41d2faa9fadc130283665f839438814055afe/screenshots/NightHacker_default_Theme.png)

# Tweaks and theming

If you want to change some colors, use the setting `workbench.colorCustomizations` 
to customize the currently selected theme. For example, you can add this snippet in your "settings.json" file:

```json
"workbench.colorCustomizations": {
  "tab.activeBackground": "#12071c",
  "activityBar.background": "#12071c",
  "sideBar.background": "#12071c"
}
```

or use the setting `editor.tokenColorCustomizations`

```json
"editor.tokenColorCustomizations": {
  "[Night Hacker]": {
    "textMateRules": [
      {
        "scope": ["source.python"],
        "settings": {
          "foreground": "#e06c75"
        }
      }
    ]
  }
}
```
## Usage

Select the theme and go!

## Installation

1. Open **Extensions** sidebar panel in Visual Studio Code. `View → Extensions`
1. Search for `Night Hacker Dark Theme`
1. Click **Install**
1. Click **Reload**
1. File > Preferences > Color Theme > **Night Hacker Dark Theme**

## Further Customization
If you want to set up the panel to the right side of the screen as shown,
then launch `Preferences:Open Settings (JSON)` using "⇧⌘P" or "Ctrl+Shift+P" and add these lines, depending on your comfort.
```json
    "workbench.sideBar.location": "right",    
    "terminal.integrated.fontFamily": "MesloLGS NF",
    "terminal.integrated.fontSize": 15,
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Night Hacker",
    "window.zoomLevel": -1
```

## Feedback

If you have suggestions, please [open an issue](https://github.com/rkstrdee/night-hacker-dark-theme/issues) or better yet, a [pull request](https://github.com/rkstrdee/night-hacker-dark-theme/pulls).

Be nice.


## Team

This theme is maintained by the following person(s) and a bunch of [awesome contributors](https://github.com/rkstrdee/night-hacker-dark-theme/graphs/contributors).

[![Dharam D.](https://avatars.githubusercontent.com/u/42842402?v=4&s=70)](https://github.com/rkstrdee) |
:---: |
[Dharam D.](https://github.com/rkstrdee) |



**Enjoy!**
