# Efa Dark Theme for Zed

A dark theme for [Zed Editor](https://zed.dev) inspired by JetBrains IDEs, featuring carefully crafted colors for optimal readability and reduced eye strain during long coding sessions.

## Theme Preview

**Efa Dark** features:
- Deep dark background (#1E1F22) for comfortable viewing
- Syntax highlighting with vibrant but balanced colors
- Distinct colors for keywords, strings, functions, and types
- Support for italic styles on comments, booleans, and constants
- Terminal color scheme that matches the editor aesthetic

## Installation

### Method 1: Manual Installation (Recommended)

1. **Locate your Zed themes directory:**
   - **macOS/Linux**: `~/.config/zed/themes/`
   - **Windows**: `%APPDATA%\Zed\themes\`

2. **Create the themes directory if it doesn't exist:**
   ```bash
   mkdir -p ~/.config/zed/themes
   ```

3. **Copy the theme file:**

   Download or copy `efa-dark.json` to your themes directory:
   ```bash
   cp efa-dark.json ~/.config/zed/themes/
   ```

4. **Activate the theme in Zed:**
   - Open Zed Editor
   - Open the Command Palette (`Cmd+Shift+P` on macOS, `Ctrl+Shift+P` on Windows/Linux)
   - Type "theme selector: toggle" and press Enter
   - Search for "Efa Dark" and select it

### Method 2: Using Git Clone

Clone this repository directly into your Zed themes directory:

```bash
cd ~/.config/zed/themes/
git clone https://github.com/yourusername/zed-theme-efa-dark.git
```

Then copy the theme file:
```bash
cp zed-theme-efa-dark/efa-dark.json ./
```

### Method 3: Via Zed Settings

1. Open Zed's settings file (`Cmd+,` or via menu: Zed → Settings)
2. Manually add the theme JSON content to your themes configuration
3. Restart Zed and select "Efa Dark" from the theme selector

## Verifying Installation

After installation, verify the theme is available:

1. Open Command Palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)
2. Type "theme selector"
3. Look for "Efa Dark" in the list
4. Select it to apply

## Configuration

Once installed, you can set Efa Dark as your default theme in your Zed settings:

```json
{
  "theme": "Efa Dark"
}
```

Or configure it to automatically switch based on system appearance:

```json
{
  "theme": {
    "mode": "system",
    "light": "One Light",
    "dark": "Efa Dark"
  }
}
```

## Color Palette

Key colors used in this theme:

- **Background**: `#1E1F22`
- **Foreground**: `#BCBEC4`
- **Blue (Functions)**: `#56A8F5`
- **Orange (Keywords)**: `#CF8E6D`
- **Green (Strings)**: `#6AAB73`
- **Cyan (Numbers)**: `#2AACB8`
- **Magenta (Properties)**: `#C77DBB`
- **Teal (Types)**: `#16BAAC`

## Troubleshooting

### Theme not appearing in the list
- Ensure the `efa-dark.json` file is in the correct directory
- Restart Zed Editor
- Check that the JSON file is valid (no syntax errors)

### Colors look different than expected
- Make sure you're using the latest version of Zed Editor
- Check that no other extensions are overriding the theme colors
- Verify your monitor's color calibration settings

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Author

**Yefimov Valentyn**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Inspired by the JetBrains IDE color schemes, particularly IntelliJ IDEA's dark themes.
