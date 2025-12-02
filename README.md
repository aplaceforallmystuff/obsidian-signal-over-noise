# Signal Over Noise - Obsidian Theme

A mid-century modern, retro-futuristic color scheme for [Obsidian](https://obsidian.md).

![Dark Theme](screenshots/dark.png)
![Light Theme](screenshots/light.png)

## Features

- Full light and dark mode support
- Automatic switching with system appearance
- Custom callout styling (tip, warning, danger, success, info)
- Enhanced typography for headings
- Styled tables with alternating rows
- Custom graph view colors
- Mobile-optimized

## Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Teal | `#1B9AAA` | Primary accent, links, interactive elements |
| Burnt Orange | `#EF6351` | Bold text, cursors, errors |
| Cream | `#F7F4EA` | Light mode background |
| Black | `#1A1A1A` | Dark mode background |
| Sage Green | `#88AB8E` | Italic text, success states |
| Mustard Yellow | `#E5B945` | Highlights, warnings |
| Navy Blue | `#2C3E50` | Secondary headings, external links |

## Installation

### From Obsidian Community Themes

1. Open Obsidian Settings
2. Go to Appearance → Themes
3. Click "Manage" and search for "Signal Over Noise"
4. Click Install, then Use

### Manual Installation

1. Download `theme.css` and `manifest.json`
2. Create folder: `YOUR_VAULT/.obsidian/themes/Signal Over Noise/`
3. Copy both files into the folder
4. In Obsidian: Settings → Appearance → Themes → Signal Over Noise

## Customization

The theme uses CSS variables for easy customization. Add to your `snippets` folder:

```css
/* Example: Change accent to a different teal */
:root {
  --son-teal: #17a2b8;
}
```

## Typography

The theme uses system fonts for optimal performance:

- **Text**: System UI (San Francisco on macOS)
- **Code**: SF Mono, Fira Code, JetBrains Mono

## About Signal Over Noise

[Signal Over Noise](https://signalovernoise.email) is a weekly AI newsletter by Jim Christian, focused on practical AI implementation over hype.

The theme reflects the brand's mid-century modern, retro-futuristic aesthetic.

## License

MIT License - see [LICENSE](LICENSE)

## Author

Jim Christian ([@jimchristian](https://github.com/aplaceforallmystuff))
