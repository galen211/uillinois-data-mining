# Week 1:
**Kinds of visualizations:**
- Interactive Visualization
- Interactive Storytelling
- Presentation Visualization

**Vector Graphics vs. Raster Graphics**
+ Vector: uses primitives to create shapes with strokes and areas to fill (requires coordinate system)
+ Raster: array of pixels (can cause aliasing)

**Hierarchical coordinate systems:**
- Multiple layers to accommodate different shapes in an entire vizualization.
- Canvas-to-screen transformation at display time (canvases within canvases)
- Rasterization allows for rescaling of vector graphics.

Sequence of rendering SVG:
Vertex processing -> raterization -> pixel processing

**Photorealism:**
+ Occlusion is the strongest depth cue
+ Shadowing is the occlusion of a light source
+ Illumination revelas surface orientation
+ Perspective can reveal different scales of visualization in addition to aiding depth perception
+ Stereo is useful when other cues are unavailable.

**Non-Photorealistic rendering:**
+ Photorealistic rendering is based on the physics of light whereas non-photorealistic (artistic) rendering is based on psychology of perception
+ Non-photorealistic rendering is based on contours instead of surfaces
+ Non-photorealistic shading makes it easier to communicate shape without complex lighting

**Memory**:
+ Sensory memory decays very quickly
+ Working memory decays quickly, but supports cognitive processing
+ Long term memories persist indefinitely, but the challenge is getting information stored
+ We can learn and remember better if we vary learning styles

Deductive reasoning: elimination of possibilities
Inductive reasoning: if true for x, then also true for x+1
Abductive reasoning: entertaining simultaneous contradictory opinions

# Week 2:
**Summary**: focusing on attributes of data and how to incorporate into a visual display

Stages in data pipeline:
+ Data Layer: locate and obtain data
+ Mapping Layer: associate appropriate geometry with corresponding data channels
+ Graphics Layer: convert geometry into displayable image with decorations

Data Types:
+ Discrete vs Continuous
+ Ordered vs Unordered

Mapping Data:
+ Quantiative: position, length, angle/slope, area, volume, density, color, saturation (intensity of color), hue
+ Ordinal: position, density, saturation, hue are most common ways
+ Nominal: position, hue, texture

Glyphs:
+ Can vary shapes of items in chart to encode additional measures on a map (error bars on bar charts are an example)
+ Heatmap can add additional visual information when overlaid on a table

Parallel coordinates:
Plot higher dimensional shapes
\image