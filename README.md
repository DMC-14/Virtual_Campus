# Interactive 3D Campus Viewer 🏛️

This repository hosts the 3D assets and web interface for my college research capstone project. It features an interactive, web-based 3D viewer that visualizes the architectural transition of the Old Sagay High School campus from the past to the present.

## 🚀 Live Demo
**Experience the 3D viewer here:** [Interactive Campus Viewer](https://atlas395.github.io/3D-Assets/)

## ✨ Features
* **Web-Native Rendering:** Uses Google's `<model-viewer>` component to display 3D models directly in the browser without requiring external software.
* **Interactive UI:** A custom dropdown menu allows users to seamlessly switch between different campus structures (e.g., Present Main Building vs. Old Campus Compound).
* **Realistic Lighting:** Utilizes a 1K HDRI skybox for natural outdoor sunlight and realistic surface reflections.
* **Guided Camera:** Locked ground-level camera constraints provide a pedestrian-level architectural walkthrough, preventing the camera from clipping underground.
* **Performance Focused:** Includes loading overlays and utilizes optimized `.glb` formats for smoother viewing across desktop and mobile devices.

## 📂 Repository Structure
* `index.html`: The core front-end interface containing the UI layout, loading animations, and viewer scripts.
* `Old_Sagay_Campus.glb` / `building.glb` / `Compound.glb`: The 3D architectural models designed and exported from Blender.
* `HDRI_puresky_1k.hdr`: The environment map used for skybox rendering and lighting data.

## 🛠️ Tech Stack
* **3D Modeling & Texturing:** Blender
* **Web Rendering:** HTML5, CSS3, Vanilla JavaScript, `<model-viewer>`
* **Deployment & Hosting:** GitHub Pages

---
*Developed by Daniel for capstone research presentation.*
