# Tools

## Bake

![type:video](source/videos/baking.mp4)

**Baking** is one of the features of **HAS Paint**. You can easily bake various maps by following these steps:

1. Optionally select **High** objects.
2. Optionally select **Low** objects. Or currently selected object will be used automatically
3. Choose to use Cage if needed. An automatic cage will be created for you.
4. Choose which maps to bake from the list below:

<div class="nice-text-box">
  <h3>Ambient Occlusion</h3>
  <p>
    The Ambient Occlusion map uses a shader setup that is assigned to source object, you can control the AO distance in settings for this map. This method provides a fast and noise-free AO map.
  </p>
</div>
<div class="nice-text-box">
  <h3>Curvature</h3>
  <p>
    To bake Curvature, the add-on uses a shader and geometry nodes setup that applies directly to the source object. In settings for this map you can use Subdivision slider, to find what is best for you. Be causios with high subdivision as it can crash or take a long time to process.
  </p>
</div>
<div class="nice-text-box">
  <h3>Object Normal</h3>
  <p>
    The Object Normal map uses a shader setup that is assigned to source object. Creates normalized World/Object Normal Map.
  </p>
</div>
<div class="nice-text-box">
  <h3>Object Position</h3>
  <p>
    The Object Position map uses a shader setup that is assigned to source object. Creates normalized Object Position map.
  </p>
</div>
<div class="nice-text-box">
  <h3>Height</h3>
  <p>
    The Height map utilizes a geometry group assigned to source object to calculate the height difference between the high-poly and low-poly meshes. This allows you to bake height data without needing to use tessellation, keeping performance efficient. Requires Source(High) Object
  </p>
</div>
<div class="nice-text-box">
  <h3>Diffuse</h3>
  <p>
    The Diffuse map is captured from source object material. Requires Source(High) Object
  </p>
</div>
<div class="nice-text-box">
  <h3>Emission</h3>
  <p>
    The Emission map is captured from source object material. Requires Source(High) Object
  </p>
</div>

## Quick Edit

![type:video](source/videos/screentool.mp4)

The **Quick Edit** tool is an enhanced version of the default Blender Quick Edit feature. It allows you to create a quick screenshot of the current view to be edited in an external editor, and then reproject the edited image back onto the model from the saved view.

- Control the **screenshot size** for better quality.
- **Save multiple views** to edit and return to them later.
- Reproject saved projections efficiently, making texture corrections easier.

## Mask Tools

![type:video](source/videos/masktool.mp4)

**Mask Tools** allow you to select polygons based on their distance from the camera. This is particularly useful for complex models where you want to focus your painting on specific areas without affecting other parts of the mesh.

## Paint Tools

![type:video](source/videos/paintby.mp4)

**HAS Paint** offers several methods for quickly painting on your model:

- **Face**: Draw By Faces.
- **UV**: Draw By Connected UVs
- **Part**: Draw By Connected Parts

---
