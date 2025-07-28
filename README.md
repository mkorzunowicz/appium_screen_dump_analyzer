# Appium Screen Dump Analyzer

This repository contains a single page HTML application for visualizing Appium screen dumps.

The viewer overlays bounding boxes defined in an XML hierarchy onto a corresponding screenshot. It is useful for inspecting UI elements and copying unique XPaths.

## Features

- Load a screenshot (JPG/PNG) and its matching XML dump.
- Display element hierarchy in a sidebar.
- Highlight elements by clicking in the tree or on the overlay.
- Copy full or shortest unique XPath for any element.
- Search for nodes by attribute or XPath.
- Drag-and-drop files or use the file selection buttons.

## Usage

1. Open `appium-viewer.html` in your web browser. No server is required—open the file directly.
2. Click **Select Screenshot** and choose an image of the screen.
3. Click **Select UI XML** and choose the XML dump exported from Appium or another tool.
4. The screenshot will appear with green overlay boxes for each element. Select an element in the sidebar tree or click a box on the image to view its properties and copy XPaths.

You can also drag and drop the screenshot and XML files anywhere on the page.
