# Blender-Molecular-Script

This is my molecular python script for blender. Forked from [scorpion81/Blender-Molecular-Script](https://github.com/scorpion81/Blender-Molecular-Script)

## Prepare 

Make sure to use python version 3.7.4, or run directly with python in the blender directory.

* Run `python make_release.py`, then you might see a `.zip` file.
<br /><br />

## Installation

### GUI Usage

* Inside Blender, go to `Edit` -> `Preferences...` -> `Add-ons` -> `Install...` and select the `.zip` file. 


### Script Usage via Adding Module Search Path

1. Unzip the `.zip` file.
2. ```python
    import sys
    sys.path.append("<module path>")
    import molecular


### Script Usage via Copy Module to `addons_contrib`

1. Unzip the `.zip` file.
2. Copy the `molecular` folder to `C:\Program Files\Blender Foundation\Blender 2.83\2.83\scripts\addons_contrib` (Windows).

*WARNING*: *DO NOT* install the addon via both ways or the two versions are mixed up and cause errors. 

<br /><br />
## Demo
1. Modify the module search path in the `molecular_script.py`
2. Run `blender -P molecular_script.py`
<br /><br />
