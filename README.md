# Div Focus - Chrome Extension

A Chrome extension that automatically focuses on the div with id "mainContent" by darkening the rest of the page.

## Features

- Automatically finds and focuses on the div with id "mainContent"
- Darkens the rest of the page to highlight the focused div
- Shows the div name (id) in a label above the div
- Click "Clear Selection" to remove the focus effect

## Installation

1. Open Chrome and navigate to `chrome://extensions/`
2. Enable "Developer mode" (toggle in the top right)
3. Click "Load unpacked"
4. Select the folder containing this extension
5. The extension icon should appear in your toolbar

## Usage

1. Navigate to a webpage that contains a div with id "mainContent"
2. Click the extension icon in your toolbar
3. Click "Focus on mainContent" button
4. The div with id "mainContent" will be highlighted with a green outline
5. The rest of the page will be darkened, creating a spotlight effect
6. The div name "#mainContent" will be displayed above the div
7. Click "Clear Selection" to remove the effect

## Files

- `manifest.json` - Extension configuration
- `content.js` - Main logic for div selection and dark overlay
- `content.css` - Styles for the overlay
- `popup.html` - Extension popup interface
- `popup.js` - Popup button handlers

## Note on Icons

The manifest references icon files (icon16.png, icon48.png, icon128.png). You can:
- Create your own icons (16x16, 48x48, 128x128 pixels)
- Or remove the icon references from manifest.json if you don't need them

# readlang-dark
