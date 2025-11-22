<h1 align="center">🎮 TroyMetrics GamerStats 1080p</h1>
<p align="center">RTSS / RivaTuner Overlays by TroyMetrics 👻</p>

<div align="center">
  <a href="https://youtu.be/Diy7iYxleP8">
    <img src="https://github.com/TroyMetrics/TM-GamerStats-1080p/blob/main/assets/Thumbnail_2.png?raw=true" width="850">
  </a>
</div>

## 🌈 Animated Multi-Color Gradient (Experimental)

<p align="center">
  <img src="https://github.com/TroyMetrics/TM-GamerStats-1080p/blob/main/assets/Preview.png?raw=true" alt="Preview">
</p>

This is an experimental overlay created to test whether a multi-color animated gradient can be achieved inside RTSS Overlay Editor,

Turns out… **it can**. Sort of.. 😂

v1.2 includes everything you need to download, load, and test the effect instantly.

---

## ⚙️ How It Works

The multi-color animation is built from **six stacked layers**, each referencing one of the six sprites from the included .png sprite sheet. These layers combine into a flowing rainbow effect through:

- **Dynamic Color Regions** – Each sprite fades in/out based on a shared timer.  
- **Master “R1” Timer Sensor** – R1 cycles from **0 → 6000 ms** repeatedly, and all six layers reference this timer to determine their fade boundaries and visibility windows.  
- **Layer-Specific Visibility Rules** – Each sprite becomes visible only during its assigned section of the R1 cycle, creating a smooth multi-color sweep across the overlay.  
- **RainbowSpeed** Sensor – A dedicated multiplier that lets you speed up or slow down the animation by editing its **Correction formula**.  
  - Increase the multiplier = faster gradient  
  - Decrease the multiplier = slower, smoother motion  

---

## 🗃️ What’s Included

- **TM GamerStats RGB 1080p.ovl**  
  Experimental version featuring the full animated multi-color gradient from the video.

- **TM GamerStats SimpCity 1080p.ovl**  
  A clean, plain-white variant with no animation — perfect as a **template** for your own designs.

- **TM GamerStats Color-Mod 1080p.ovl**  
  A 2-Tone Color-Mod version that allows near-instant color theme changes through the **Color** sensor.
  > 🧙‍♂️ **[Learn how to change the Color](#-color-mod-color-adjustment)**

---

# 🛠️ Setup & Installation

## ✅ Prerequisites

Before setting up the TM GamerStats 1080p Overlay, make sure the following software is installed and properly configured:

**✅ MSI Afterburner + RivaTuner Statistics Server (RTSS)**

🔽 Download the latest BETA versions of **MSI Afterburner & RTSS** from [www.guru3d.com](https://www.guru3d.com/files-details/msi-afterburner-beta-download.html)
> 📝 Note: The latest beta builds are often shared exclusively on the official Guru3D forums by the developer, Unwinder.
- The MSI Afterburner installer includes **RivaTuner Statistics Server (RTSS)** as a bundle — this is required for the overlay to function.
- During installation, ensure that **✅ RivaTuner Statistics Server** is left **check-marked.**
- 
---

## 🛠️ Setup Instructions

**1. 📦 Extract and Prepare Files**
- Open the downloaded package: **`TM GamerStats 1080p`**
- In a **new File Explorer window**, navigate to your **`C:\` drive**

**2. 📁 Copy Overlay Files to RTSS**
- **Drag and drop** (or **copy/paste**) the folder named **`Program Files (x86)`** from the downloaded package directly into your **`C:\` drive**
- If prompted for admin permission:
  - ✅ Check **"Do this for all current items"**
  - ✅ Click **"Continue"**

> This step places the overlay files in the correct RTSS directory.

---

**3. 🔤 Install the Required Font**
- Navigate to:  
  `C:\Program Files (x86)\RivaTuner Statistics Server\Fonts`
- Double-click to install the fonts: **Armstrong.otf** and **Armstrong-Extrabold.otf**

---

**4. ⚙️ Enable OverlayEditor in RTSS**
1. Launch **RivaTuner Statistics Server (RTSS)**  
2. Click the **`[Setup]`** button  
3. In the new window, go to the **Plugins** tab:
   - ✅ Enable **`OverlayEditor.dll`**
   - ✅ (Optional but recommended) Enable **`HotkeyHandler.dll`**
     - Highlight **`HotkeyHandler.dll`** & Click **`[Setup]`** at the bottom to assign hotkeys:
       - **Toggle On-Screen Display**: e.g., `Home`
       - **Begin/End Recording**: e.g., `Page Up / Page Down`

> ⚠️ If you’ve already assigned hotkeys in **MSI Afterburner**, you can skip this step or unassign them there. Only **one program** should manage OSD hotkeys to avoid conflicts.

---

**5. 🎛 Load the Overlay in OverlayEditor**
1. With **OverlayEditor.dll** enabled, double-click it or click **`[Setup]`** after high-lighting it 
2. In the Overlay Editor window:
   - Go to the **`Layouts`** tab → Click **`Load`**
   - Select one of the **`TM GamerStats`** presets → Click **`Open`**

---

**6. 🧠 Apply Master Settings (Important)**
> 🧙‍♂️ This step only applies to presets that are not locked.
- Since **RTSS Beta 7.3.2**, you can now use **`Ctrl + Shift + M`** to apply the overlay’s master layout settings. Otherwise, follow the steps below for manual application.
- Back in the **Layouts** tab → Click **`Edit`**
- In the **Overlay Properties** window:
  - Click **`[Master Settings]`**
  - Click **`Yes`** when prompted
  - Click **`OK`** to finalize

✅ Your overlay is now fully active and ready to use!

## 🎨 Color-Mod (Color Adjustment)

The following settings apply specifically to these presets:  

* **TM GamerStats Color-Mod 1080p**  

The **Color-Mod** presets let you transform the overlay’s accent color instantly. Just set a value from **0–100** in the **Color** sensor's Correction formula field and the entire overlay shifts to your chosen hue! — no manual layer editing required. 🪄

To adjust the color:  
1. Open the **Color** sensor in your data source list.  
2. Set a value between **0–100** to define your desired hue across the full RGB spectrum.  

A handy Color Reference Chart is included to guide your inner artist:

<div align="center">
  <img src="https://github.com/TroyMetrics/Benchmark-Overlays/blob/main/assets/images/Color_Reference_Chart.png?raw=true">
</div>  

> 🧙‍♂️ Setting the **Color** sensor to 50 produces a **Cyan** accent color. 

# ❤️ A Note to the Community

If you encounter any issues, or anything that feels off — please open an Issue on GitHub. Screenshots are incredibly helpful and greatly speed up fixes.

Your reports and suggestions directly help these project grow.
Thank you for testing, supporting, and helping improve these overlays for everyone. 🙏

# 🧙‍♂️ More from TroyMetrics

If you enjoy this overlay, check out some other designs:

- [📌 **TroyMetrics Benchmark Overlays**](https://github.com/TroyMetrics/Benchmark-Overlays)

*(This list will continue to expand as more designs are released.)*

🚀 Happy Benchmarking!  
