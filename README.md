#  g2f

A Python GUI tool that slices a **square GIF** into a 3x3 grid per frame, exports each tile as individual PNG images, and bundles everything into a ZIP file. Ideal for pixel-art animation, game development, or creative experiments!

![SHOWCASE](https://github.com/gaxolotl/g2f/blob/main/Screen%20Recording%202025-06-15%20230647.gif?raw=true)

---

##  Features

-  Splits square GIFs into 3x3 tiles per frame.
-  Optional filters: `None`, `Grayscale`, `Tint`.
-  Automatically clears output folders before export.
-  Organizes output by tile (e.g. `tile-0-0`, `tile-1-2`, etc.)
-  Zips the result into `gif_tiles_export.zip`.
-  GIF preview and progress bar included.
-  Runs processing in a separate thread (non-blocking GUI).
