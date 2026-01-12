# Auto Engine Simulation - Augmented Reality Learning Media

**Auto Engine Simulation** is an Android-based augmented reality (AR) application developed to simulate the 3D working principles of **gasoline** and **diesel engines**.  
The project serves as an **interactive learning medium** for students and teachers of *Light Vehicle Engineering (Teknik Kendaraan Ringan)* at SMK N 1 Kedungwuni.  
This application was developed as a **final thesis project** by *Fattah Chaerul Majid* at *STMIK Widya Pratama Pekalongan*.

---

##  System Overview

The **Auto Engine Simulation** app visualizes the engine cycle and its mechanical processes using **Augmented Reality (AR)**.  
It integrates **3D animation**, **audio narration**, and **textual information** into a real-world environment, helping students understand the theoretical concepts of petrol and diesel engines more effectively.

The development followed the **Multimedia Development Life Cycle (MDLC)** method, which includes:
> Concept → Design → Material Collecting → Assembly → Testing → Distribution  

---

##  Core Features

-  **3D Augmented Reality Simulation**  
  Displays detailed 3D engine components and their motion in AR using Vuforia SDK.

-  **Theoretical Module**  
  Contains 18 pages of theoretical material explaining combustion systems, lubrication, cooling, and fuel mechanisms for both petrol and diesel engines.

-  **Audio Narration**  
  Built-in TTS-based narration and background music to enhance learning immersion.

-  **Interactive Controls**  
  Users can rotate, zoom, and switch between different engine models (gasoline or diesel).

-  **User Interface**  
  Designed with clean visual hierarchy and easy navigation (Splash Screen → Main Menu → Information → Theory → AR Simulation).

-  **Testing and Validation**  
  GUI testing and User Acceptance Test (UAT) with 34 students — resulting in **78.9% user satisfaction**, confirming educational effectiveness.

---

##  Technology Stack

| Layer | Technology |
|-------|-------------|
| **Development Engine** | Unity3D |
| **AR Framework** | Vuforia SDK |
| **3D Modeling** | SketchUp 2022, Blender |
| **Design Tools** | Figma |
| **Audio** | TTSFree.com (narration), Mixkit.co (background music) |
| **Programming Language** | C# |
| **Target Platform** | Android (min. Android 8.0 Oreo) |

---

##  System Requirements

| Component | Minimum Specification |
|------------|------------------------|
| **CPU** | 2.0 GHz |
| **RAM** | 4 GB |
| **Camera** | 4 MP |
| **Android Version** | 8.0 (Oreo) or higher |
| **Storage** | 230 MB free space |

---

##  Application Structure

```
📦 Auto Engine Simulation
 ┣ 📁 Assets/
 ┃ ┣ 📁 Scripts/                 # C# scripts for menu & AR logic
 ┃ ┣ 📁 Models/                  # 3D engine models (gasoline/diesel)
 ┃ ┣ 📁 Animations/              # Blender-exported .fbx animations
 ┃ ┣ 📁 Audio/                   # Narrations & background music
 ┣ 📁 Scenes/
 ┃ ┣ 📄 Splash.unity             # Splash screen
 ┃ ┣ 📄 Menu.unity               # Main menu
 ┃ ┣ 📄 Info.unity               # App information page
 ┃ ┣ 📄 Theory.unity             # Theoretical content module
 ┃ ┣ 📄 ARSimulation.unity       # Augmented Reality scene
 ┣ 📁 Plugins/Vuforia/           # AR SDK configuration
 ┗ 📄 AutoEngineSimulation.apk   # Final Android build
```

---

##  Testing and Evaluation

- **GUI Test** — Verified interface consistency and button functionality across devices.  
- **User Acceptance Test (UAT)** — Conducted with 34 respondents (students).  
  Result: **78.9%** of users agreed that the application effectively improved learning comprehension of engine systems.  
- **Hardware Used** — Redmi 9T (Android 12, 4GB RAM), Oppo A1K (Android 9, 2GB RAM).

---

##  Development Process (MDLC Phases)

1. **Concept:** Identify educational needs in the PMKR (engine maintenance) subject.  
2. **Design:** Create navigation structure, activity diagrams, and GUI mockups in Figma.  
3. **Material Collecting:** Build 3D models, animations, and narration assets.  
4. **Assembly:** Integrate models, animations, and scripts within Unity3D + Vuforia.  
5. **Testing:** Perform GUI and UAT to ensure usability and learning effectiveness.  
6. **Distribution:** Deploy the `.apk` file to students and teachers for classroom and home learning.

---

##  Installation & Usage

1. Download the `.apk` file from the shared Drive folder.  
2. Install it on an Android device (allow installation from unknown sources).  
3. Print or display the **AR marker sheet**.  
4. Launch the app and select **Gasoline Engine** or **Diesel Engine** simulation.  
5. Point the camera toward the marker to view 3D engine animations.  
6. Use on-screen controls to rotate, zoom, or play narration.

---

##  Research Results

- **User Comprehension Increase:** 78.9%  
- **Feedback Summary:**  
  > Teachers found the application aligned with “New Step 1” learning material and helpful for theoretical teaching.  
  > Students reported improved understanding and engagement during theory sessions.  
- **Recommendation:**  
  Future development can implement **markerless AR** or **object tracking**, and expand simulation depth to cover **individual engine components**.

---

##  Repository Description

> Android-based Augmented Reality app that simulates 3D working principles of gasoline and diesel engines. Developed using Unity3D, Vuforia, and Blender following the MDLC methodology.

*(Max. 350 characters for GitHub description)*  
**Description:**  
> Android AR app visualizing gasoline and diesel engine systems in 3D. Built with Unity3D, Vuforia SDK, and Blender. Aimed at enhancing learning for vocational students.

---

## 🏷️ Keywords
`Augmented Reality` `Unity3D` `Vuforia` `Android` `3D Simulation` `Engine` `Education` `MDLC` `Blender` `SketchUp` `Auto Engine Simulation`
