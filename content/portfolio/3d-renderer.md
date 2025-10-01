+++
title = "🖥️ CPU-Based 3D Renderer in C++ From Scratch"
date = "2025-07-01"
description = "A CPU-based 3D renderer written in C++ 20 from scratch (no librairies) with importable object files."
[taxonomies]
tags = ["3D", "Rendering", "CPP", "Graphics", "Software", "Tool"]
[extra]
cover.image = "images/3d-renderer-cover.png"
cover.alt = "3D Renderer project cover"
category = "Technical"
pinned = true
+++

✨ **3D Renderer** is a CPU-based 3D renderer written in C++20, supporting simple primitive shapes and built entirely from scratch. It offers both perspective and orthographic projections and supports simple `.obj` imports.

💻 **GitHub Repository**

<a href="https://github.com/marcusaasjensen/3d-renderer">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=marcusaasjensen&repo=3d-renderer&theme=github_dark_dimmed" alt="3D Renderer Repo"/>
</a>

---

## 🛠️ Features
- 🧱 **Primitive Shapes**: Render basic shapes like cubes, spheres, and pyramids.
- 🖼️ **.obj Import**: Load and render simple **.obj** files.
- 🔄 **Projection Modes**: Switch between perspective and orthographic projections.
- 🖥️ **CPU-Based**: Built entirely from scratch without relying on external graphics libraries.

---

## 🖼️ Rendering Pipeline  

The rendering pipeline transforms **3D objects** from their local definitions into **2D rasterized pixels** on the screen.  

{% mermaid() %}
graph TD;
    A["Object Space<br/>(Local Space)<br/><small>Vertices defined relative to origin</small>"] --> 
    B["World Space<br/><small>Apply transforms (position, rotation, scale)</small>"] --> 
    C["Camera/View Space<br/><small>Relative to camera orientation</small>"] --> 
    D["NDC<br/>(Normalized Device Coordinates)<br/><small>Range [-1, 1]</small>"] --> 
    E["Screen Space<br/><small>Mapped to 2D pixel coords</small>"] --> 
    F["Rasterization<br/><small>Z-Buffer + Triangle Filling</small>"];
{% end %}

---

## 📸 Gallery
*Screenshots of the 3D Renderer in action*

| | | | |
|---|---|---|---|
| [![Shaded View](/images/shaded.png)](/images/shaded.png) | [![Z-Buffer View](/images/3d-renderer-cover.png)](/images/3d-renderer-cover.png) | [![Wireframe](https://github.com/user-attachments/assets/cd2f8b72-7aa9-4921-8a46-783a0146263f)](https://github.com/user-attachments/assets/cd2f8b72-7aa9-4921-8a46-783a0146263f) | [![Suzanne](https://github.com/user-attachments/assets/4ded6d99-e889-4c36-a4d1-b14c8eb235c9)](https://github.com/user-attachments/assets/4ded6d99-e889-4c36-a4d1-b14c8eb235c9) |