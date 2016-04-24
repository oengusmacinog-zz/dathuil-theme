# Dathuil Theme for Sublime Text 3 3103+

This theme was really a range of adjustments to existing resources to make them meld a bit better, and then I kept making tweaks. This theme is for me because I love an awesome looking dev space, if you want changes then fork it and make it your own.

Theme was build on top of [Material Theme](https://github.com/equinusocio/material-theme), with some changes to colors and fonts.  The color scheme was build on [Seti UX](https://github.com/ctf0/Seti_UX). I was never a fan of the color palate from Seti UX, but greatly enjoyed the expanded syntax heighlighting (seriously it highlights *a lot* more then almost any other color scheme).

# Manual installation

1. Download the [latest release](https://github.com/oengusmacinog/dathuil-theme), extract and rename the directory to **"Dathuil Theme"**.

2. Move the directory inside your sublime Packages directory. **(Preferences > Browse packages...)**


# Activate the theme

Activate the theme with the following preferences at  **(Preferences > Setting - User)**:

```json
"theme": "Dathuil-Theme.sublime-theme",
"color_scheme": "Packages/Dathuil Theme/schemes/Dathuil-Theme.tmTheme",
```

***Note*** : Remember to restart Sublime Text after activating the theme.

# Theme options

```json
"dathuil_theme_small_tab"                : true , // Set small tabs
"dathuil_theme_disable_fileicons"        : true , // Hide sidebar file type icons
"dathuil_theme_disable_folder_animation" : true , // Disable folder animation
"dathuil_theme_small_statusbar"          : true , // Set small status bar
"dathuil_theme_compact_sidebar"          : true , // Set compact side bar
"dathuil_theme_compact_panel"            : true , // Set minimal padding for the search panel
"dathuil_theme_disable_tree_indicator"   : true , // Disable sidebar file indicator
"dathuil_theme_bold_tab"                 : true , // Make the tab labels bolder
"dathuil_theme_tabs_separator"           : true , // Show tabs separator, this disables tab hover animation
"dathuil_theme_accent_lime"              : true , // set green lime accent color
"dathuil_theme_accent_purple"            : true , // set purple accent color
"dathuil_theme_accent_red"               : true , // set pale red accent color
"dathuil_theme_accent_orange"            : true , // set orange accent color
"dathuil_theme_accent_yellow"            : true , // set yellow accent color
"dathuil_theme_accent_indigo"            : true , // set indigo accent color
"dathuil_theme_accent_pink"              : true , // set pink accent color
"dathuil_theme_accent_blue"              : true , // set blue accent color
"dathuil_theme_accent_cyan"              : true , // set cyan accent color
"dathuil_theme_panel_separator"          : true , // show bottom panel separator
"dathuil_theme_tabs_autowidth"           : true , // Enable autowidth for tabs
"dathuil_theme_contrast_mode"            : true , // Enable sidebar and panels contrast mode

// If you use Dathuil Theme - Appbar addon you can use additional settings:
"dathuil_theme_tree_headings"            : true , // Show sidebar headings
```

<!-- # Recommended settings for a better experience: -->

# Compiling to Edit the Theme

This UI theme use a custom compiler build on Gulp and JS. If you want to edit the UI you must first install the compiler:
```
$ npm install
```
then run compiler and watcher by run:
```
$ gulp
```
You can now edit the source files under `/src` folder that will be compiled inside the root folder (don't edit compiled files.)