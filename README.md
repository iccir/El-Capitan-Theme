# El Capitan Theme

OS X inspired light theme for Sublime Text 3.

Based on Soda Theme by Ian Hill ([http://buymeasoda.com/](http://buymeasoda.com/))

## Design

![Screenshot](https://raw.githubusercontent.com/wiki/iccir/El-Capitan-Theme/Screenshot.png)

Also available in a [dark version](https://github.com/r3volution11/El-Capitan-Theme), courtesy of [Doug Hardester](https://github.com/r3volution11)!

The code font shown in the screenshot is Monaco.  The color scheme is [Xcode-ish](https://gist.github.com/iccir/b999104536ce8211e5e7).


## Installation

El Capitan theme is designed to work with the latest development builds of [Sublime Text 3](http://www.sublimetext.com/3dev).

#### Package Control

If you are using [Sublime Package Control](https://packagecontrol.io), you can easily install the theme via `Package Control: Install Package` and then select the  `Theme - El Capitan` package.

#### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/iccir/El-Capitan-Theme/ "Theme - El Capitan"

#### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - El Capitan`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating and configuring the theme

To configure Sublime Text to use the theme, follow the instructions below:

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "El Capitan.sublime-theme"`

**Example Sublime Text 3 User Settings**

    {
        "theme": "El Capitan.sublime-theme",
        
        "el_capitan_font_default": false,
        "el_capitan_font_san_francisco": false,
        "el_capitan_font_helvetica_neue": false,
        "el_capitan_font_helvetica": false,
        "el_capitan_sidebar_blue_folders": false
    }

* `el_capitan_font_default` - If `true`, prevents the theme from specifying fonts (for systems without Helvetica Neue or SF)
* `el_capitan_font_san_francisco` - If `true`, the font is explicitly set to San Francisco
* `el_capitan_font_helvetica_neue` - If `true`, the font is explicitly set to Helvetica Neue
* `el_capitan_font_helvetica` - If `true`, the font is explicitly set to Helvetica
* `el_capitan_sidebar_blue_folders` - If `true`, the sidebar uses blue folders rather than Xcode-style yellow folders.
* 'el_capitan_sidebar_graphite' - If 'true', the sidebar uses graphite folders and selected states, to match the UI Graphite settings in OS X System Preferences > General > Appearance setting.

## Development

Please note, Sublime Text dev builds move quickly and changes can occur with the theme API between releases, so there may be occasions where the theme doesn't quite work with a brand new dev release.

## License

El Capitan Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

El Capitan Theme is based on Ian Hill's excellent Soda Theme, and thus the following Creative Commons license "author specified" components apply:

* Attribution example: Based on Soda Theme by Ian Hill (http://buymeasoda.com/)

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Soda Theme" (or a close variant) in the main project title, repo name or Package Control name.
