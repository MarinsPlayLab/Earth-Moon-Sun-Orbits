# Earth–Moon–Sun Orbits

A simple, data-informed Unity 6000.3+ WebGL simulation of the Earth–Moon–Sun system, showing basic orbital motion and rotations for educational and visualization purposes.

> This is an illustrative model, not an ephemeris-accurate orbital integrator. It aims for clarity and correct qualitative behavior rather than micro-precision.

## Features

- Heliocentric visualization of the Earth–Moon–Sun system  
- Continuous orbital motion of Earth around the Sun and the Moon around the Earth  
- Basic axial rotation for Earth (day/night cycle) and synchronous rotation for the Moon  
- WebGL-ready scene suitable for embedding on a website  
- Minimal setup designed as a starting point for further experiments and extensions  

## Requirements

- **Unity:** 6000.3 or newer (LTS or latest compatible version)  
- **Modules:**
  - WebGL Build Support  
- **Target platform:** WebGL (desktop and mobile browsers), also runs in the Editor  

## Getting Started

### 1. Clone or download the repository

- Clone the repo via `git clone https://github.com/MarinsPlayLab/Earth-Moon-Sun-Orbits.git`
- Or download it as a ZIP and extract it locally.

### 2. Open in Unity

- Open the project with Unity **6000.3** or newer.  
- Let Unity complete any initial import/upgrade steps.

### 3. Open the main scene

- Go to `Assets/Scenes/`.  
- Open the main scene for the simulation `EarthMoonSun_Orbits.unity`.

### 4. Run in the Editor

- Press **Play** in the Unity Editor to view the orbital simulation.

### 5. Build for WebGL

1. Open **File → Build Settings…**  
2. Set **Platform** to **WebGL** and click **Switch Platform** if needed.  
3. Add the main scene to **Scenes In Build**.  
4. Click **Build** or **Build And Run** to produce a WebGL build for deployment to your website.

## Project Structure

- `Assets/`  
  Core Unity assets (scenes, prefabs, materials, scripts).

- `Assets/Scripts/`  
  C# scripts controlling orbital motion, rotation, and basic camera behavior.

- `ProjectSettings/`  
  Unity project configuration (input, quality, player settings, etc.).

## License

This project is licensed under the **MIT License** – see the `LICENSE` file for details.

You are free to use, modify, and integrate this simulation into your own projects. Attribution by keeping the existing copyright and license notice is appreciated.
