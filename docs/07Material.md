# Material

There are three available shader presets that you can use:

1. **Principled BSDF**: This is the default **Physically Based Rendering (PBR)** material.

2. **Unlit**: This preset only uses **Diffuse** and **Alpha** channels, which is ideal for hand-painted textures or stylized art that doesn’t require lighting interactions.

3. **Custom**: This preset doesn't alter the current material settings, allowing you to fully customize your shader. This is useful if you have a custom node setup that you would like to use instead of the pre-defined options.

## Options
Each material assigned or created with **HAS Paint** is stored within the add-on. Each material is assigned a unique name known as a "set," which allows for easier management and identification of different materials used in your project.

## Preview Mode
**Preview Mode** allows you to preview each type of image used in the material, such as **Diffuse**, **Roughness**, and others. This makes it easier to verify how each map is affecting the final material appearance, and to identify any adjustments that need to be made.

## Material Actions
This menu can be found on top of layers list

- **Combine All Layers**: Merge all layers in the material to one layer.
- **Resize All Layers**: Change the resolution of all layers within the material.
- **Setup Scene**: Configure the scene settings.
- **Delete All Layers**: Remove all layers from the current material.


## Material Options

<div class="nice-text-box">
  <h3></h3>
  <ul>
    <li><strong>Shader</strong>: 
    <ul>
      <li><strong>Principled BSDF</strong>: A physically-based shader suitable for realistic materials.</li>
      <li><strong>Unlit</strong>: Uses only diffuse and alpha, ideal for hand-painted or stylized looks where lighting is not needed.</li>
      <li><strong>Custom</strong>: A custom shader that can be adapted to fit specific needs.</li>
    </ul>
    </li>
    <li><strong>Maps Setup</strong>: Each material can have a unique set of maps assigned.</li>
    <li><strong>Texture Filtering</strong>: Control the type of texture filtering.</li>
    <li><strong>UV Channel</strong>: Specify the UV channel that will be used for all textures in the material. Empty by default will use default UVs</li>
    <li><strong>Height Intensity</strong>: Adjust the height intensity to affect the entire material.</li>
    <li><strong>Transparency Mode</strong>: Choose how the material handles transparency:</li>
    <li><strong>Alpha Setting</strong>: Choose whether to use the Diffuse Alpha as the material's opacity.
      <ul>
        <li><strong>Opaque</strong>: No transparency, the material is fully solid.</li>
        <li><strong>Hashed</strong>: Uses a dithered approach to simulate transparency.</li>
        <li><strong>Blending</strong>: Uses smooth blending for transparency.</li>
        <li><strong>Clip</strong>: Sharp, transparency based on an alpha threshold.</li>
      </ul>
    </li>
    <li><strong>Texture Size</strong>: Define the default texture resolution for the material. It does not affect already create textures</li>
    <li><strong>Default Material Values</strong>: Define base values for current material</li>
  </ul>
</div>

---
