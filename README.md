# GeomCV
A lightweight C++ computational geometry library and interactive Learning with OpenCV-powered visualizations.
GeomCV designed for both developers and learners, as it provides clean implementations of classic geometric algorithms (like segment intersections, convex hulls, polygon simplification, etc.) with a built-in visual layer using OpenCV to explore and debug geometry interactively.

## ✨ Features

- 🧮 Core 2D Geometry: intersection, convex hulls, area, decimation
- 🖱️ Mouse-driven visualization using OpenCV
- 📷 Process contours from images
- 🎯 Easy to extend for academic or industrial applications



---

### **Project Structure**  
**GeomCV/**  
├── 📂 **include/**           → Headers for geometry and visualization  
│    ├── `geomcv.hpp`         → Master header for the project  
│    ├── `geometry_core.hpp`  → Core geometry algorithms  
│    └── `visualizer.hpp`     → Header for drawing functions  
├── 📂 **src/**               → C++ source implementations  
│    ├── `geometry_core.cpp`  → Core geometry algorithms  
│    └── `visualizer.cpp`     → Functions for visualization  
├── 📂 **demos/**             → Interactive demos for geometric operations  
│    ├── `convex_hull_demo.cpp` → Demonstrates convex hull computation  
│    ├── `intersect_segments_demo.cpp` → Segment intersection demo  
│    └── `polygon_simplify_demo.cpp`  → Polygon simplification demo  
├── 📂 **images/**            → Sample images for testing and processing  
│    └── `test_shapes.png`    → Test image for contour processing  
├── 📜 `CMakeLists.txt`       → Build script for project  
└── 📜 `README.md`            → Project documentation

---



##### 🔧 Prerequisites
- C++17 or newer
- OpenCV (>= 4.x)
- CMake (>= 3.15)

###### 🛠️ Build
```bash
git clone https://github.com/STGK10/GeomCV.git
cd GeomCV
mkdir build && cd build
cmake ..
make
