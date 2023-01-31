# MNI Surface Models

These 3D models were constructed from an extended MNI152 template.

## Files

### mni152_surface.vtk

Surface extracted from the MNI152 template.

### mni152_surface_57cm.vtk

Surface extracted from the MNI152 template but shrunk to a circumference of 57 cm. Most EEG caps are manufactured in standard sizes (e.g., suitable for heads with 56, 58, 60 cm circumference). This model should allow for a good fit of a cap with of size 58 cm.

### mni152_surface_57cm_coreg.vtk

Surface extracted from the MNI152 template but shrunk to a circumference of 57 cm. This model includes 14 dents in the surface whose positions in MNI152 space is known exactly. Hence, by digitizing these points, it is possible to get an accurate coregistration between MRI and digitizer space.

To view these models, use for example [ParaView](https://www.paraview.org) or [ParaView Glance](https://kitware.github.io/glance/app/).
