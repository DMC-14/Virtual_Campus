# Interactive 3D Campus Viewer 🏛️

This repository hosts the 3D assets and web interface for my college research capstone project. It features an interactive, web-based 3D viewer designed for seamless architectural exploration and navigation of the SUNN campuses.

🚀 **Live Demo**
Experience the 3D viewer here: [Interactive Campus Viewer](#)

✨ **Features**
* **Interactive UI Navigation:** A custom, dark-mode sidebar menu allows users to seamlessly switch between different campus structures and isolate specific administrative or academic buildings.
* **Architectural Exploration:** Users can interact with distinct building meshes and navigate the environment to understand the spatial layout of the campus.
* **Web-Native Rendering:** Uses optimized web technologies to display 3D models directly in the browser without requiring external software.
* **Guided Camera Constraints:** Locked ground-level and orbital camera constraints provide a smooth, collision-free walkthrough, preventing the camera from clipping underground or phasing through structures.
* **Performance Focused:** Utilizes highly optimized `.glb` formats and loading overlays for smoother rendering across desktop and mobile devices.

📂 **Repository Structure**
* `index.html`: The core front-end interface containing the UI sidebar, title card, and viewer scripts.
* `Old_Sagay_Campus.glb` / `building.glb` / `Compound.glb`: The 3D architectural models designed and exported from Blender.
* `HDRI_puresky_1k.hdr`: The environment map used for realistic outdoor lighting data.
