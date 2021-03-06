# dolphin-meld-service-menu

![Image 1](https://raw.githubusercontent.com/ivavis/dolphin-meld-service-menu/master/screenshot/meld-compare-menu-1.png)

[Opendesktop.org download link](https://www.opendesktop.org/p/1100882)

[store.kde.org download link](https://store.kde.org/p/1100882)

## Description: 

Simple service menu for file comparison with Meld.
Supports files and directories in 2-way or 3-way compare mode.

### Actions
* **Compare each other:** select 2 or 3 files or directories to compare
* **Select for compare:** Save one or more file/directory paths for compare
* **Compare:** Compare selected element with previously saved paths


### INSTALLATION
place *dolphin_meld_servicemenu.desktop* file in *~/.local/share/kservices5/*

For a system-wide installation place the file in */usr/share/kservices5/*

Logout and login or execute in a console
```bash
kbuildsycoca5
```

#### NOTE
These installation paths are valid for Kubuntu 18.04.

For the full list of installation paths for your system execute in a console 
```bash
kde4-config --path services
```
and check your output

;)


## CONTRIBUTIONS
### Translations
* Dutch and German translations picked from [naraesk dolphin-service-menu-meld repository](https://github.com/naraesk/dolphin-service-menu-meld).
  KUDOS to [@naraesk](https://github.com/naraesk)
