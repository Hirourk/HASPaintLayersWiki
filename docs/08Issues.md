# Known Issues

## Limitations

Due to the way **HAS Paint** utilizes textures as layers, you may encounter some limitations while working with the add-on. Specifically, if you add too many layers, the material can fail to calculate properly, resulting in a **pink color** in the viewport. This pink color indicates missing or broken materials, which is a common issue in Blender when shaders cannot be processed correctly.

The limitations you experience depend largely on the capabilities of your GPU. The more powerful your GPU, the more layers it will be able to handle before running into performance issues.

### Potential Fixes
If you run into these limitations, here are a few potential solutions:

1. **Collapse Layers**: **Collapse layer** can be found in [Layer Action](02_1LayerActions.md) menu. This will apply all filters, textures and masks to single image in layer. It can reduce shader computation time and amount of textures used.

3. **Combine Layers**: Consider merging multiple layers into one. One way is to combine 2 layers using **Combine with layer below** option in Layer Action menu. Another way is to combine all layers into one, using Combine all layers in [Material Action](07Material.md) menu

---