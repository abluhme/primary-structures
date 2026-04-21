# Primary Structures — Testing Table Tool

A browser-based tool for designing geometric kidney-like forms, built from overlapping circles connected by tangent-smooth Bézier curves.

**[Open the tool →](https://abluhme.github.io/primary-structures/)**

---

### How it works

Shapes are constructed from three or more circles. Each pair of adjacent circles is bridged by a cubic Bézier curve whose endpoints are tangent to the respective circles, producing a smooth, flowing outer contour.

- Drag circle centers to reposition
- Drag the edge handle to resize
- Use the **Flow** slider to tune how much the connectors curve
- Export as a clean SVG stroke — ready for Illustrator or a pen plotter

### Local use

No build step. Open `index.html` in any modern browser.
