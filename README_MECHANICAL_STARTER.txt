BR2 V2 Wide U-shaped KiCad mechanical starter

Source geometry:
- Alchitry_Br_V2_Wide.step uploaded by user
- Header-hole centers extracted directly from cylindrical geometry.
- All mating breakout/header holes are on a 2.54 mm pitch.

Mechanical mapping used (STEP top-view orientation):
- Control: x=3.23..15.93 mm, rows J17/J18/J19/J20 at y=47.76/50.32/52.88/55.44 mm.
- Bank A: x=19.74..52.76 mm, rows J7/J8/J9/J10 at y=47.76/50.32/52.88/55.44 mm.
- Bank B: x=19.74..52.76 mm, rows J11/J12/J13/J14 at y=-10.44/-7.90/-5.36/-2.82 mm.
- Pin 1 is at the left end of each row in this STEP orientation.

KiCad coordinates are STEP XY shifted by +30 mm in X and +30 mm in Y.

Board outline:
- Conservative rotated-U / C shape around the three header regions.
- The central area is deliberately open.
- IMPORTANT: Io V2 clearance has NOT yet been proven with an Io V2 STEP model. Verify the center opening and vertical stack clearance before fabrication.

The mechanical mating headers are placed at exact STEP-derived positions. U1, R1-R3, C1, and J21 are parked outside the outline on the right so they can be placed after clearance is finalized.

If Update PCB from Schematic is used later, KiCad may ask to relink footprints. Relink by reference designator (J7-J21, U1, R1-R3, C1).
