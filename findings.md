# Findings: Color Analysis

## Palette Colors (from pallete.lua)
- bg: "#101010"
- fg: "#b0b0b0"
- dim: "#181818"
- line: "#272727"
- keyword: "#777777"
- comment: "#50585d"
- border: "#ffffff"
- emphasis: "#ffffff"
- func: "#ffffff"
- string: "#ffffff"
- const: "#d9ba73"
- highlight: "#0058d0"
- info: "#8ebeec"
- success: "#86cd82"
- warning: "#d9ba73"
- danger: "#ff7676"

## Color Mappings Used
- Background: bg "#101010"
- Foreground: fg "#b0b0b0"
- Dim/selection: dim "#181818"
- Border: border "#ffffff"
- Highlight/cursor: highlight "#0058d0"
- Accent/info: info "#8ebeec"
- Success/green: success "#86cd82"
- Warning/yellow: warning "#d9ba73"
- Danger/red: danger "#ff7676"
- Line/box: line "#272727"
- Keyword: keyword "#777777"

## Files Updated
- walker.css: Updated @define-color to palette colors
- waybar.css: Updated foreground and background
- swayosd.css: Updated colors
- hyprland.conf: Updated border colors to rgb
- hyprlock.conf: Updated rgba colors
- mako.ini: Updated text, border, background
- chromium.theme: Updated rgb to bg
- btop.theme: Updated all colors and gradients
- kitty.conf: Updated foreground, background, cursor, tabs, palette
- alacritty.toml: Updated primary, cursor, search, hints, selection, palette
- ghostty.conf: Updated palette, background, foreground, cursor, selection
- obsidian.css: Updated all CSS variables and hardcoded colors to palette

## Files Not Updated
- neovim.lua: Uses evergarden theme, not directly configurable with palette
- vscode.json: Just extension name
- icons.theme: Just theme name
