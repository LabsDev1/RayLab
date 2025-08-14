# RayLab

RayLab is a browser-based 3D ray tracer for creating and rendering simple 3D scenes. Built with HTML, CSS (Tailwind CSS), and JavaScript, it allows you to interactively build scenes with basic geometric shapes and custom meshes, all rendered in real time.

---

### Features

* Interactive 3D Viewport: Create and manipulate 3D scenes directly in your browser.
* Built-in Primitives: Easily add and configure spheres, cubes, cones, and pyramids.
* Object Properties: Adjust an object's position, size, and shading properties (color, roughness, reflectivity, glass).
* Advanced Rendering: Supports soft shadows, depth of field, and reflections for more realistic output.
* OBJ File Support: Load custom 3D models from .obj files for more complex geometry.
* Export Options: Render and save high-resolution images as a PNG file.

---

### How to Use

1. Open the Application: Open the RayLabs.html file in any modern web browser. No installation is required.
2. Add Objects: Use the toolbar to select a shape and click the add button to place it in the scene.
3. Select and Inspect: Click on an object in the viewport. The right-hand panel, or inspector, will let you edit its properties.
4. Edit Properties: Use the tabs to adjust the object's position and size (properties), its appearance (shading), or fine-tune camera, lighting, and rendering settings.
5. Render and Export: Click render for a high-quality image, then use the save button to export it as a PNG.

---

### Tips for Experimenting

* Experiment with Shading: Set an object's glass value to 1 and its ior to 1.5 for a clear glass effect.
* Create Complex Meshes: Use the load OBJ button to import 3D models and change their material properties.
* Adjust Lighting: Change the light's position and intensity, or use objects with emissive values to create light sources.

---

### Technical Details

The project uses a custom JavaScript ray tracing engine. It performs all rendering calculations on a single CPU core, without relying on WebGL or other graphics APIs. The UI is styled with Tailwind CSS.

* HTML: Provides the user interface structure.
* Tailwind CSS: Styles all UI components.
* JavaScript: The core of the project, including the 3D math library, ray tracing engine, and UI logic.
