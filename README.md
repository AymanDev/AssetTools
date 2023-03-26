# IQE/IQM 3D Asset Tools

### Credits:

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

- First is to fix importing itself by updating 1 flag (https://github.com/ccxvii/asstools/issues/8)
- Second is to fix mirroring in UV's. I don't really sure if it needed. I used this tools to import models from SAO:HR with [SAO Viewer tool](https://forum.xentax.com/viewtopic.php?t=17714).

If you need mirrored UV's just uncomment this line: https://github.com/AymanDev/AssetTools/blob/master/iqe_import.py#L676

License: BSD unless otherwise stated.
