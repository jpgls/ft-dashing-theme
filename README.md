# FT-Dashing Theme 1.0

## General Overview
This is an original, custom theme designed for [FoldingText](http://www.foldingtext.com).

![](http://jpgls.com/ft-dashing-theme/example-images/FoldingText.png)

### Fonts
---  
Ideally, this theme is intended to make use of Adobe's Open Source fonts, **Adobe Source Sans Pro** and **Adobe Source Code Pro**. You can check out the **GitHub** Projects ([code](https://github.com/adobe/source-code-pro) - [sans](https://github.com/adobe/source-sans-pro)) or download the OTF files directly from **SourceForge** ([code](http://sourceforge.net/projects/sourcecodepro.adobe/files/) - [sans](http://sourceforge.net/projects/sourcesans.adobe/files/)). The easiest way to install the fonts though, is using Typekit ([code](https://typekit.com/fonts/source-code-pro) - [sans](https://typekit.com/fonts/source-sans-pro)) - assuming you have an account either directly or through Creative Cloud.

Alternate fallbacks have been defined in the stylesheet, but, I really would encourage you to get the *Source* fonts.

### Notes
---  
At the moment, the styling is mostly focused on ToDos, but will work nicely as a general theme too.

This theme currently targets the latest version available in the App Store, Version 1.2.2 (647), but I'm looking forward to checking out the new developments that seems to be underway for 2.0 ([Check them out here.](http://support.foldingtext.com/discussions/development-versions/196-foldingtext-20-dev-build-723))

#### Fun Fact
I'm also building out a version of this theme for [LightPaper](http://clockworkengine.com/lightpaper-mac/), [Mou](http://mouapp.com), and other markdown editors/viewers which is available in this repo: [md-dashing-theme](https://github.com/designerJordan/md-dashing-theme)

I've been tinkering with these fonts and colors for quite a while, across most apps I use regularly that allow for much customization of their appearance. I hope to continue rounding them up, polishing things, and sharing them. Apps that are hopefully coming sometime sort of soon-ish include:

* OmniGraffle
* OmniOutliner
* OmniFocus
* Sublime Text 3/2
* iTerm 2
* Alfred
* Path Finder
* LibreOffice

If you would like to request support for any other apps, let me know and we can take a look. Contact info is at the bottom of this doc.


## Installation
- Download style.css from this repo
- If you don't already have it, download and install Adobe Source Code Pro from the link above
- Quit FoldingText if it's currently running
- Open a finder window and navigate to the Applications folder
- Right-click (ctrl-click) on FoldingText
    + Select "Show Package Contents" from the context menu
    + **Note:** You will be prompted to enter an administrator password for any changes you make to the package contents
- Navigate to Contents/Resources/javascript-dom-build/themes/Courier.fttheme/
    + **Note:** *User.fttheme (or any theme other than Courier.fttheme) seems to be getting ignored in the current version of FoldingText, so it's necessary to overwrite the contents of Courier.fttheme for the time being. I recommend duplicating the existing version of style.css and renaming it to style.css.ORIG or something similar so that you can easily roll back if you decide.*
- Replace the style.css file with the version from this repo
- Launch FoldingText and enjoy

## Uninstallation
**This is the part where it becomes important to have followed the steps to backup the original style.css file noted above**
- Quit FoldingText if it's currently running
- Open a finder window and navigate to the Applications folder
- Right-click (ctrl-click) on FoldingText
    + Select "Show Package Contents" from the context menu
- Navigate to Contents/Resources/javascript-dom-build/themes/Courier.fttheme/
- Delete the style.css file you installed from this repo
- Rename the backup you made during installation back to "style.css"
- Launch FoldingText

## Contact
Please feel free to open an Issue.

## Mundane but Important
Dashing Theme is released under the MIT license and is copyright 2014 Jordan Pagels. The full license is located in the project repository for more information.