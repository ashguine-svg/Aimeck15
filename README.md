# 👁️ Aimeck15 - Intelligent Image Recognition Auto-Clicker

<!-- ここにGitHub_splash.mp4をドラッグ＆ドロップしてください -->
<div align="center">
  <video src="https://github.com/user-attachments/assets/93a77554-e704-4ef9-b523-17c6133155da" width="600" />
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Rust-orange.svg" alt="Rust">
  <img src="https://img.shields.io/badge/UI-Slint-blue.svg" alt="Slint">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20(X11)-lightgray.svg" alt="Platform">
  <img src="https://img.shields.io/badge/Vision-Custom%20OpenCV%20(SIMD)-green.svg" alt="OpenCV">
</p>

## 🚀 What is Aimeck15?
Aimeck15 is NOT just another simple coordinate-based auto-clicker. It is a **next-generation autonomous bot engine** built from scratch in Rust and Slint. 

Designed for high performance and strict anti-cheat evasion, Aimeck15 utilizes a custom SIMD-optimized OpenCV implementation to achieve 100+ FPS image matching with near-zero CPU overhead. Whether you are automating tedious game loops or building complex logical workflows, Aimeck15 handles it seamlessly across Windows and Linux (X11).

## ✨ Key Features
* 👁️ **Intelligent Image & Text Recognition (OCR)**
  Stop clicking blindly. Aimeck15 reads the screen, recognizes target HP bars, icons, and live text, and executes actions only when specific conditions are met.
* ⚡ **Blazing Fast & Lightweight**
  Fully asynchronous multitasking architecture written in Rust. It runs incredibly fast without freezing your system.
* 🔀 **No-Code Complex Workflows**
  Build advanced logic (e.g., "If A appears, do B. If C fails, run recovery sequence D") through an intuitive, modern UI built with Slint.
* 🛡️ **Auto-Recovery & Discord Alerts**
  Unexpected crash? Aimeck15 detects drops and restarts the target process automatically. It also sends periodic status reports and alerts directly to your Discord.

---

## 💀 The "Crazy" Part: Humanized Mouse Trajectories
Most macro tools use simple Bezier curves for mouse movement, which modern anti-cheats can flag instantly. 

**I didn't want to take that risk.** 
Instead of relying on math formulas, I physically sampled my own wrist movements—capturing millisecond-level velocity and distance fluctuations—and baked them into `human_profiles.json`. Aimeck15 drives the mouse simulation using this real-world biomechanical data, making the cursor movements virtually indistinguishable from a real human playing the game. 

---

## 🎁 14-Day Free Trial
Experience the power of intelligent automation yourself. A fully functional 14-day trial is included in the latest release.

### [📥 Download the Latest Release (v1.3.6) Here](https://github.com/ashguine-svg/Aimeck15/releases/tag/v1.3.6)

### How to run:
**For Windows:**
Simply download `Aimeck15_v1.3.6_Windows_x64.zip`, extract, and run the executable.

**For Linux (X11):**
Download `Aimeck15_v1.3.6_Linux_x64_X11.zip`, extract, grant execution permissions, and run.
*(Note: Wayland is currently not supported due to strict input injection and screen capture security models. Please use an X11 session or XWayland.)*

---

## 💬 Feedback & Support
I built this tool to push the boundaries of what native desktop macros can do. I would love to hear your feedback on the architecture, the Slint UI integration, or the computer vision performance! 

Join our community on Discord to share your thoughts, ask questions, or just chat about the project:
**[💬 Join the Aimeck15 Discord](https://discord.gg/586GP3Ffj)**
