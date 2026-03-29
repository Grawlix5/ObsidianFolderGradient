
**WARNING** MADE WITH A **LOT** OF VIBE-CODED SLOP!!!!!!!!!

![Obsidian_n4WsSf4oPR](https://github.com/user-attachments/assets/06c34d58-1343-4921-9a51-81357d955e4a)


# Folder Gradient
 
An Obsidian plugin that colors your sidebar folders by interpolating their positions across a fully customizable gradient. Instead of manually assigning colors to each folder, the plugin automatically distributes colors based on where each folder sits alphabetically — just pick your gradient and let it do the rest.
 

---
 
## Features
 
**Gradient editor**
- Define a gradient with any number of color stops
- Click any color swatch to open a color picker
- Drag position sliders to control where each stop sits on the gradient
- Live preview bar updates as you edit
 
**Presets**
- Ships with 8 built-in gradients: CyanVoxel, Sunset, Ocean, Forest, Candy, Midnight, Autumn, and Neon
- Save your own gradients as named custom presets
- Load and delete custom presets from a single dropdown
 
**Auto-spacing**
- One click redistributes all color stops evenly across the gradient, preserving their color order
 
**Subfolder support**
- Optionally color nested folders too
- Choose between two modes: subfolders spread across the full gradient individually, or subfolders inherit their top-level parent's exact color
 
**File name tinting**
- Optionally tint file names inside each colored folder
- Saturation slider controls how strongly the folder color bleeds into the file names (0% = default text color, 100% = full folder color)
 
**Dynamic accent color**
- When enabled, Obsidian's global accent color (buttons, links, checkboxes, sliders, active states) dynamically shifts to match the gradient color of whichever folder the currently open file lives in
- Switch between files in different folders to see the entire UI recolor in real time
 
---
 
## Installation
 
### From the Community Plugins browser
1. Open Obsidian Settings → Community Plugins
2. Click **Browse** and search for **Folder Gradient**
3. Click **Install**, then **Enable**
 
### Manual installation
1. Download `main.js`, `manifest.json`, and `styles.css` from the [latest release](https://github.com/yourusername/obsidian-folder-gradient/releases/latest)
2. Create a folder at `<your vault>/.obsidian/plugins/folder-gradient/`
3. Copy the three files into that folder
4. Reload Obsidian and enable the plugin under Settings → Community Plugins
 
---
 
## Usage
 
1. Enable the plugin
2. Open **Settings → Folder Gradient**
3. Pick a preset from the dropdown or build your own gradient using the color stops editor
4. Your sidebar folders will update immediately
 
All settings apply live — no need to restart or reload.
 
---
 
## Settings reference
 
| Setting | Description |
|---|---|
| Presets | Load a built-in or saved gradient, or save the current one as a new preset |
| Color Stops | Add, reposition, recolor, or remove individual stops on the gradient |
| Auto-space Evenly | Redistribute all stops to perfectly even positions in one click |
| Color subfolders | Extend the gradient coloring to nested folders |
| Subfolders inherit parent color | Nested folders share their top-level parent's color instead of getting their own gradient position |
| Color file names | Tint file names inside each folder with the folder's gradient color |
| File name saturation | Controls how strongly the tint is applied to file names |
| Highlight opacity | Controls the strength of the colored background on active and hovered items |
| Override accent color from active file | Dynamically shifts Obsidian's global accent color based on the active file's folder |
 
---
 
## Credits
 
The CyanVoxel preset is based on the [Colored Sidebar Items](https://github.com/CyanVoxel/Obsidian-Colored-Sidebar) CSS snippet by CyanVoxel.
 
---
 
## License
 
Copyright (c) 2026 Grawlix

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
