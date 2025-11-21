<h1 align="center">TroyMetrics GamerStats 1080p</h1>
<p align="center">RTSS / RivaTuner Overlays by TroyMetrics 👻</p>

<p align="center">
  <img src="https://github.com/TroyMetrics/TM-GamerStats-1080p/blob/main/assets/Preview.png?raw=true" alt="Preview">
</p>

### 🎥 Video Demo  
▶️ **[Watch the Animated Multi-Color Gradient Demo on YouTube](https://www.youtube.com/watch?v=Diy7iYxleP8)**

---

## 🌈 Animated Multi-Color Gradient (Experimental)

This update introduces a fun experiment: a fully **multi-color animated gradient** running natively inside RTSS OverlayEditor — something most people assume *can’t* be done.

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

---

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
