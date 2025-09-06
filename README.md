# Interactive Mathematical Visualizations

Welcome to a collection of interactive, mind-bending mathematical and geometric visualizations. Each demo is a self-contained HTML file, crafted with vanilla JavaScript and the HTML5 Canvas API to bring complex abstract structures to life on your screen.

## Demos

This repository currently contains the following visualizations:

1.  [E8 Lie Group](#-e8-lie-group-e8html)
2.  [Tesseract (4D Hypercube)](#-tesseract-4d-hypercube-tesseracthtml)

---

### 🌌 E8 Lie Group (`e8.html`)

This demo presents a 3D projection of the E8 root system, one of the most exceptional and complex structures in mathematics. You are viewing a projection of 240 root vectors from their native 8-dimensional space.

#### Features

- **8-Dimensional Rotation**: The structure rotates simultaneously across multiple 8D planes.
- **240 Root Vectors**: All 240 root vectors of the E8 lattice are generated and displayed.
- **Interactive Controls**: Manipulate the 3D perspective, zoom, and visualization style in real-time.
- **Multiple Visual & Color Modes**: Explore the structure with different visual styles, including modes that color points based on their mathematical properties or on-screen velocity.

#### Controls

| Key      | Action                                                              |
| :------- | :------------------------------------------------------------------ |
| `Mouse`  | Control the 3D perspective of the projection.                       |
| `Scroll` | Zoom in and out.                                                    |
| `Space`  | Pause or resume the animation.                                      |
| `R`      | Reset all rotations and zoom to the default state.                  |
| `C`      | Toggle **Chaos Mode** for variable rotation speed.                  |
| `V`      | Cycle through **Visual Modes** (Standard, Lines, Minimal).          |
| `G`      | Cycle through **Color Modes** (Categorical, Dimensional, Velocity). |
| `E`      | Toggle **Root Emphasis** to make points larger.                     |
| `H`      | Hide or show the UI overlays.                                       |

---

### 🎮 Tesseract (4D Hypercube) (`tesseract.html`)

This demo showcases an interactive projection of a 4-dimensional hypercube (a tesseract). Watch as a single 4D object rotates through its dimensional planes, casting a 3D shadow that is then rendered on your 2D screen.

#### Features

- **True 4D Rotation**: The tesseract rotates across all 6 of its 4D rotational planes (`xw`, `yw`, `zw`, `xy`, `xz`, `yz`).
- **Cell Visualization**: The 8 cubic "cells" that form the tesseract are rendered with transparency and depth-sorting.
- **Interactive 3D View**: Use the mouse to control the final 3D projection's camera angle.
- **Visual Styles**: Switch between a standard view, a glowing neon aesthetic, and a minimalist wireframe.

#### Controls

| Key      | Action                                                         |
| :------- | :------------------------------------------------------------- |
| `Mouse`  | Control the 3D perspective of the projection.                  |
| `Scroll` | Zoom in and out.                                               |
| `Space`  | Pause or resume the animation.                                 |
| `R`      | Reset the view and all rotations.                              |
| `C`      | Toggle **Chaos Mode** for accelerated, unpredictable rotation. |
| `V`      | Cycle through **Visual Modes** (Standard, Neon, Minimal).      |

---

## How to Use

No complex setup is required!

1.  Clone or download this repository.
2.  Open either `e8.html` or `tesseract.html` directly in a modern web browser (like Chrome, Firefox, or Edge).

That's it! Enjoy the journey through higher dimensions.

## Future Work

This project may be expanded with more mathematical objects in the future. Ideas include:

- Other Polytopes (16-cell, 120-cell, etc.)
- Fractal structures (Mandelbulb)
- Other Lie group projections
