# FreeCAD Extension Manager

## Description

This project is an attempt to improve management of FreeCAD Extensions repositories.

## Install

### Git
```
cd ~/.FreeCAD/Mod
git clone https://github.com/mnesarco/FreeCAD_ExtMan.git ExtMan
```
Restart FreeCAD

### Zip
```
cd ~/.FreeCAD/Mod
curl -LOk https://github.com/mnesarco/FreeCAD_ExtMan/archive/master.zip
unzip master.zip
mv FreeCAD_ExtMan-master ExtMan
```
Restart FreeCAD



| :warning: WARNING: This project is in active development and it is not ready for final users. |
| --- |

## Python Requirements

* python3-pyside2.qtwebchannel
* python3-pyside2.qtnetwork
* python3-pyside2.qtwebenginecore
* python3-pyside2.qtwebenginewidgets

## Core Classes

![Classes](https://github.com/mnesarco/FreeCAD_ExtMan/blob/master/Resources/docs/core-classes.png)

## UI Rendering

![Sequence](https://github.com/mnesarco/FreeCAD_ExtMan/blob/master/Resources/docs/gui-cycle.png)
