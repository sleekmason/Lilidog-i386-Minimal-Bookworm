﻿### Lilidog Linux

Website: https://lilidog.org/ <br/>
Forum Link: https://www.forum.lilidog.org/ <br/>
Download link: https://sourceforge.net/projects/lilidog/
 
Lilidog is a lightweight Linux distro using the Openbox window manager with the tint2 panel. <br/>

Lilidog is based on Debian, with most of the hard parts done, and some cool stuff along the way. <br/>
Everything is easily accessible, with numerous options to customize further.

### There are several versions of Lilidog available based on users needs and wants. 
Click on 'Files', and then 'Releases' to see the different versions currently available.

- Lilidog full version -  Has most programs already installed for everyday use, and installers for several others.
This includes Firefox, Thunderbird, Thunar, Geany, Gpicview, Smplayer, Gparted, Synaptic and Libreofficeto name a few.
This build comes with approx. 1300 packages installed, still making for a lightweight general setup.

- Lilidog-Minimal-amd64 - This version contains all of the goodness of Lilidog while allowing you to choose most all 
of your own main packages.  This option includes all of the Lilidog options found in the full version while still being 
as light as possible. Approx. 1080 packages installed.

- Beardog - A play on words a bit.  This is the "bare" minimal version of Lilidog with no ld theme changer.  Thunar
geany and lxterminal are the default installed applications.  You don't need to be an advanced user to use Beardog,
but a basic understanding of linux is probably a good idea.  Approx. 920 packages installed.
If you are wanting to start with a bare build system, this may be the one for you!
 
- Lilidog-i386 (Bullseye i386 full version) Uses the same base packages as the amd64 version, but for older hardware.
You may need to boot with the kernel parameter 'forcepae' if you have difficulties.  This version will no longer be
available after debian changes from Bullseye to Bookworm.

### You may also find a testing or sid version on occasion.  
While generally stable, these are for testing purposes and should be recognized as such if used.

 Join the Lilidog forum to report any issues and keep lilidog bug free!  Forum Link: https://www.forum.lilidog.org/ <br/>
See further below for features.

### NOTE - The DOWNLOAD button defaults to the Bookworm-amd64 full version! (stable).  Click below for the others.

[![Download Lilidog](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/lilidog/files/latest/download)

### Click Here for the other releases: 
https://sourceforge.net/projects/lilidog/files/Releases/

### Directions

Probably the easiest way to use Lilidog is to put it on a usb stick.

One easy way is to grab the live-usb-maker app: https://github.com/MX-Linux/lum-qt-appimage/releases/tag/19.11.02 <br/>
Download the AppImage.tar.gz and open a terminal:<br/>
```sh
tar -xaf live-usb-maker-qt-19.11.02.x86_64.AppImage.tar.gz
Then:
sudo ./live-usb-maker-qt-19.11.02.x86_64.AppImage
```
Use "image mode" in the live-usb maker when burning the image.

### Installing Lilidog

### Debian Installer (All builds)

The grub boot screen for Lilidog gives a choice of using Lilidog in a Live session, or installing using the debian installer. <br/>
Lilidog uses the Debian installer with both text and graphical installs available though the Calamares installer is available through
the green icon in the system tray while in the live environment if using bookworm.

### Calamares Installer (Bookworm only)

The Calamares installer is a new addition to Lilidog going forward. In the live session, find the green install icon in the system tray to get started.
For All live sessions, Username is "user" and root password (sudo) is "live"

### Navigating Lilidog:
After booting into Lilidog, you have the option to install or try out the Lilidog live environment. Once in a session, there are a few items 
that can shape your experience. Look in the "paw" icon in the tint2 panel for theming options.  Look in the "Toggles" section of the menu for 
some useful options, and look in the "Install Extras" portion of the menu for extra programs you may want.  Look around.  There
is more to see as well.

Again, the username and password for the live environment is "user", and "live" respectively. 

Lilidog: <br/>

[![Installer.png](https://i.postimg.cc/6qSpSZNR/Installer.png)](https://postimg.cc/JHN8HG04)

[![Lilidog-Slate.png](https://i.postimg.cc/3J4CRPs6/Lilidog-Slate.png)](https://postimg.cc/SJ4z1tN7) <br/>

### Features:

- Based on Debian with contrib and non-free sources enabled by default.

- Bullseye backport and Debian Fast Track can be added to your sources from the 'Extras' portion of the menu under 'Utilities'.

- These are 'no recommends' builds. This means only required dependencies are included during install.
This leaves out any recommended or suggested packages, allowing for complete control over package installation.
No unwanted packages will be installed by default. This can be changed after install if desired.

- Tint2 is the panel by default. Currently available options for tint2 include icon type, icon size, transparency, time format,
autoshrink, autohide,and position (top or bottom). These can be accessed from either the toggles menu, or in the tint2panel
under the 'T2' icon.

- Jgmenu is the menu for all versions.  Huge amount of customization available.
Go to menu -> configuration -> jgmenu.conf for how to change and add items. 

- Wallpapers - Handled by Feh.  Place any image you would like to use as a wallpaper in ~/Pictures/wallpapers.
Go to Menu -> Configuration -> Wallpaper Chooser to change wallpapers.
You can also right-click on any image you choose from the file manager to set as background wallpaper. Other right-click
options for images include rotation and copying to ~/Pictures.wallpapers. A random wallpaper toggle is included.

- Icons - The Breeze icon set comes installed as default. Papirus and Gnome icon sets both have menu install entries as well.
Both menu options provide for a variety of different colors to choose from.  There is an extra script to provide even
more Papirus theme colors if interested. (24 in total for now.)

- Menu Toggles - Items like Autologin, notification sounds, screen color correction, conky, random BG, and more.

- Menu Extras - an extra install menu with options for Liquorix kernel, Qemu, Steam, Etcher, Discord, and more.

- Grub background changer opens a window to choose your own images. Lilidog ships with six to give you an intitial
choice before finding your own to add to the collection.

- There is a shortcut for xfce4-power-manager by right-clicking on the battery icon.
To see time format options for 24 hour vs. 12 hour, middle-click over the time for the man page.
Hover over the icons to see what they are.  The live password is "live" for the screenlock.

- Xscreensaver and other handy startup apps readily available through the toggles in the menu,
or can be activated on login by adding to the autostart configuration file.

- Dmenu for an alternate menu source. - ALT + F2 pulls the full Dmenu up, while ALT + F3 pulls up a
customized Dmenu with only the most commonly used apps. Look under Configuration in the menu to change items.

- Wbar for icons on the desktop if desired. activate from Toggles in the menu. Fun to configure!

- Thunar is the default file manager.  Custom right-click options are already added as well. These include everything from
"Open as Root', to different rotations and sizing of pics, to comparisons of files using Meld. And more.

- Custom Lilidog Openbox and GTK themes, and matching themes for Geany and Xfce4-terminal.
The fonts are Liberation Sans, except for urxvt and Conky, where Dejavu is used. (see "instructions" below.)

- Xfce4-terminal is default, with URXVT also installed. Use "App Alternatives in the menu
 or __sudo update-alternatives --config x-terminal-emulator__ in a terminal to switch default terminals.  

- URXVT terminal has font size control (ctl+up/down), transparency, and opens urls in Firefox.

- Conky Chooser in the toggles section of the menu contains toggles for six different Conkys and the time format shown. All of
the Conkys contain relevant info. These include a Clock, Full Info, Fortunes, Shortcuts, Worldclock, and Current Conditions.
Please note that "Current Conditions" takes a moment to initialize.  Mix, match, change, etc. Everything is located in the
conky folder ~/.config/conky including the Conky Chooser script.

- Picom Composite Manager with transparency enabled. Look in the "paw" in tint2 for easy adjustment options, or
Look in the configuration menu to access ~/.config/picom.conf in order to change even more settings.

- Gammy screen color and lightness control located in Toggles, and from the keybind "Super + g". This will allow you to change
and set the gamma and brightness of your screen for different times of your choice, or simply as a toggle when desired.

- Newsboat RSS reader with a custom configuration already in place and ready for new RSS feeds.

- System notifications enabled with Dunst.

- Swapid script for the frequent dual installer. This grabs your swap uuid and opens the appropriate windows to edit.
Run 'swapid' in a terminal after installing another distro to a different partition.

- ld-hotcorners - Each corner of the screen responds to a command.
Turn it on with the button in the lower left corner or under Toggles in the menu.
Change the corners in ~/.config/ld-hotcorners.
Currently clockwise from top left: __file manager, toggle Picom, exit menu, and terminal.

### Instructions For Various Tasks:

__Theme changes:__  
The easiest way to change themes is with the 'Quick Theme Changer' located in the menu under Configuration.
This changes The GTK theme, Openbox theme, Geany theme, Lightdm, wallpaper, menu, and terminal theme all on the fly.

__Make your own themes:__ <br/>
All of the theme files are located in ~/.config/lilidog-themes. This will allow you to change the settings on the existing themes,
to making your own and adding a button to the theme changer. For a quick overview see the discussion: https://sourceforge.net/p/lilidog/discussion/setup/thread/b3fec6a23b/ <br/>
or the README located in ~/.config/lilidog-themes. <br/>

__Other Settings:__
- For keyboard language layout see: https://sourceforge.net/p/lilidog/discussion/setup/thread/e9e88533c0/<br/>
- Most common items to change will have an entry under 'Configuration' in the menu.<br/>
- Settings Manager - Change your gtk theme, fonts, and icons on an individual basis.  Other important settings are here as well. <br/>
- Openbox Conf - The settings here control the window borders and other settings specific to Openbox. <br/>
- Jgmenu - Go to menu -> configuration -> jgmenu.conf for menu items. For theme changes, got to Jgmenu Theme Changer in the menu. ("o" or "g") <br/>
- Geany - There are themes to match.  These are changed through the Geany program under "view" - "change color scheme" <br/>
- Conky net speed (when uncommented) -  Use: __ls /sys/class/net/__ in a terminal to determine which wired/wireless network you have, <br/>
and replace "wlp2s0" with yours. <br/>
- Printer - Setup entry in the menu under utilities. <br/>
- Lightdm - Configuration settings in the menu. <br/>

Also look under the "Toggles" section in the menu for some instant changes to different items as well.

There is a discussion forum above on Sourceforge as well if you have suggestions or questions.
https://sourceforge.net/p/lilidog/discussion/

### Instructions for building your own if you so choose:

For all the inner workings of Lilidog, and directions to build your own if you so choose:
https://github.com/sleekmason/Lilidog
Forum Link: https://www.forum.lilidog.org/

Contact info: sleekmason@gmail.com

### Good Luck!

## Lilidog

[![Lili.png](https://i.postimg.cc/hjy8qYS8/Lili.png)](https://postimg.cc/5YzQBnQj)


