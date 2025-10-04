+++
title = "🪄 It's Magic — Multi-Device Multiplayer Game"
date = "2025-01-20"
description = "Experimental multiplayer game exploring distributed interaction across several devices."
[taxonomies]
tags = ["2D", "Unity", "CSharp", "JavaScript", "Java", "Android", "Multiplayer", "Academic", "Game"]
[extra]
cover.image = "images/its-magic-cover.png"
cover.alt = "Its Magic project cover"
category = "Technical"
+++

It’s Magic is an experimental **multiplayer game** exploring **distributed interaction** across several devices.  
Created as a college final project in a team of 4, it combines Unity clients and a mobile app to create a cooperative, immersive potion-making adventure.

💻 **GitHub Repository**

<a href="https://github.com/marcusaasjensen/its-magic">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=marcusaasjensen&repo=its-magic&theme=github_dark_dimmed" alt="Its Magic Repo"/>
</a>

---

## ✨ Overview
Three players cooperate in a magical world using **three different interfaces**:
- **Interactive Table** – Top-down view of the forest and workshop.
- **Vertical Screen** – Side views for detailed actions.
- **Mobile Phone** – Special tools and environment control.

The game encourages **communication and coordination** as each device provides unique perspectives and actions.

---

## 🎯 Goal of the Game
Play as **three wizards** working together to brew a potion before time runs out.

1. **🍄 Harvest Ingredients** – Gather forest ingredients and store them in the bag.  
2. **🥣 Prepare the Cauldron** – Toss ingredients into the cauldron inside the house.  
3. **🪵 Heat the Cauldron** – Move it to the chimney when bubbling starts.  
4. **🔥 Light the Fire** – Use the bellows to ignite the flame.  
5. **⚗️ Finish the Potion** – Wait for dark blue bubbles, then pour the potion into a flask.  
⚠️ **Careful not to spill it!**

---

## 🖥️ Device Interactions

### Interactive Table
- **Multi-touch Selection** – Cooperative harvesting and object manipulation.
- **Drag & Drop** – Move ingredients and reveal hidden areas on the vertical screen with the magic wand.

### Vertical Screen
- **Slash Interaction** – Cut ingredients in the side forest scene.
- **Tap Navigation** – Open doors, trigger objects, and receive hints.

### Mobile Phone
- **💨 Blow into Microphone** – Ignite fires for the cauldron.
- **👜 Throwable Inventory** – Manage and share collected ingredients.
- **💡 Brightness Control** – Change time of day to access night-only resources like fireflies.

---

## ⚙️ Technical Details
- **Unity 3D 2022.3.20f1** for both top and side view clients.
- **Android Studio** for the mobile app.
- **WebSocket Server** handles real-time communication between all devices.

---

## 🔧 Setup

1. **Build the Android App**  
   - Open `Client/Android` in Android Studio and build the APK.

2. **Build Unity Clients**  
   - Create separate builds for the table (top view) and vertical screen.  
   - Update `config.json` with the correct IP/port (see `config.template.json`).

3. **Run the Server**  
   - In the `Server` folder:  
     ```bash
     npm install
     npm run start
     ```

4. **Launch All Clients**  
   - Run each Unity build on different machines and start the Android app.  
   - If the app crashes, simply restart it.

---

## 📸 Gallery

<div style="display: flex; flex-wrap: wrap; gap: 1rem; justify-content: center;">

  <a href="https://github.com/user-attachments/assets/c88956ce-76a6-44bd-89c0-506c72a829f9" style="flex: 1 1 300px; max-width: 500px;">
    <img src="https://github.com/user-attachments/assets/c88956ce-76a6-44bd-89c0-506c72a829f9" alt="Growing Minds Map" style="width:100%; height:auto; border-radius:8px;" />
  </a>

  <a href="https://github.com/user-attachments/assets/fa88282f-da62-46a8-85ce-361a5688d05f" style="flex: 1 1 300px; max-width: 500px;">
    <img src="https://github.com/user-attachments/assets/fa88282f-da62-46a8-85ce-361a5688d05f" alt="Growing Minds Gameplay" style="width:80%; height:auto; border-radius:8px;" />
  </a>

  <a href="https://github.com/user-attachments/assets/1fda0afb-8b20-424d-93fe-37a08c753aa7" style="flex: 1 1 300px; max-width: 500px;">
    <img src="https://github.com/user-attachments/assets/1fda0afb-8b20-424d-93fe-37a08c753aa7" alt="Growing Minds Gameplay" style="width:100%; height:auto; border-radius:8px;" />
  </a>

  <a href="https://github.com/user-attachments/assets/7fb8af25-fdf1-48e5-a896-421157196fef" style="flex: 1 1 300px; max-width: 500px;">
    <img src="https://github.com/user-attachments/assets/7fb8af25-fdf1-48e5-a896-421157196fef" alt="Growing Minds Gameplay" style="width:80%; height:auto; border-radius:8px;" />
  </a>

  <a href="https://github.com/user-attachments/assets/37941215-6dac-43fd-b6bd-b603a2767876" style="flex: 1 1 300px; max-width: 500px;">
    <img src="https://github.com/user-attachments/assets/37941215-6dac-43fd-b6bd-b603a2767876" alt="Growing Minds Gameplay" style="width:100%; height:auto; border-radius:8px;" />
  </a>

  <a href="https://github.com/user-attachments/assets/4f6c4de8-af2b-484a-8e9a-da50e5d9b6d7" style="flex: 1 1 300px; max-width: 500px;">
    <img src="https://github.com/user-attachments/assets/4f6c4de8-af2b-484a-8e9a-da50e5d9b6d7" alt="Growing Minds Gameplay" style="width:100%; height:auto; border-radius:8px;" />
  </a>

  <a href="https://github.com/user-attachments/assets/d76ea95a-ef0e-40fd-84e7-3f354a9114e6" style="flex: 1 1 300px; max-width: 500px;">
    <img src="https://github.com/user-attachments/assets/d76ea95a-ef0e-40fd-84e7-3f354a9114e6" alt="Growing Minds Gameplay" style="width:100%; height:auto; border-radius:8px;" />
  </a>

  <a href="https://github.com/user-attachments/assets/f68f0b1b-a833-4388-92fe-bda12f5c5b30" style="flex: 1 1 300px; max-width: 500px;">
    <img src="https://github.com/user-attachments/assets/f68f0b1b-a833-4388-92fe-bda12f5c5b30" alt="Growing Minds Gameplay" style="width:100%; height:auto; border-radius:8px;" />
  </a>

  <a href="https://github.com/user-attachments/assets/41eaa7d9-6514-45c9-a9b2-a053f608475a" style="flex: 1 1 300px; max-width: 500px;">
    <img src="https://github.com/user-attachments/assets/41eaa7d9-6514-45c9-a9b2-a053f608475a" alt="Growing Minds Gameplay" style="width:100%; height:auto; border-radius:8px;" />
  </a>
</div>
