# 🚀 Space Shooter Pro (Windows Build)

Welcome to **Space Shooter Pro**, a fast-paced 2D action game built in **Unity 6**.  
Take control of your spaceship, dodge incoming enemies, and blast your way to the highest score!</br>
This is my **first Unity 2D Game**.

---

## 🕹️ Game Overview

**Space Shooter Pro** is a classic arcade-style shooter inspired by retro space games — rebuilt with modern effects, post-processing, and optimized performance using Unity’s **URP (Universal Render Pipeline)**.

### 🎯 Features
- Smooth 2D gameplay with responsive controls  
- Power-ups like triple-shot, speed-boost and shield mechanics  
- Post-processing effects (Bloom, Color Grading)  
- Player health and scoring system  
- Enemy wave spawner system
- Responsive Explosions and Sound effects
- Built for Windows using **Unity 6**

---

## 📦 Repository Contents

This repository contains the **Windows build** of the game:

### 📁 Directory Structure

```
Space-Shooter-Pro-Windows/
├── 📂 D3D12/
│ └── Direct3D 12 dependencies required for Windows graphics
├── 📂 MonoBleedingEdge/
│ └── Mono runtime files used by Unity for scripting
├── 📂 Space Shooter Pro_BurstDebugInformation_DoNotShip/
│ └── ⚠️ Debug information, not required for release
│ └── Data/
│ └── Plugins/
│ └── x86_64/ (platform-specific plugin binaries)
├── 📂 Space Shooter Pro_Data/
│ ├── 📂 Managed/ (compiled C# assemblies and Unity DLLs)
│ ├── 📂 Plugins/ (Unity plugin files)
│ ├── 📄 resources.assets (Unity game resources)
│ ├── 📄 sharedassets0.assets
│ ├── 📄 sharedassets1.assets
│ └── … (other Unity-generated data files)
├── 📄 .gitattributes (Git LFS tracking configuration)
├── 📄 Space Shooter Pro.exe (main Windows executable)
├── 📄 UnityCrashHandler64.exe (Unity crash handler)
├── 📄 UnityPlayer.dll (Unity runtime DLL)
└── 📄 Space Shooter Pro-Windows.rar (compressed build for download)
```

Here’s an overview of the **Space Shooter Pro Windows build** repository:



> ⚙️ Note: All large build files are managed using **Git LFS (Large File Storage)**. 

### 🔹 Notes
- All large files (`.exe`, `.dll`, `.resS`, `.assets`) are managed using **Git LFS**.  
- The `.rar` file is the full Windows build ready to run.  
- `Space Shooter Pro_BurstDebugInformation_DoNotShip` can be ignored by players — it contains debug info for developers.

---

## 🧩 How to Play

1. **Download the build**
   - Go to the [Releases](../../releases) page.
   - Download the latest `.zip` build and extract it.

2. **Run the game**
   - Double-click **`Space Shooter Pro.exe`**.

3. **Controls**
   - **Arrow keys / WASD** → Move your ship  
   - **Spacebar** → Fire lasers

---

## 🧠 Development Details

| Engine | Version |
|:-------|:---------|
| Unity  | 6    |
| Render Pipeline | URP |
| Platform | Windows (D3D12) |

---

## 🧰 Technologies Used

- **Unity 6**
- **C# (Mono Runtime)**
- **URP (Universal Render Pipeline)**
- **Git LFS** for large asset management
- **Visual Studio / Rider** for scripting

---

## 🧑‍💻 Developer

**Rajat Singh**  
🎮 Game Developer | Web & Software Engineer
🌐 [GitHub Profile](https://github.com/Rajatsingh900k)

---

## ⚖️ License

This project is released for educational and demonstration purposes.  
You may play, share, or modify the build for non-commercial use.

---

> 💬 *If you enjoyed playing Space Shooter Pro, don’t forget to star ⭐ this repository!*


