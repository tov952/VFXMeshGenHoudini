# VFXMeshGenHoudini
VFX Mesh Generator Houdini Working Files

The VFX Mesh Generator relies on Houdini Engine to produce VFX Meshes, COPS-generated VFX Textures, Master VFX Materials and a template BP to quickly prototype real-time VFX!


If you'd just like to test this without accessing the source:

https://drive.google.com/file/d/1NNyQqCunIeXmn-c_Ie3wWwOsVbvhpmNY/view?usp=sharing

VFX Mesh Gen Explainer Video:
https://www.artstation.com/artwork/b5306E

Content:
- houdiniProjectFolder
  - HDA (contains the HDA)
  - Preset (Contains preset to simplify vfx dev in houdini)
  - Final HIPLC file (For further development of the HDA)
- TestEngine (Contains UE asssets that should be imported into a fresh project)
- VFXMeshExplainer (Review to understand how this tool works!)

# Pre-requisite

File above downloaded and unzipped!

You should already have Houdini Engine Indie V18.0.460 running on UE 4.25.0 or 4.25.3!

You should have SideFXLabs Release 460 installed!


# To Test:

1.Install "hda/VFXMeshGenerator.hda" (or "hda/VFXMeshGenerator.hdalc" depending on your houdini version) into Houdini Asset Library

2.Import "TestEngine" assets into your unreal project!

3.Choose to Instantiate this asset:

![image](https://user-images.githubusercontent.com/59757164/171695462-f9e1f51f-662a-4811-978c-928002683287.png)

4.Start playing with it! :)
