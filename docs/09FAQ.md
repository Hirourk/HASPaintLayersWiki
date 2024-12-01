# FAQ

## I See Only One Texture
- If you haven't already: On the HAS Paint Layers panel, press the button shown below. This will switch you to shading mode.
![setupscene](source/images/setup_scene.png)

- In the 3D Viewport, select either Material Preview or Render Preview from the shading options at the top-right corner.

## My model is pink
A pink model typically means there’s an issue with the materials or textures. Common causes include:

- **Missing Textures** Ensure all textures assigned to your material are properly loaded and accessible.

- **Too Many Textures** Check if your material has exceeded the texture slots supported by your GPU. See [More](08Issues.md)

## I can't paint on textures
- **Correct Layer Selection** Make sure you are trying to paint on a Paint Layer and that it is selected in the HAS Paint Layers panel.

- **Masks** Verify if a mask is applied. If so, ensure it’s correctly configured and not blocking your painting area.

- **Camera Distance** Move the camera farther from the model. Being too close can sometimes prevent proper painting.

- **Polygon Masking** Check if Mask by Polygons is enabled. Disable it if it’s not needed.

Check if any mask is applied

Camera is too close to the model

Check if mask by polygons is off

## I Deleted a Node Group or Texture, and Now Something Doesn't Work
If you accidentally deleted a node group or texture. The addon will automatically recreate any missing node group. And you can create and reassign textures in HAS Paint Layers panel manually or create a new one. Changing the visibility of a layer or switching the material type will trigger the shader to rebuild, restoring its functionality.

## I Have Issues With Textures/Texture Painting
HAS Paint Layers created to work with shader node setup, baking, and tools that doesn't affect native texture painting in any way. If you're new to texture painting in Blender, most issues can usually be resolved by understanding how Blender’s texture painting system operates independently of this add-on.

Before troubleshooting, it's important to familiarize yourself with how texture painting works in Blender itself, as many issues arise from misunderstanding the fundamental aspects of this workflow. Once you're comfortable with that, you should find it easier to use the add-on without conflicts.

## I still have a question
You can ask me questions here

Please report bugs here 

---