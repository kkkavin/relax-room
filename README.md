# MetaWell: VR-Based Mental Wellness Platform

MetaWell is an innovative, immersive Virtual Reality (VR) mental wellness platform designed to provide accessible, stigma-free, and affordable emotional support. By combining spatial audio, immersive environment design, and contextual user interfaces, MetaWell helps users ground themselves and regulate their nervous systems through scientifically structured mindfulness practices.

---

## 🌟 Key Features

### 🏢 Contextual Indoor-to-Outdoor Workflow
* **Minimalist Room Menu:** Users begin inside a calm, beautifully structured minimalist indoor room where a TV-styled **Diegetic UI Canvas** serves as the main menu. This grounds the user immediately and maintains full immersion.
* **Teleport Locomotion:** Using intuitive VR controller pointer interaction, users pick a session and teleport seamlessly outside to a fixed sun chair spot on the beach.
* **Pure VR Skybox View:** Moving the UI indoors leaves the open outdoor environment pristine and free of visual clutter.

### 🌊 Immersive Open-Gaze Beach Environment
* **Live Beach View:** Features an expansive, serene tropical shore flanked by trees and a vast horizon line.
* **Spatial Audio Integration:** High-fidelity 3D audio tracks ocean waves and environmental wind patterns to maximize relaxation.
* **Eyes-Open Mindfulness:** All sessions are meticulously engineered to be practiced with the eyes *open*, leveraging natural focal elements to anchor user attention, optimize heart rate variability (HRV), and completely eliminate VR motion sickness.

---

## 🧘 Guided Breathing Sessions

The platform features 4 distinct open-gaze breathing tracks (capped under 5 minutes each) designed for high-impact grounding using natural anchors in the scene:

1. **The Horizon Box Breath (4-4-4-4 Rhythm)**
   * *Focus:* Mental clarity and clearing racing thoughts.
   * *Mechanism:* Guides the user's open gaze to trace a square path mentally using the massive, straight horizon line and shoreline.
2. **The Shoreline Tide Breath (4-7-8 Natural Tranquilizer)**
   * *Focus:* Deep relaxation and parasympathetic nervous system activation.
   * *Mechanism:* Synchronizes deep inhalations and long, smooth structural exhalations with the spatial sound of waves breaking and retreating along the shoreline sand.
3. **The Peripheral Ocean Gazing (5-5 Coherent Flow)**
   * *Focus:* Anxiety reduction and lowering hyper-vigilance.
   * *Mechanism:* Instructs the user to soften their focal gaze and expand awareness into their peripheral vision, taking in the vast left-to-right expanse of the sky and ocean simultaneously.
4. **The Minimalist Two-Point Grounding Breath (Paced Visual Tracking)**
   * *Focus:* Mind centering and disrupting acute stress loops.
   * *Mechanism:* Employs a gradually lengthening rhythm (scaling from 3s to 6s cycles) while tracking the eyes horizontally between an indoor structural architectural beam on the left and a natural beach anchor on the right (similar to EMDR principles).

---

## 🛠️ Tech Stack & Prerequisites

* **Engine:** Unity 3D (2022.3 LTS or higher recommended)
* **Language:** C#
* **XR Architecture:** OpenXR Plugin / XR Interaction Toolkit (XRI)
* **Hardware Target:** Meta Quest 2 / Quest 3 / Quest Pro (Standalone Android deployment)
* **Audio:** Unity Spatial Audio Engine

---

## 📦 Project Directory Structure

├── Assets/
│   ├── _Project/
│   │   ├── Audio/               # Spatial beach soundscapes & Guided Session voiceovers
│   │   ├── Environments/        # Minimalist room meshes, beach sand models, foliage
│   │   ├── Materials/           # Skybox textures (2:1 panoramic wrapped) & custom shaders
│   │   ├── Prefabs/             # Sun chair anchors, Teleportation areas, World-space TV UI
│   │   ├── Scenes/              # Main_Relaxation_Space.unity
│   │   └── Scripts/             # Locomotion control, Audio triggers, and UI button mappings

## ⚙️ Setup & Installation
Clone the Repository:

1. Bash
git clone https://github.com/kkkavin/relax-room.git

2. Open in Unity:

* Open the Unity Hub, click Add, and select the cloned project folder.

* Ensure your editor version matches or is compatible with the project specifications.

3. Configure XR Settings:

* Navigate to Edit > Project Settings > XR Plug-in Management.

* Under the Android tab, ensure OpenXR or Oculus is selected.

4. Build & Run:

* Connect your Meta Quest device via Link cable or AirLink.

* Go to File > Build Settings, switch platform target to Android, choose your scene, and click Build and Run.
