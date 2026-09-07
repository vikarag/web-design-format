# Minimal Design Format

## Fonts
- Arial (primary)
- Vazirmatn (Persian/Arabic)
- Noto Sans KR (Korean)
- Noto Sans SC (Chinese)
- Noto Sans Tamil (Tamil)
- Noto Sans Sinhala (Sinhala)

## Colors
- White: #ffffff (background)
- Black: #000000 (text, borders)
- #e9e9e9 (buttons, boxes, table headers/borders, code background)
- #555 (links default)
- #777 (links hover)
- #eee (button hover)

## Design Rules
- 0.5rem rounded corners on divs
- Minimal CSS
- Sharp edges on all elements except divs
- Monospace font for code blocks

## Files
- style.css - Base styles
- sample.html - Sample page with all components
- themes/minimal.css - MicroLighter minimal theme

## Dependencies
- [MicroLighter](https://github.com/davatron5000/microlighter) - Syntax highlighting (~2KB)

## Components
- .btn - Button with #e9e9e9 background, #eee on hover
- .box - Box with #e9e9e9 background
- .grid - Responsive grid layout
- .rtl - Right-to-left text direction
- table - Basic table with #e9e9e9 borders and headers
- a - Links with #555 default, #777 on hover, no underlines
- pre/code - Code blocks with #e9e9e9 background, black text
