# Software Engineering Project Portfolio

**Author: Adiandra Nallakka Gari Supritha**

This repository brings together a diverse set of software engineering projects developed across algorithm design, graphics rendering, system-level analysis, and Android development. Each project highlights practical applications of computer science principles, written with attention to performance and modular design.

---

##Featured Projects

###  N-Queens Problem Solver
Solves the classical N-Queens puzzle using an optimized backtracking strategy that includes diagonal conflict tracking.

- **Language**: C++
- **Highlights**:
  - Constant-time safety checks using boolean arrays
  - Supports dynamic board sizes (N ≤ 9)
  - Clean CLI interaction and efficient pruning logic

---

### Module Dependency Cycle Detector
Detects cyclic dependencies in module graphs using DFS with state-tracking.

- **Language**: C++
- **Highlights**:
  - Depth-first traversal with unvisited/visiting/visited states
  - Handles thousands of modules and edges efficiently
  - Useful for analyzing package imports and build systems

---

###   GPU-Based Fireworks Simulator
Simulates fireworks using real-time rendering powered by OpenGL ES 3.0 and custom shaders.

- **Language**: C++
- **Features**:
  - Over 5,000 particles rendered at high frame rates
  - Interactive explosion control via mouse clicks
  - Visual enhancements using instancing and additive blending

---

###  WeatherTrack Android App
An Android app that shows weather trends using MVVM architecture, Room database, and background updates via WorkManager.

- **Language**: Kotlin
- **Features**:
  - LiveData observers for UI responsiveness
  - Automatic sync every 6 hours
  - Battery-efficient scheduling and error handling
  - Offline data access and weekly trends visualization

---

##  Technologies Used

- **Languages**: C++, Kotlin, GLSL
- **Libraries/Frameworks**: OpenGL, Android Jetpack, Room, WorkManager
- **Concepts**: Backtracking, Graph Algorithms, Shader Programming, MVVM

---

##  Setup & Installation

### Prerequisites

```bash
# For C++ Projects
sudo apt install build-essential cmake g++

# For Fireworks Simulation
sudo apt install libglew-dev libglfw3-dev libglm-dev

# For Android App
Android Studio (v4.0+), Java 8, Android SDK (API 21+)

