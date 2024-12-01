# Layers

## Layer Types

<div class="image-box">
  <img src="/source/images/layertypes.png" alt="layer action image">
  <div class="text-box">
    4 Layer types available
  </div>
</div>


<div class="nice-text-box">
  <h3>Paint Layer</h3>
  <p>
    The Paint Layer is an empty layer, best used for directly painting textures onto your mesh. By default, it affects the Diffuse channel, but you can change this to target other channels as needed.
  </p>
</div>
<div class="nice-text-box">
  <h3>Fill Layer</h3>
  <p>
    The Fill Layer is a layer with a color input, ideal for quickly filling areas, applying solid colors, or configuring specific channels.
  </p>
</div>
<div class="nice-text-box">
  <h3>PBR Layer</h3>
  <p>
    The PBR Layer is designed to allow painting across multiple channels that are commonly used in physically based rendering (PBR). You can paint details for channels like Diffuse, Metallic, Roughness, Normal, Height, etc  that can be defined in Material Settings
  </p>
</div>
<div class="nice-text-box">
  <h3>Folder Layer</h3>
  <p>
    The Folder Layer is used for organizing and managing multiple layers. You can group related layers under a folder to keep your project organized. Filters added will be applied to all layers in this folder.
  </p>
</div>

## Layer Textures
In **HAS Paint**, paint layers are represented by textures. The textures created with this add-on have the following properties:

- **Alpha Premultiplied**: All textures have alpha premultiplication, meaning that transparency is accounted for color values, which helps ensure proper blending of textures. Can be changed in [Layer Actions](02_1LayerActions.md)

- **Color sRGB**: The textures use sRGB color space, which gives accurate color representation and blending in the 3D viewport. Can be changed in [Layer Actions](02_1LayerActions.md)

All new textures are created with a default size of **1024x1024** pixels unless changed in the [Material Settings](07Material.md).

## Layer Layout
<div class="image-box">
  <img src="/source/images/layerlayout.png" alt="layer action image">
</div>
Each layer has properties that allow you to control its behavior and appearance:

- **Image/Color Preview**: Layer image preview or Color property that can be edited if no image assigned
- **Select Layer**: Select layer for painting and editing properties/filters/sub-layers.
- **Opacity Control**: Adjust the opacity of the layer to blend it with layers below.
- **Blending Mode**: Set the blending mode (e.g., Mix, Multiply, Overlay) to control how the layer interacts with those beneath it.
- **Visibility**: Toggle the visibility of the layer to hide or show it as needed.
- **Layer Name**: Visible name for layer.
- **Layer Actions**: Operations with layer. Details in [Layer Actions](02_1LayerActions.md)
- **Move Layer**: Change layer order

---
