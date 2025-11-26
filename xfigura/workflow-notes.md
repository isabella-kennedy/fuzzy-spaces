# Workflow Notes & Troubleshooting

## Common Issues

### "My output looks too chaotic / messy."
*   **Diagnosis:** Your "High-Pass Filter" (text prompt detail) is overpowering your "Bassline" (image input).
*   **Fix:** Increase the **Image Strength** slider. This forces the AI to adhere more strictly to your original collage's structure. Simplify your text prompt to 2-3 key adjectives.

### "The model isn't understanding my 3D view."
*   **Diagnosis:** The AI is interpreting your collage as a flat texture rather than spatial depth.
*   **Fix:** Use terms like "Isometric," "Axonometric," "Depth map," or "Z-depth" in your negative prompt to remove flat interpretations. Ensure your input collage has clear tonal contrast (lighter = closer, darker = further) if possible.

### "I lost my previous iteration."
*   **Note:** xFigura is iterative. Always save/export promising results immediately.
*   **Tip:** Keep a "Logbook" of your prompts. Copy-paste successful text prompts into a local text file.

## Advanced Techniques

### The "Feedback Loop"
1.  Generate an output in xFigura.
2.  Take a screenshot of that output.
3.  Re-import that screenshot as a NEW input image.
4.  Remix it again.
*   *Effect:* This solidifies the geometry and removes artifacts, making the "fuzzy" space more concrete.

### The "Masking" Technique (In Photoshop)
Before uploading to xFigura:
1.  Create your collage.
2.  Paint pure black (`#000000`) over areas you want to be "void" or "background."
3.  xFigura often interprets black as infinite depth or empty space.

