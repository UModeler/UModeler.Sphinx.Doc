############################
UModeler 2023
############################

Version 2.10.15 | Dec. 21, 2023
=================================
- Fixed an issue where selected faces would disappear in the UV tool upon saving a scene.
- Added a static delegate named 'BridgeTool.CallbackAfterBridgeToolExecuted' that is triggered after the execution of the bridge tool.

Version 2.10.14 | Dec. 07, 2023
=================================
- Fixed an issue where null reference exception occurs when a line or a curve is drawn in the Prefab mode.
- Added "Disable Mesh Read/Write" property in the Local Settings tool.

Version 2.10.13 | Nov.07.2023
=================================
- Added a feature to align multiple polygons and islands when using tools from the alignment group in the UV Editor.

Version 2.10.12 | Oct.06.2023
=================================
- Fixed a bug in the Pivot To Center Tool where errors occurred when executing Top Center and Bottom Center.
- Fixed an issue where the save indicator did not appear when modified in the Local Settings Tool.
- Fixed a bug where the Export Tool in UVEditor did not work properly in HDRP mode.
- Fixed a problem that arose when some objects were not deleted during script reloading.

Version 2.10.11 | June.29.2023
=================================
- Fixed a bug related to the rect selection where vertices behind the camera were selected.
- Fixed the issue where there was a problem with UV movement in the UV Editor when the texture size was different horizontally and vertically.

Version 2.10.10 | June.02.2023
=================================
- Added a new feature called [Snap Angle] in the Cut tool.

Version 2.10.9 | Apr.28.2023
==================================
- Fixed an issue where editing a mesh with very small and invalid polygons caused exception errors and performance issues.

Version 2.10.8 | Apr.21.2023
==================================
- Fixed NullReferenceException error occurred where Select by Selected Polygons button is clicked.

Version 2.10.7 | Apr.18.2023
==================================
- Fixed another NullReferenceException issue in the CheckAllUModelerPrefabInstance() method. This issue occurred in a level containing many prefab UModeler instances created with an older version of UModeler.

Version 2.10.6 | Apr.10.2023
==================================
- Fixed a NullReferenceException issue that occurred while setting a prefab instance during the loading process.

Version 2.10.5 | Mar.24.2023
==================================
- Fixed an issue where polygon counts got doubled when UModelerizing with "Create Smoothing Groups as UModelerize"

Version 2.10.4 | Feb.27.2023
==================================
- Fixed an issue where polygons to which smoothing groups are assigned are invisible.

Version 2.10.3 | Feb.23.2023
==================================
- Fixed a flickering issue caused in a UModeler mesh to which the smoothing group and lightmaps are applied.
- Fixed an issue where some vertices of Capsule and Cylinder shapes are detached when they are moved.

Version 2.10.2 | Feb.2.2023
==================================
- Fixed a bug where UV settings like Shift, Scale, Rotate etc in the UV tool are reset when a polygon is split using Loop Slice tool.
- Fixed an issue where UVs coordinates on the polygons with smoothing groups aren't updated in real time while you change the UV tool parameters like Shift, Scale and Rotate etc.

Version 2.10.1 | Jan.31.2023
==================================
- Fixed the vertex selection issue where the occluded vertices that should not have been selected were selected using the rectangle selection

Version 2.10.0 | Jan.25.2023
==================================
- Fixed an issue where ``Error : mainRenderableMesh is Null`` error occurred when a mesh was saved.
- Fixed displaying different scale UIs of the transform component.
- Fixed an issue occurred in Unity 2022.2 where undoing an 'Unpack Prefab' action shows a prompt "You can't add a UModeler component in a Prefab instance" and selecting 'OK' crashes the Editor