<img width="736" height="980" alt="Untitled (1)" src="https://github.com/user-attachments/assets/75b8b568-6c43-4555-811c-789109a95d86" />

# Cursed-Technique
​Cursed Technique is a real-time, gesture-based AR visualizer inspired by Jujutsu Kaisen (呪術廻戦).
Using your device’s camera, it detects hand gestures and manifests cursed techniques in the world around you through immersive particle-based visual effects.

The project is optimize for the mobile devices. it combines MediaPipe hand tracking with Three.js rendering to recreate iconic abilities from the series directly in the browser.

---

# Features

This project utilizes particle systems and real-time gesture detection to render volume-based cursed techniques.

1. Secret Technique: Hollow Purple

   - Visuals:
A chaotic singularity combining attraction and repulsion.

   - Trigger:
Pinch gesture (thumb + index finger touching).


2. Domain Expansion: Infinite Void

   - Visuals:
A multi-layered celestial domain featuring: a bright event horizon ring

   - Trigger:
Cross gesture (index + middle fingers crossed).


3. Cursed Technique Reversal: Red

   - Visuals:
A blinding white-hot core generating a violent, jagged sphere of repulsive force.

   - Trigger:
Index finger pointing upward.

4. Domain Expansion: Malevolent Shrine
   - Visuals:
     The shrine takes the form of a derelict, open-air Buddhist temple.
   - Trigger:
     Flat hand/Prayer gesture
---

# Getting Started

Prerequisites You need:

  - A modern browser (Chrome, Edge, or Firefox)
  - Internet access for loading libraries

---

# Run the project

Open the Link:

https://cursed-technique.netlify.app/

Then:

1. Click on Camera button
2. Allow all the necessary permission.

Your browser will run the project automatically.

---

# How It Works

The system pipeline works like this:

Camera → MediaPipe Hand Tracking → Gesture Detection → Three.js Particle System → Rendered Cursed Technique

1. MediaPipe tracks hand landmarks in real time.
2. The gesture recognition system interprets finger positions.
3. Each recognized gesture activates a specific technique.
4. Three.js generates particle-based volumetric effects in a 3D scene.

---

# Note

This project was built and powered by Google Gemini 3. it's created for experimental purposes inspired by the Jujutsu Kaisen universe.
