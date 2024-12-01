# File

## Saving
**Auto Save Toggle Button**: **HAS Paint** allows you to save textures automatically whenever the scene is saved. This feature helps prevent loss of textures if Blender shuts down unexpectedly.


## Export Textures
**HAS Paint** allows you to export created textures as individual images or as an **ORA** (Open Raster Archive) file. ORA is an open-source layer file format compatible with programs like **Krita** and other open-source graphic editors.

<div class="image-box">
  <img src="/source/images/exportoptions.png" alt="Export options and template example">
  <div class="text-box">
    Export options and template example
  </div>
</div>

Each map can be packed using different channels. For example you can create RMO(Rougness, Metallic, Occlusion) using R+G+B+A.
To export your textures, follow these steps:

1. Navigate to the **File** menu on top of the addon.
2. Click on the **Export Textures** button, which will open the path selection window.
3. Choose a name for your export.
4. Use presets or create new, for different channels as needed.
5. Save presets for easy reuse in future projects.

### Naming Conventions
You can use specific properties in the naming to ensure consistency:

- Allowed properties: `(obj)`, `(mtl)`, `(file)`, `(set)`
- Example: `(obj)_Diffuse` will be saved as `YourObject_Diffuse`.
- Example 2: `(obj)_(mtl)_(file)_(set)_D` will be saved as `Cube_Material_Untitled_Set01_D`.

This flexibility helps you maintain a clean and consistent file structure, especially in projects with multiple objects and textures.

## Export ORA
When exporting as an **ORA** file, be aware of certain limitations:
- All **layer filters, masks, and other data** will be collapsed into a single image.
- Images will be exported while maintaining **blending modes** and **opacity**. However, **Passthrough** and **Normal** blend modes will be converted to **Mix Blending**.

While there are limitations, the ORA export is still very useful for taking layered textures into external programs like **Krita** for further editing.

## Import ORA
If you have saved an ORA file, you can import it into **HAS Paint** as layers. This feature makes it easy to move your projects between HAS Paint and other software without losing the basic structure of your layers.

## Cleanup HAS Data
**Clear Unused HAS Data** will clear only unused textures, node groups, and internal data created by HAS Paint Layers

**Remove All HAS Data** will remove all data created by this addon.

Note! This affects only data blocks (textures, node groups) that start with ".HAS_", "HASM" or "HAS"

## Set Collection
**HAS Paint** stores all materials in sets, allowing you to unassign materials from **HAS** and rename sets for better management.

---
