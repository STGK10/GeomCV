# GeomCV
A lightweight C++ computational geometry library and interactive Learning with OpenCV-powered visualizations.
GeomCV designed for both developers and learners, as it provides clean implementations of classic geometric algorithms (like segment intersections, convex hulls, polygon simplification, etc.) with a built-in visual layer using OpenCV to explore and debug geometry interactively.

## ✨ Features

- 🧮 Core 2D Geometry: intersection, convex hulls, area, decimation
- 🖱️ Mouse-driven visualization using OpenCV
- 📷 Process contours from images
- 🎯 Easy to extend for academic or industrial applications

# Project Structure
GeomCV/
├── include/         # Headers for geometry + visualization
├── src/             # C++ implementations
├── demos/           # Interactive demos
├── images/          # Sample images for contour processing
├── CMakeLists.txt   # Build script
└── README.md

#Directory Structure
GeomCV/
├── include/
│   ├── geomcv.hpp            # Master header
│   ├── geometry_core.hpp     # Algorithms
│   └── visualizer.hpp        # Drawing functions
│
├── src/
│   ├── geometry_core.cpp
│   └── visualizer.cpp
│
├── demos/
│   ├── convex_hull_demo.cpp
│   ├── intersect_segments_demo.cpp
│   ├── polygon_simplify_demo.cpp
│
├── images/
│   └── test_shapes.png
│
├── CMakeLists.txt
└── README.md


### 🔧 Prerequisites
- C++17 or newer
- OpenCV (>= 4.x)
- CMake (>= 3.15)

### 🛠️ Build
```bash
git clone https://github.com/STGK10/GeomCV.git
cd GeomCV
mkdir build && cd build
cmake ..
make
