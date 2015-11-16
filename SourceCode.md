## Git Repository ##

You can [browse the source code online](http://github.com/aseprite/aseprite). Or you can clone the official source code git repository from github:
```
git clone git://github.com/aseprite/aseprite.git
cd aseprite
git submodule init
git submodule update
```

## Migrating from SourceForge.net ##

If you have already cloned the git repository from SourceForge, you can switch the origin URL to github with the following command:
```
git remote set-url origin git://github.com/aseprite/aseprite.git
```
## Hacking Aseprite ##

If you want to modify Aseprite source code, please refer to the [Hacking](Hacking.md) section.