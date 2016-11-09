# Stereographic-projection

In geometry, the stereographic projection is a particular mapping (function) that projects a sphere onto a plane. The projection is defined on the entire sphere, except at one point: the projection point. Where it is defined, the mapping is smooth and bijective. It is conformal, meaning that it preserves angles. It is neither isometric nor area-preserving: that is, it preserves neither distances nor the areas of figures.

Source : [wiki](https://en.wikipedia.org/wiki/Stereographic_projection)

---

The script implements the inverse of the stereographic projection: it maps a plane onto the sphere.
It replaces the active bm.mesh with a mesh on the sphere then extrudes this to a solid for 3D printing.

Tested Blender 2.77

- stereo_proj.py : replaces the active bm.mesh with a mesh representing inverse of the stereographic projection
- grid.py :  Blender script to make a pair of meshes accepted by [stereo_proj.py](https://github.com/macbuse/Stereographic-projection/blob/master/stereo_proj.py)

---

![before](https://github.com/macbuse/Stereographic-projection/blob/master/flat%20mesh.png)

![after](https://github.com/macbuse/Stereographic-projection/blob/master/modified%20mesh.png)



