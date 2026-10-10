# Warehouse Layout Studio

A dependency-free, English-language warehouse floor-plan editor. Open `dist/index.html` in a modern browser, or serve the `dist` folder with a static web server.

## Features

- Drag, resize, duplicate, and rotate racks and other objects.
- Add packing tables, receiving/shipping areas, aisles, walls, offices, columns, and doors/docks.
- Load a B21 photo-based layout or start from a blank canvas.
- Undo/redo and browser-local autosave.
- Export JPG, PNG, SVG, PDF, flattened PSD, and editable JSON backups.
- Import JSON to move a layout between devices.

B21 uses drawing coordinates, not measured dimensions. Labels marked “verify” need on-site confirmation. The reference photo is included in `dist/reference.jpg`.

PDF exports contain a high-resolution raster image on an A4 page. PSD exports contain a flattened RGB composite, not independently editable rack layers. JSON preserves editable objects.

No installation or build is required. For local HTTP serving: `python3 -m http.server 8000 --directory dist`.

Layouts are stored only in the current browser. Back them up before clearing browser storage.
