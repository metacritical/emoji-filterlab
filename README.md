# Emoji Filter Lab

A CSS filter playground to tint and customize emojis in real-time.

## Features

- 🎨 **Real-time CSS Filters**: Adjust hue, saturation, brightness, contrast, sepia, invert, grayscale, and opacity
- 💎 **Large Preview**: 112px emoji preview with adjustable size (12-256px)
- ✨ **Selection-Based**: Select any emoji in the live editor to preview it automatically
- 📋 **Copy-Ready**: Generate and copy CSS filter code and HTML snippets
- 🎯 **Live Editor**: Type and edit text with emojis, all applying filters in real-time
- 🌈 **Customizable**: Adjust text color, background, and font size
- 📱 **Responsive**: Works on desktop, tablet, and mobile devices

## Usage

Simply open `index.html` in a web browser. No build process or dependencies required!

### Quick Start

```bash
# Navigate to the directory
cd ~/Development/emoji-filterlab

# Open in browser (macOS)
open index.html

# Or use a simple HTTP server
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## How It Works

1. **Select an emoji** in the live editor or type one in the emoji input field
2. **Adjust the filter sliders** to customize the appearance
3. **Copy the CSS** or HTML snippet to use in your projects

## Technologies

- Pure HTML, CSS, and JavaScript
- No frameworks or dependencies
- Uses modern browser APIs:
  - `Intl.Segmenter` for proper emoji grapheme cluster extraction
  - CSS filters for real-time effects
  - Clipboard API for easy copying

## Browser Support

Works in all modern browsers that support:
- CSS Filters
- Unicode emoji
- ES6 JavaScript

## License

Free to use for any purpose.
