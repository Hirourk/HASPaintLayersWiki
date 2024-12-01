# Filters

All layers in **HAS Paint** can be modified with filters. Filters can be added through the action menu, and they serve as a way to manipulate the textures directly, giving you greater control over the final look of your materials.

Adding a filter to a layer results in a few noticeable changes. The layer will now be marked with a filter icon, and selecting the layer will reveal a column with all the filters that have been assigned.


<div class="image-box">
  <img src="/source/images/filters.png" alt="layer action image">
  <div class="text-box">
    Filters list
  </div>
</div>

## Applying Levels
![type:video](source/videos/levels.mp4)

## Applying Mask and Light filter
![type:video](source/videos/light.mp4)

## Filter

<div class="nice-text-box">
  <h3>Levels</h3>
  <p>
    This filter allows you to control the levels of an RGB image, with controls similar to those found in image editing software. It also has the option to display a histogram of the current image by updating the histogram.
  </p>
</div>
<div class="nice-text-box">
  <h3>Color Ramp</h3>
  <p>
    Helps adjust the image contrast or adds color to a black and white image. It is useful for creating artistic effects or emphasizing specific tones.
  </p>
</div>
<div class="nice-text-box">
  <h3>Curve</h3>
  <p>
    Allows control over the colors of an image using RGB curves. This is useful for fine-tuning the brightness, contrast, and color balance of the layer.
  </p>
</div>
<div class="nice-text-box">
  <h3>HSV</h3>
  <p>
    Uses a **Hue Saturation Value** node to adjust these properties of the image. This filter is useful for color manipulation, such as shifting hues or changing overall saturation.
  </p>
</div>
<div class="nice-text-box">
  <h3>Invert</h3>
  <p>
    Inverts the color values of the image, effectively creating a negative effect. This filter can add interesting visual effects or be used in masking techniques.
  </p>
</div>
<div class="nice-text-box">
  <h3>Gamma</h3>
  <p>
    Controls the gamma of the current layer. It allows you to adjust the midtones without affecting highlights and shadows too much.
  </p>
</div>
<div class="nice-text-box">
  <h3>Brightness Contrast</h3>
  <p>
    Adjusts the brightness and contrast of the current layer. It is simple but effective for balancing the look of your textures.
  </p>
</div>
<div class="nice-text-box">
  <h3>Paint Layer</h3>
  <p>
    This filter allows adding a simple paint layer to the existing layer.
  </p>
</div>
<div class="nice-text-box">
  <h3>Mask By Color</h3>
  <p>
    Selects specific colors in the image to mask. This is useful for isolating and editing areas based on their color properties.
  </p>
</div>
<div class="nice-text-box">
  <h3>Mask Generator</h3>
  <p>
    Generates a mask using grunge textures and realtime or baked maps such as Ambient Occlusion (AO), Curvature, or Position. 
  </p>
</div>
<div class="nice-text-box">
  <h3>Light</h3>
  <p>
    Fake light based on geometry or baked Object Normal Map
  </p>
</div>
<div class="nice-text-box">
  <h3>Blur</h3>
  <p>
    Takes a snapshot of the current layer and creates a blurred image.
  </p>
</div>
<div class="nice-text-box">
  <h3>Snapshot</h3>
  <p>
    Takes a snapshot of the current layer, allowing you to reuse it in other parts of your workflow. It essentially saves the layer state so you can apply it elsewhere.
  </p>
</div>
<div class="nice-text-box">
  <h3>Transform</h3>
  <p>
    Translates, scales, or rotates the current layer. This filter allows you to manipulate the positioning of your texture without manually adjusting UVs.
  </p>
</div>
<div class="nice-text-box">
  <h3>Custom Filter</h3>
  <p>
    Allows for the use of a custom node group, created by users. It should have at least one input and output. The add-on automatically displays all input sockets, enabling users to edit properties and change inputs as needed.
  </p>
</div>


<div class="image-box">
  <img src="/source/images/filterexample.png" alt="layer action image">
  <div class="text-box">
    Filters assigned to layer
  </div>
</div>


---
