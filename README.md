# IQE/IQM 3D Asset Tools

## Credits:

- Original author: [Tor Andersson](https://github.com/ccxvii)
- Original repo: [asstools](https://github.com/ccxvii/asstools)

## Description:

A set of tools for manipulating 3d assets in IQE/IQM format.

- assview -- an Open Asset Import Library based model viewer using OpenGL and GLUT
- iqeview -- an IQE model viewer using OpenGL and GLUT

- assiqe -- an Open Asset Import Library based IQE exporter

- iqm_import.py -- a python importer for IQM and IQE models
- iqm_to_iqe.py -- convert binary IQM back into textual IQE format

## Differences:

First of all, i don't really do plugins for blender and anything like that. Just wanted to have fixed solution for my needs at my hands if i'll need it.

I implemented 2 fixes compared to original repo:

- First is to fix importing itself by updating 1 flag (https://github.com/ccxvii/asstools/issues/8) Thanks to [eLTehh](https://github.com/eLTehh)
- Second is to fix mirroring in UV's. I don't really sure if it needed. I used this tools to import models from SAO:HR with [SAO Viewer tool](https://forum.xentax.com/viewtopic.php?t=17714).

If you need mirrored UV's just uncomment this line: https://github.com/AymanDev/AssetTools/blob/master/iqe_import.py#L676

## Installation

1. Go to https://github.com/AymanDev/IQE-IQM-3D-Asset-Tools/releases and download `iqe_import.zip`
2. Go to your addons folder in blender which is located here: `C:\Users\{username}\AppData\Roaming\Blender Foundation\Blender\{version}\scripts\addons` where is `{username}` will be your name of the PC and `{version}` will be version of the blender you use`
3. Unpack all files from zip in addons folder
4. Then in blender `Edit -> Preferences -> Add-ons` and search for IQE and select checkboxes for features you need
5. That's it you can now import `.iqe` models

## License:

BSD unless otherwise stated.
