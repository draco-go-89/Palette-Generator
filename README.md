# Palette Generator

[![Palette Generator Preview](https://via.placeholder.com/800x400/4F46E5/FFFFFF?text=Palette+Generator+Preview)](https://via.placeholder.com/)

## 🎨 Overview

A beautiful, fully-responsive **Random Color Palette Generator** built with pure HTML, Tailwind CSS (CDN), and vanilla JavaScript. Generate stunning 5-color palettes with one click and instantly copy any color's hex code by clicking on it!

Perfect for designers, developers, and anyone needing quick color inspiration.

## ✨ Features

- 🎲 **Random Palette Generation**: Click 'Generate New Palette' to get 5 beautiful, random hex colors
- 📋 **One-Click Copy**: Click any color block to copy its hex code to clipboard
- 👁️ **Smart Contrast**: Automatic black/white text based on color luminance for perfect readability
- 📱 **Fully Responsive**: Works perfectly on desktop, tablet, and mobile
- ⚡ **No Dependencies**: Self-contained single HTML file - no build tools needed
- 🎨 **Smooth Animations**: Hover effects, transitions, and micro-interactions
- 🚀 **Instant Loading**: Uses Tailwind CSS via CDN for zero setup

## 🚀 Quick Start

1. **Open** `main.html` in any modern web browser
2. **Click** "Generate New Palette" to create your first palette
3. **Click** any color to copy its hex code
4. **Done!** Use the colors in your projects

```bash
# Just double-click main.html or drag to browser
open main.html  # macOS
start main.html  # Windows
```

## 📱 Demo

Live demo available by simply opening `main.html`!

## 🛠️ Tech Stack

- **HTML5** - Semantic structure
- **Tailwind CSS** (CDN) - Utility-first styling
- **Vanilla JavaScript** - No frameworks, pure DOM manipulation
- **Modern CSS** - Custom properties, transforms, backdrop filters

## 🎯 How It Works

1. **Color Generation**: `Math.random()` creates random 24-bit hex colors
2. **Contrast Detection**: W3C luminance formula determines optimal text color
3. **Clipboard API**: `document.execCommand('copy')` for reliable copying
4. **Event-Driven**: Pure event listeners for all interactions

## 🔮 Future Enhancements

- [ ] Save/load palettes
- [ ] Export to CSS/SCSS/JSON
- [ ] Color harmony algorithms (complementary, analogous)
- [ ] Gradient generation
- [ ] Share palettes via URL

## 🤝 Contributing

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

⭐ **Made with ❤️ using vanilla web technologies**

