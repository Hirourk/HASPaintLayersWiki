# First Steps

## Setup

After installation, you will find the **HAS Paint Layers** panel on the right side of the 3D viewport. Make sure you have selected a mesh before proceeding.

To get started, press the following button in the **HAS Paint Layers** panel:
![setmtl](source/images/setup_mtl.png)
This will initialize the material setup for your selected mesh.



After setting up the material, you can begin by adding [Layers](02_0Layers.md). Once the layers are added, you can start working on your textures right away.

If you need more control, explore the [Material](07Material.md) page.

Another important element in the **HAS Paint Layers** panel is the:
![Welcome_Page_Image](source/images/setup_scene.png)

The **Setup Scene** button adjusts the **View Transform** of the current scene to **Standard**. It is important that colors are displayed accurately, especially for tasks like using eyedroppers or projecting images. Without this setup, colors might appear different than expected, potentially causing confusion when sampling colors or projecting images.

## Understanding HAS Paint Layers

**HAS Paint Layers** is a material setup add-on designed to simplify the process of creating node groups and configuring a basic shader. It automates the initial steps required for painting and texture creation, making it faster to get started with your project.

Each layer added through **HAS Paint Layers** represents a texture, color or node. All is stored within the Blender scene. This means you can manage, re-use, and export textures as needed for other parts of your workflow.

### Important Note on Node Groups
Avoid editing the node groups created by **HAS Paint Layers**. Directly modifying these node groups can result in unexpected errors or could lead to the overwriting of any custom changes you've made. If customization is needed, always make copies of the node groups first to ensure that the original functionality remains intact.

---
