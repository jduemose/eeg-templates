# MNI Surface Models

These 3D models were constructed from an extended MNI152 template.

## Files

### mni152_surface.vtk

Surface extracted from the MNI152 template.

### mni152_surface_57cm.vtk

Surface extracted from the MNI152 template but shrunk to a circumference of 57 cm. Most EEG caps are manufactured in standard sizes (e.g., suitable for heads with 56, 58, 60 cm circumference). This model should allow for a good fit of a cap with of size 56-58 cm.

### mni152_surface_57cm_coreg.vtk

Surface extracted from the MNI152 template but shrunk to a circumference of 57 cm. This model includes 14 dents in the surface whose positions in MNI152 space are known exactly. Hence, by digitizing these points, it is possible to get an accurate coregistration between MRI and digitizer space.

To view these models, use for example [ParaView](https://www.paraview.org) or [ParaView Glance](https://kitware.github.io/glance/app/).

### Targets

These are the RAS coordinates of the 13 targets (excluding the inion).

```
nasion   -0.348   77.779  -40.058
rpa      75.564  -10.589  -49.227
lpa     -74.548   -8.055  -51.961
L1      -18.433 -104.513  -43.862
R1       28.035 -105.596  -21.606
R2       47.001  -80.739   53.064
L2      -51.261  -78.908   51.496
R3       64.425  -46.913   58.446
L3      -63.330  -53.636   56.894
L4      -47.365    3.692   69.660
R4       42.257  -17.649   80.919
R5       44.024   45.783   48.697
L5      -43.392   53.902   35.598
```
