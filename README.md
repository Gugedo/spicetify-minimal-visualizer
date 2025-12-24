# Spicetify minimal Visualizer

A lightweight, CSS-only 4-bar visualizer that sits in the extra controls area of the playback bar.

## 📸 Preview

<p align="center">
  <img src="preview.gif" alt="Minimal 4-Bar Visualizer Preview">
  <br>
  <b>Theme:</b> text by darkthemer | <b>Color Scheme:</b> RosePine
</p>

## ✨ Features
- **Independent Motion:** Each bar moves at its own rhythm for a more realistic feel.
- **Universal Compatibility:** Language-independent logic (works in English, Italian, Spanish, etc.) by targeting SVG paths.
- **Performance Friendly:** 100% CSS, no JavaScript, zero CPU impact.

## 🛠 Installation

### Method 1: Marketplace (using +Add CSS)
If you have the Marketplace installed, go to `Marketplace > Snippets > + Add CSS` and then paste the content found in `visualizer.css`.

### Method 2: Manual (Recommended)
1. Open your Spicetify `user.css` file.
2. Paste the content of `visualizer.css` at the end of the file.
3. Run `spicetify apply` in your terminal.

## 🎨 Customization
You can tweak the visualizer by editing the variables at the top of the CSS file:
- `--viz-color`: Change the color of the bars.
- `--viz-speed`: Adjust the animation speed.
- `--viz-width`: Change the total width.
- `--viz-height`: Change the total height.
- `--viz-bar-w`: Change width of each bar.
- `--viz-off-y`: Adjust vertical alignment.

## 📜 License
MIT
