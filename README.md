rGuiIcons
A simple and easy-to-use raygui icons editor.

Useful for tools icons customization. The best tool companion for rGuiLayout and rGuiStyler.

rGuiIcons can be used for free as a WebAssembly online tool and it can also be downloaded as a standalone tool for Windows and Linux with some extra features.

NOTE: Latest rGuiIcons 3.0 release is intended to be used with raygui 4.0 release.

Features
Icon editing and preview at multiple sizes
Cut, copy, paste icons for easy editing
Undo/Redo system for icon changes
Save and load as binary iconset file .rgi
Export iconset as an embeddable code file (.h)
Export iconset as a .png black&white image
Icon name ids exported as standard PNG chunk (zTXt)
Multiple UI styles for tools reference
+200 custom icons for reference and basic edition
Command-line support for .rgi/.h/.png batch conversion
Completely portable (single-file, no-dependencies)
Free and open source
Screenshot
rGuiIcons

Usage
The tool is quite intuitive, the expected steps to follow are:

Choose the icon to edit from icons panel
Edit the icon pixels in the right panel
Select next icon for edit or export set/individual icon
NOTE: Icon changes are previewed in real time in the same tool!

Once icons have been created/edited, they can be saved as a raygui-ready icon set (.rgi), exported as an embeddable .h code file or exported as a .png image. Note that the .png contains the icons ids information in a standard chunk (tEXt/zTXt).

raygui icon set file (.rgi) can be loaded by raygui using the function GuiLoadIcons().

raygui icon set code file (.h) can be embedded into a raygui-based application just defining:

#define RAYGUI_IMPLEMENTATION
#define RAYGUI_CUSTOM_ICONS     // Custom icons set required 
#include "gui_iconset.h"        // Custom icons set provided, generated with rGuiIcons tool
#include "raygui.h"
rGuiIcons Standalone comes with command-line support for batch conversion. For usage help:

rguiicons.exe --help

License
rGuiIcons source code is distributed as open source, licensed under an unmodified zlib/libpng license.

rGuiIcons binaries are completely free for anyone willing to compile it directly from source.

rGuiIcons Standalone desktop tool is distributed as freeware.

In any case, consider some donation to help the author keep working on software for games development.

Copyright (c) 2019-2025 raylib technologies (@raylibtech) / Ramon Santamaria (@raysan5)
