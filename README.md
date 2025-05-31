# VisualSystem-GraphicsProject
README: Visual Tour of the Human Visual System
Project Overview
Welcome to the Visualizing the Human Visual System project — a 3D educational experience developed in Blender as part of the "Computer Graphics and Visualization" course (SBES 140), Spring 2025, Cairo University.

This project provides an immersive journey through the structure and function of the human eye, from the cornea to the visual cortex, using 3D modeling, animation, and camera navigation.
Project Structure
visual-system-tour/
├── models/                # Blender (.blend) files and 3D assets
├── textures/              # Image files used as textures
├── renders/               # Final renders and animation frames
├── scripts/               # Blender Python scripts (if any)
├── README.md              # This file
└── docs/
    └── VisualSystem.pdf   # Project documentation (analysis, design, implementation)
Objectives
- Model key anatomical components of the human visual system.
- Animate light's path through the eye and simulate image formation on the retina.
- Provide smooth camera transitions to guide viewers through each visual structure.
- Support interactive understanding for educational purposes.
Components Modeled
- External Eye Structures: Cornea, Sclera, Iris, Pupil, Lens
- Internal Eye: Aqueous/Vitreous Humors, Retina, Fovea
- Neural Pathway: Optic Nerve, Optic Chiasm, Optic Tracts, LGN, Primary Visual Cortex (V1)
Technologies Used
- Blender (v4.4.3): 3D modeling, animation, and rendering
- Python for Blender: Scripting camera paths
- FFmpeg: Video rendering 
Walkthrough Features
- Zoom-ins on anatomical structures
- Camera flythrough via animation keyframes
- Label overlays for educational annotation
- Animation of light refraction through lens to retina
- Signal tracing from retina to visual cortex
How to Use
1. Open the `.blend` file in Blender.
2. Press `Spacebar` or select the timeline and hit `Play` to start the animation.
3. To render a video:
   - Go to `Render Properties` > Output
   - Choose resolution and output format (e.g., MP4)
   - Click `Render` > `Render Animation`
Report & Documentation
The full documentation of the anatomical design, modeling steps, rendering strategy, and educational goals is available in `docs/VisualSystem.pdf`.
Future Enhancements
- Add VR compatibility for Oculus or Cardboard.
- Introduce interactive click-based anatomy exploration.
- Expand to include diseases of the visual system and their visual effects.
