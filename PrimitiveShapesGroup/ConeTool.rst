.. |Icon_PrimitiveShapes_Cone| image:: /images/Icon_PrimitiveShapes_Cone.png
   :scale: 100 %

################################################
Cone Tool |Icon_PrimitiveShapes_Cone|
################################################   

Creates a cone

Steps
------
1. Select ``Cone Tool``
2. Drag the mouse on a floor or an another polygon to draw a disk.
3. Release ``LMB`` and move the mouse cursor in a normal direction to raise the height.
4. Click ``LMB`` to stop raising.
5. Type the count of edges in ``Segment`` field, radius in ``Radius`` field and height in ``Height`` field if necessary.
6. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

Interface
-------------
``LMB Drag``
 Draws a disk.
 
``SPACE``
 Completes creating a cone
 
``ESC``
Cancels creating a cone.

Properties
---------------
Select Only Visible
 If on, the shape can be built on only a visible polygon. Namely backfaced or occluded polygons are excluded.
 
Floor Height
 The height of the floor where the primitive shape is built by LMB Dragging.
 
Segments
 The count of side faces

Radius
 A radius of a cone

Height
 A height of a cone

Angle Snap
 When you drag the mouse with this property on, the disk’s direction will snap to every 90 degree.

Auto Smoothing
 Creates smoothed surfaces which have a common smoothing group.

Border Check
 If this is enabled, the ray cast will run and it checks if the created cone is beyond the other polygons. It might cause a stop for a second at the beginning.

Glue
 The cone with this property enabled will be glued to the polygon where it started to be created. It means that the hidden part of the floor polygon by the created cone is removed.
 
.. figure:: /images/UModeler_Cone_OnTheFloor.jpg
   :scale: 95 %

   Cone created on the floor.
   
.. figure:: /images/UModeler_Cone_OnPolygon.jpg
   :scale: 95 %

   Cone created on the other polygon.