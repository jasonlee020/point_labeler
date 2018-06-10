## Version 1.0 ##

[x] Visibility/Filtering of labels.
  - use vertex shader with transform feedback to update visibility
[x] Label only visible points.
[x] Save labels of unloaded point clouds on forward/backward automatically.
[ ] Polygon labeling: non-convex simple polygons.
  - ear cutting and use updateLabels shader for polygon labeling. [x]
  - use texture for representation of triangulated polygon.
[ ] Segment-based labeling: use grid-based segmentation to find segments, which can be selected for labeling.
[ ] Filter labels by category. Have category "Last used" that includes all lately used labels.
[ ] Use color from images to colorize points.
[ ] Draw oultine (2d) of brush for better control of labeling with brush.
[ ] moving/static labeling (bit in labels?)
[x] save on quit.
[x] min/max range of points in laserscan.


## Future work
1. integrate pcp (?)