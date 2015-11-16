# Configuration #

On WinXP/Vista/7 the main configuration file is `aseprite.ini`
which is saved in the same folder of `aseprite.exe`. In this way Aseprite is a portable application, i.e. you can
transport a copy of the program in a USB flash drive.

On GNU/Linux, the configuration file is `~/.asepriterc`, and the `data/`
files are searched in these locations (in priority order):
```
$HOME/.aseprite/
../share/aseprite/
./data/
```

The following is a list of some configuration files that you could
modify to customize Aseprite:
```
aseprite.ini          Program configuration
data/gui.xml          Menus, shortcuts, and tools
data/convmatr.def     Convolutions matrices
data/skins/*.*        Aseprite skins
data/widgets/*.xml    XML files with dialogs
```