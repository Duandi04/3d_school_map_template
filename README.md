# 3D School Map Template

An interactive 3D school map template built using **Three.js** and **ES Modules**. This project provides a modern campus visualization with detailed interaction features for each building.

## 🚀 Key Features

- **Interactive 3D Visualization**: Free navigation using mouse/touch controls (OrbitControls).
- **Building Details**: Dynamic info panels that appear when hovering over specific buildings.
- **Exploration Controls**:
  - Reset Camera to return to the home view.
  - Auto-Rotate mode for automatic presentations.
- **Display Options**:
  - Wireframe Mode to view the geometric structure.
  - Toggle Shadows for performance or aesthetic preferences.
- **Responsive Design**: UI that adapts to various screen sizes (Desktop & Mobile).
- **No Build Tools Required**: Utilizes ES Modules directly from CDN (Unpkg), requiring no `npm install` or compilation steps.

## 🛠️ Technologies Used

- **Three.js (r158)**: Core library for 3D rendering.
- **Vanilla JavaScript (ES Modules)**: Application logic.
- **CSS3**: Modern UI design featuring glassmorphism (backdrop-filter) and smooth animations.
- **HTML5**: Page structure.

## 📋 Included Buildings/Complexes

1. **Main Administrative Complex**: Central hub for administration and reception.
2. **Digital Learning Library**: Resource center with computer lab facilities.
3. **Athletic & Wellness Center**: Sports complex and swimming pool.
4. **STEM Research Center**: Advanced science research laboratories.
5. **Primary Academic Hall**: Main educational building.
6. **Creative Arts Wing**: Dedicated area for arts, music, and drama.
7. **Community Dining Hall**: Cafeteria and social space.
8. **Performing Arts Theater**: Professional performance venue.

## 📖 How to Use

### Running Locally

Since this project uses ES Modules, you must run it through a web server (rather than opening the `.html` file directly in a browser).

1. **Using VS Code (Live Server)**:
   - Install the `Live Server` extension.
   - Right-click `index.html` and select **Open with Live Server**.

2. **Using Python**:
   ```bash
   python -m http.server 8000
   ```
   Open `http://localhost:8000` in your browser.

3. **Using Node.js (serve)**:
   ```bash
   npx serve .
   ```

### Navigation Controls
- **Left Click + Drag**: Rotate camera (Orbit).
- **Scroll**: Zoom In/Out.
- **Right Click + Drag**: Move camera position (Pan).
- **Hover Building**: Display detailed information in the side panel.

## 📁 Project Structure

```text
3d_school_map_template/
├── index.html    # Contains HTML, CSS, and Three.js Logic (Single File)
└── README.md     # Project documentation
```

## 📄 License

This project is licensed under the [MIT License](LICENSE). You are free to modify and use it for personal or commercial purposes.
