# VR Toybox (Unity / Oculus SDK)

## 🎮 Overview
A WWII-inspired VR Tower Defense experience developed for Meta Quest. Players engage in a "Tabletop War" from a god-view perspective, utilizing both strategic turret placement and direct first-person "Hand Cannon" mechanics to repel waves of enemies.

## 🛠 Key Responsibilities & Features
* **Advanced Ballistics System**: Implemented a real-time physics-based projectile system using `Raycast` and `Rigidbody` for high-precision hit detection and explosive effects.
* **Intelligent Turret AI**: Developed a multi-stage target acquisition and automated firing system.
* **Lead Shooting Algorithm**: Engineered a predictive aiming module that calculates enemy velocity and trajectory to ensure controllable accuracy for automated turrets.
* **Immersive Interaction**: Designed the "God-View" tabletop interaction paradigm, focusing on low-latency feedback and physical presence within the VR space.

## 🚀 Technical Highlights
* **Optimized Physics**: Balanced high-frequency Raycast calls with Rigidbody physics to maintain stable 72/90 FPS on mobile VR hardware.
* **Predictive Math**: Applied vector intercept calculations for the lead-shooting logic, allowing for adjustable "difficulty" by tuning the prediction error margin.
