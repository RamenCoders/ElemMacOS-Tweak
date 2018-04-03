# ElementaryOS Sierra -Tweak Gtk


_*Contains appearance correction for GTK applications_


![First Screenshot](https://raw.githubusercontent.com/btd1337/eOS-Sierra-Gtk/master/screenshots/screenshot1.png)


![Second Screenshot](https://raw.githubusercontent.com/btd1337/eOS-Sierra-Gtk/master/screenshots/screenshot2.png)


![Third Screenshot](https://raw.githubusercontent.com/btd1337/eOS-Sierra-Gtk/master/screenshots/screenshot3.png)


![Fourth Screenshot](https://raw.githubusercontent.com/btd1337/eOS-Sierra-Gtk/master/screenshots/screenshot4.png)


![Fifth Screenshot](https://raw.githubusercontent.com/btd1337/eOS-Sierra-Gtk/master/screenshots/screenshot5.png)


![Sixth Screenshot](https://raw.githubusercontent.com/btd1337/eOS-Sierra-Gtk/master/screenshots/screenshot6.png)


![Seventh Screenshot](https://raw.githubusercontent.com/btd1337/eOS-Sierra-Gtk/master/screenshots/screenshot7.png)



## How to install

### First:
 * Recommended install the La Sierra icon pack a La Capitaine's fork available in https://github.com/btd1337/La-Sierra-Icon-Theme or/and La Capitaine Icon Theme: https://github.com/keeferrourke/la-capitaine-icon-theme.
 * Recommended install San Francisco Fonts, available in https://github.com/RamenCoders/ElemMacOS-Tweak/tree/master/Fonts/SanFranciscoFont-master
 * Recommended install Cairo Dock and the theme Cairo-Dock macOS Sierra Style available in https://github.com/btd1337/Cairo-Dock-macOS-Sierra-Style


### Second:
Clone the repository for folder ~/.themes/

    $ git clone https://github.com/btd1337/eOS-Sierra-Gtk ~/.themes/eOS-Sierra-Gtk

### Third:
Set theme:

    $ gsettings set org.gnome.desktop.interface gtk-theme 'eOS-Sierra-Gtk'
    
### Fourth:
Clone/Download Fonts and Install:

    Download the fonts https://github.com/RamenCoders/ElemMacOS-Tweak/tree/master/Fonts/SanFranciscoFont-master
    then install them, to install multiple fonts system wide: ttf files:

    $ sudo cp ./yourpath/*.ttf /usr/share/fonts/truetype/  
      
   opentype:

    $ sudo cp ./yourpath/*.otf /usr/share/fonts/opentype/
   And then:

    $ sudo fc-cache -fv


### Looking to uninstall the theme instead?
    $ gsettings set org.gnome.desktop.interface gtk-theme 'elementary'
    $ rm -R ~/.themes/eOS-Sierra-Gtk


### Extras:
 * Icons: La Capitaine available in https://github.com/keeferrourke/la-capitaine-icon-theme
 * Dock: Cairo-Dock macOS Sierra Style available in https://github.com/btd1337/Cairo-Dock-macOS-Sierra-Style
 * Wallpaper: macOS Sierra wallpaper macbook available in https://github.com/btd1337/Cairo-Dock-macOS-Sierra-Style/blob/master/images/wallpapers/




#### Improvements are accepted!
