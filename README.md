# TM-GamerStats-1080p
RTSS / RivaTuner Overlays by TroyMetrics 👻

### 🎥 Video Demo  
▶️ **[Watch the animated multi-color gradient demo on YouTube](https://www.youtube.com/watch?v=Diy7iYxleP8)**

---

## 🌈 Animated Multi-Color Gradient (Experimental Test)

This is an experimental overlay created to test whether a **multi-color animated gradient** can be achieved inside RTSS Overlay Editor,

It turns out: **it’s can** — sort of lol

This repository includes everything needed to download, load, and test the animation directly inside RTSS OverlayEditor.

---

## ⚙️ How It Works

- **A master animation speed controller (`RainbowSpeed`)**
- **A timer sensor (`R1`) that loops 0 → 6000 ms**

As R1 advances through the 6000 ms cycle, each layer activates during its assigned window, fades into the next layer, and creates a continuous rainbow animation.
