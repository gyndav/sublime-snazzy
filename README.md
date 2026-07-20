# Snazzy Sublime Text Theme

> Elegant Sublime Text color scheme with bright colors, based on Sindre Sorhus' iTerm2 Snazzy theme

![Snazzy Preview](https://raw.githubusercontent.com/sindresorhus/iterm2-snazzy/master/screenshot.png)
*Preview image from the original iTerm2 Snazzy theme*

## Description

Snazzy is a vibrant and elegant color scheme that brings the popular iTerm2 Snazzy theme to Sublime Text. It features a dark background with bright, colorful syntax highlighting that's easy on the eyes while providing excellent contrast and readability.

This port faithfully reproduces the iTerm2 Snazzy color palette in Sublime Text's `.sublime-color-scheme` format, ensuring a consistent visual experience across your development tools.

## Installation

### Using Package Control (Recommended)

1. Open Sublime Text
2. Press `Cmd+Shift+P` (macOS) or `Ctrl+Shift+P` (Windows/Linux)
3. Type `Package Control: Install Package` and press Enter
4. Search for `Snazzy` and install it
5. Go to Preferences > Color Scheme > Snazzy

### Manual Installation

1. Download both `Snazzy.sublime-color-scheme` and `Snazzy.sublime-theme` files from this repository
2. Open Sublime Text
3. Go to Preferences > Browse Packages...
4. Navigate to the `User` directory
5. Place both files in the `User` directory
6. Go to Preferences > Color Scheme > User > Snazzy
7. Go to Preferences > Theme > User > Snazzy

**Note**: For the best experience, use both the color scheme and theme together. The color scheme handles syntax highlighting, while the theme handles the UI (sidebar, tabs, status bar, etc.).

## Color Palette

### Base Colors

| Element | Hex | RGB |
|---------|-----|-----|
| Background | `#282a36` | 40, 42, 54 |
| Foreground | `#eff0eb` | 239, 240, 235 |
| Cursor | `#e9e9e9` | 233, 233, 233 |
| Selection | `#9370db` | 147, 112, 219 |
| Line Highlight | `#44475a` | 68, 71, 90 |

### ANSI Terminal Colors

| Index | Color | Hex | Usage |
|-------|-------|-----|-------|
| 0 | Black | `#000000` | ANSI Black |
| 1 | Red | `#ff5c57` | ANSI Red |
| 2 | Green | `#5af78e` | ANSI Green |
| 3 | Yellow | `#f3f99d` | ANSI Yellow |
| 4 | Blue | `#57c7ff` | ANSI Blue |
| 5 | Magenta | `#ff6ac1` | ANSI Magenta |
| 6 | Cyan | `#9aedfe` | ANSI Cyan |
| 7 | White | `#f1f1f0` | ANSI White |
| 8 | Bright Black | `#686868` | Bright Black |
| 9 | Bright Red | `#ff5c57` | Bright Red |
| 10 | Bright Green | `#5af78e` | Bright Green |
| 11 | Bright Yellow | `#f3f99d` | Bright Yellow |
| 12 | Bright Blue | `#57c7ff` | Bright Blue |
| 13 | Bright Magenta | `#ff6ac1` | Bright Magenta |
| 14 | Bright Cyan | `#9aedfe` | Bright Cyan |
| 15 | Bright White | `#f4f4f4` | Bright White |

### Syntax Highlighting Colors

| Element | Scope | Color | Hex |
|---------|-------|-------|-----|
| Comments | `comment` | Gray | `#6272a4` |
| Strings | `string` | Bright Yellow | `#f3f99d` |
| Numbers | `constant.numeric` | Magenta | `#ff6ac1` |
| Keywords | `keyword` | Magenta | `#ff6ac1` |
| Functions | `entity.name.function` | Cyan | `#9aedfe` |
| Classes/Types | `entity.name.class`, `support.type` | Blue | `#57c7ff` |
| Variables | `variable` | Foreground | `#eff0eb` |
| Constants | `constant` | Yellow | `#f1fa8c` |
| Invalid | `invalid` | Red | `#ff5c57` |

## Features

- **Vibrant colors**: Bright syntax highlighting that's easy to read
- **Consistent palette**: Uses the exact colors from the original iTerm2 Snazzy theme
- **Comprehensive coverage**: Syntax rules for all major programming languages
- **Complete UI theming**: Includes both color scheme (syntax) and theme (UI) files
- **Modern format**: Uses Sublime Text 4's `.sublime-color-scheme` and `.sublime-theme` JSON format
- **Variables**: Color variables for easy customization
- **Git integration**: Special colors for git diff markers
- **Markdown support**: Styled markdown headings, links, and code blocks
- **HTML/CSS support**: Proper styling for web development
- **Themed UI elements**: Sidebar, tabs, status bar, buttons, panels, and more

## Customization

The color scheme uses CSS-like variables for consistency. You can override any color by:

1. Open Sublime Text preferences
2. Add or modify the `color_scheme` settings
3. Override specific colors using the variable names

For example, to change the background color:

```json
{
  "color_scheme": "Snazzy.sublime-color-scheme",
  "theme": "YourTheme.sublime-theme",
  "color_scheme_vars": {
    "background": "#1e1e1e"
  }
}
```

## Compatibility

- **Sublime Text 4**: Full support
- **Sublime Text 3**: Full support
- **Windows/macOS/Linux**: All platforms supported

## Included Files

| File | Description |
|------|-------------|
| `Snazzy.sublime-color-scheme` | Main color scheme for syntax highlighting |
| `Snazzy.sublime-theme` | UI theme for sidebar, tabs, status bar, etc. |
| `Snazzy.tmTheme` | Legacy XML format for older Sublime Text versions |
| `README.md` | Documentation and usage instructions |
| `LICENSE` | MIT License |
| `.github/workflows/test-color-scheme.yml` | CI workflow for validation |
| `.editorconfig` | Editor configuration |
| `.gitignore` | Git ignore patterns |

## Credits

- **Original Design**: Sindre Sorhus ([@sindresorhus](https://github.com/sindresorhus))
- **iTerm2 Theme**: [sindresorhus/iterm2-snazzy](https://github.com/sindresorhus/iterm2-snazzy)
- **Sublime Text Port**: David Guyon ([@gyndav](https://github.com/gyndav))

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.

## Screenshots

![JavaScript Example](screenshots/javascript.png)
![Python Example](screenshots/python.png)
![HTML/CSS Example](screenshots/html.png)

*Note: Screenshots coming soon - feel free to contribute your own!*

## Related Projects

- [iTerm2 Snazzy Theme](https://github.com/sindresorhus/iterm2-snazzy) - Original theme
- [Snazzy for VS Code](https://github.com/TimUntverfehrt/vscode-snazzy) - VS Code port
- [Snazzy for Terminal](https://github.com/sindresorhus/hyper-snazzy) - Hyper terminal theme