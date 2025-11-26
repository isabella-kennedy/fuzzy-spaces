# Tools: xFigura, Rhino, and Workflows

## xFigura.ai
**Role:** The primary "synthesizer" and "remix" engine.

xFigura is a generative design tool that bridges the gap between 2D image inputs and 3D geometric outputs. It allows for:
*   **Image-to-Model:** Converting 2D sketches/collages into 3D depth maps and meshes.
*   **Text-Guided Manipulation:** Using natural language to alter specific features of the geometry.
*   **Hybrid Viewing:** Visualizing outputs in latent states between 2D and 3D.

### setup
Students will use the web-based platform. Project files are pre-configured for each assignment. See specific assignment READMEs for links.

## Rhino / Revit / Blender
**Role:** The "Mastering" suite.

While xFigura generates the raw "track," traditional CAD tools are used to "master" the output—refining geometry, setting precise scales, and producing final documentation.

### Workflow: xFigura to Rhino
1.  **Export:** From xFigura, export your result as `.OBJ` or `.GLB`.
2.  **Import:** Import into Rhino.
3.  **Scale:** The AI output is unit-less. You must scale it to a human reference (e.g., assume a door height or stair tread).
4.  **Refine:** Use the imported mesh as a template.
    *   *Method A (Drape):* Use `Drape` or `Patch` to create clean surfaces over the mesh.
    *   *Method B (Section):* Cut sections through the mesh to extract profile curves.

