HIGH-RISE TOWER — SketchUp model
=================================

True-scale architectural model of the axonometric sheet
(project: HIGH-RISE TOWER, drawing: AXONOMETRIC).

OPEN IN SKETCHUP
----------------
SketchUp Pro, Studio, or SketchUp Make (desktop):

  1. File → Import…
  2. Set the file type to "COLLADA File (*.dae)".
  3. Choose High-Rise-Tower.dae
  4. Import. Leave "Merge coplanar faces" OFF so the
     mullions and spandrels stay crisp.
  5. Camera → Parallel Projection, then orbit to a
     front-right axonometric to match the sheet.

The COLLADA file is Z-up, in inches (SketchUp's native unit),
with a correct unit tag. Imported into a meters template it is
still true size. Confirm with Window → Model Info → Units.

If the glass comes in opaque, open the Materials panel,
select "Glass-Vision" and "Glass-Lobby", and set opacity
to about 40%. The names are already assigned.

ALSO INCLUDED
-------------
  High-Rise-Tower.dxf   AutoCAD 3D faces, Z-up, meters.
                        SketchUp Pro: File → Import → DXF.
  High-Rise-Tower.obj   Same mesh, Z-up, meters (+ .mtl).
                        SketchUp Pro OBJ import: set units to meters.
  High-Rise-Tower.kmz   Same COLLADA wrapped for File → Import → KMZ.

OUTLINER GROUPS
---------------
  Site_Plaza, Site_Joints, Site_Dropoff
  Landscape_Planters, Landscape_Planting
  Podium_Walls, Podium_Fins, Podium_Glazing, Podium_Terrace
  Entrance_Portal, Entrance_Canopy, Entrance_Lobby
  Tower_Corner_Piers, Tower_Mullions, Tower_Spandrels, Tower_Glazing
  Floor_Plates
  Roof, Roof_Parapet
  Entourage_Figures, Entourage_Figures_B

Delete the two Entourage groups if you do not want scale figures.

DIMENSIONS (meters)
-------------------
  Tower plate          32.00 × 32.00
  Tower floors         22 @ 3.60  =  79.20 shaft
  Vision glass         2.58 high,  5 bays × 2 lites
  Typical lite width   see model (module is equal on all faces)
  Corner piers         1.20
  Podium plate         46.00 × 45.50
  Podium               4 storeys, ground 5.00 + 3 × 4.20  =  17.60
  Front setback        9.50    side 7.00    rear 4.00
  Entrance opening     12.80 wide, recessed 1.70
  Canopy               15.20 × 6.40 projection, soffit at 3.85
  Roof slab            0.42 thick, cornice 0.38
  Parapet              1.35 high × 2.85 deep (the inner roof rectangle)
  Overall height       98.57  (plaza surface to parapet coping)
  Site                 82.00 × 82.50, slab 0.60 thick
  Model origin         southwest corner of the site slab, plaza at Z = 0

Grid bubbles on the sheet (A–D, 1–5) are drawing annotations,
not geometry, and are not in the model.

The back and the far side repeat the same curtain wall and fin
pattern so the model is complete, not just the two faces in the view.
