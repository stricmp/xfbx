<div align="right">
<a href="http://aritri.com/" target="_blank">
	<img alt="ARITRI.COM" width="100px" src="https://raw.githubusercontent.com/stricmp/dread-series-postmortem/master/images/tridh.gif"/>
</a>
</div

#

# XFBX

## Introduction

This is an add-on to improve the workflow between __Blender__ and __Unreal Engine 4__.

Specifically tailored to work with _UE4's FBX Static Mesh Pipeline_, it has been used by fellow _Environment Artists_ at [__Digital Happiness__](http://digitalhappiness.net "Digital Happiness")  to develop their games.

Requires Blender 2.80 or later.

## Installation

Clone or download this repository to your workstation and locate the __xfbx.py__ file.

Open __Blender Preferences__ by clicking the ___Edit___ menu and select ___Preferences...___

In __User Preferences__ select ___Add-ons___ then press ___Install Add-on from File...___ and select the __xfbx.py__ file.

Now the add-on will be listed in __User Categories__ and you can enable it by checking the checkbox.

If you want this add-on to be enabled on restart, just press ___Save Preferences___.

## Basic Usage

Press __T__ to bring the Tools panel up in Blender's 3D Viewport, then expand XFBX panel and click __Initialize__ button.

Select a directory to save the exported fbx files into. If your workflow is like ours, you will only need to set this once :-)

Now select the object you want to export and then press __EXPORT__ button.

If you enable the __Center Pivot__ option then the exported object will be located at world's origin on import.

If you enable the __Also Export Collision__ option then the add-on will search for any object which adheres to _UE4's FBX Static Mesh Pipeline_ naming convention and will include it automatically in the export.

Use __Include Tangent__ option if you also want to include binormal and tangent vectors data on export.

## About UE4's FBX Static Mesh Pipeline

See https://docs.unrealengine.com/en-us/Engine/Content/FBX/StaticMeshes


