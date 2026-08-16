# kicad-esc-board
PCB for mounting and cooling ESCs in a small footprint.

# Use
1. Open the `.kicad_pro` file in KiCAD 10.0 or later.
2. Add the custom symbols library in `Preferences` -> `Manage Symbol Libraries` -> `Project Specific Libraries` -> Folder Icon Dropdown -> `KiCAD (.kicad_sym)`. When the folder dialog opens, navigate to `.../kicad-esc-board/Resources` and select `esc_board_custom_symbols.kicad_sym`. Click `OK` to save and exit.
3. Add the footprint libraries in `Footprint Editor` -> `Preferences` -> `Manage Footprint Libraries` -> `Project Specifc Libraries` -> Folder Icon Dropdown -> 'KiCAD (folder with .kicad_mod files)`. When the folder dialog opens, navigate to `.../kicad-esc-board/Resources` and select the `esc_board_custom_footprints.pretty' folder. Click `OK` to save and exit.