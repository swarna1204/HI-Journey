# 🌱 Hyper Island Journey — Immersive WebXR Experience

An interactive WebXR project built with A-Frame that tells the story of my personal and professional growth through spatial storytelling, immersive visuals, and user-driven interaction.

---

## 🎯 Project Goal

To design and build an immersive web experience that meaningfully combines **visual, spatial, and interactive elements** using **industry-relevant tools**, and to engage the user with a personal journey that evokes reflection and emotional connection.

---

## 🔧 Tools & Technologies Used

- **A-Frame** (v1.5.0) — WebXR framework for immersive scenes
- **TWEEN.js** — Smooth camera animations
- **Three.js** (underlying engine of A-Frame)
- **GLB 3D Room Model** — Custom isometric environment
- **Custom JavaScript Logic** — VR controller interaction, story overlays, raycasting
- **Audio Integration** — Background music playback
- **Meta Quest 3 Testing** — Physical headset tested and debugged

---

## 🧾 Key Features

| Feature | Description |
|--------|-------------|
| 🎮 Dual-mode Interactivity | Works on both Desktop and VR (Meta Quest 3) with mouse & hand controllers |
| 📖 Story Overlays | Each object reveals part of my personal journey when interacted with |
| 🎥 Smooth Camera Zoom | Focuses on objects when clicked using TWEEN.js for elegant movement |
| 🪟 Responsive UI | Desktop text overlays + VR panels with titles and messages |
| 🎵 Background Music | Looping audio enhances atmosphere (plays on first click for autoplay policy) |
| 🌌 Spatial Design | Carefully positioned lighting, model scaling, and object placements for immersion |

---

## ✨ Narrative Highlights

This experience tells the story of my journey:
- **The Bed**: Balancing motherhood and ambition
- **The Monitor**: Late-night coding and job hunting
- **The Plant**: Finding roots in a new country
- **The Light**: The final realization and hope for future growth

Each object is selected for symbolic meaning and placed intentionally within the space.

---

## 🔍 User Testing & Iteration

I tested this experience on **Meta Quest 3** and desktop browsers. Based on feedback and real-world testing, I made the following improvements:

- ✅ **Fixed VR hand controller click detection** for multiple objects
- ✅ **Refined camera positioning logic** to zoom correctly to different mesh targets
- ✅ **Added object name recognition mapping** for better story targeting (e.g. 'monitor001_3' → Monitor)
- ✅ **Ensured text overlays appear uniquely** per object in both VR and non-VR modes
- ✅ **Simplified UX with back buttons** and entry/exit animations

---

## 🪞 Critical Reflection

This project challenged me to combine **storytelling, code, and spatial design** into one cohesive experience. I learned how to:

- Work with **3D assets** and structure complex scenes
- Debug **WebXR interactions** across devices
- Design emotionally resonant experiences using minimal elements
- Align user input (controller clicks, cursor clicks) to dynamic UI responses

If I had more time, I would:
- Add **audio narration** per story
- Build out additional scenes as part of a journey progression
- Integrate **analytics or feedback tracking** to see how users interact with the space

---

## 🏁 Conclusion

This immersive experience is a heartfelt reflection of my time at Hyper Island and the resilience behind my learning path. It combines technical execution with personal storytelling—inviting the user to explore not just a room, but a life in motion.

---
