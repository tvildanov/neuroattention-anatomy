# Female anatomy GLBs (female-reproductive.glb, placenta.glb, breasts.glb)

Derived from the **HuBMAP CCF 3D Reference Object Library**, VH_Female v1.2 (reproductive
organs, placenta) and v1.3 (mammary glands), which are built on the National Library of
Medicine Visible Human Female dataset.

- Source: https://github.com/hubmapconsortium/ccf-3d-reference-object-library
- License: Creative Commons Attribution 4.0 International (CC BY 4.0)
- Citation: Browne, K., Schlehlein, H., Herr II, B. W., Quardokus, E., Bueckle, A.,
  Börner, K. (2022). HuBMAP CCF 3D Reference Object Library.

Processing: organ sub-meshes renamed to atlas tokens (Uterus/Cervix/Ovary.l/.r/
Fallopian tube.l/.r/Vagina/Placenta/Breast.l/.r), rigidly aligned (uniform scale 0.97 +
translation) from VH-Female CCF space into the Z-Anatomy normalized atlas frame via a
pelvis-to-pelvis bounding-box match, DRACO-compressed. No rotation/flip (axes coincide:
+X=left, Y=up, +Z=anterior). See docs/female-anatomy-inventory.md in the site repo.
