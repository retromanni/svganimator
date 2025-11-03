# PNG to Animated SVG (NFT Animator)

A **zero-dependency**, **offline-first** web tool that converts **PNG frame sequences** into a **single animated SVG** — perfect for **NFTs**, **pixel art**, and **web animations**.

---

## Features

- **Drag & drop** PNG frames (or click to upload)
- **Unlimited intros** with:
  - Custom frame range
  - **Up to 50 repeats** per intro
  - Enable/disable per intro
  - Remove any intro
- **Loop section** (repeats forever)
- **Pixel-perfect rendering** (`image-rendering: pixelated`)
- **Live preview** before download
- **Single SVG file output** (NFT-ready, no external assets)
- **100% client-side** — no server, no install

---

## How to Use

1. **Prepare your PNGs**  
   - All same size (e.g., 64x64)
   - Name sequentially: `frame1.png`, `frame2.png`, ..., `frame10.png`

2. **Open `index.html` in any browser**

3. **Drag & drop** your PNGs

4. Click **"+ Add Intro"** as many times as needed

5. For each intro:
   - Set frame range
   - Adjust repeat count (1–50)
   - Toggle on/off

6. Set **Loop range** (last section, loops forever)

7. Click **Generate SVG**

8. Preview → Click **Download SVG**

9. Upload to **OpenSea**, **Rarible**, or embed on your site!

---

## Example Use Case

> **Like an animated GIF:**  
> A man walks into a room, sits down, and takes **3 sips of coffee** → picks up a newspaper → **flicks through pages in an infinite loop**.  
> *Refresh the page to restart the full animation.*

### How to set it up:
```text
Intro 1: frames 1–5   → Walk in & sit (1×)
Intro 2: frames 6–8   → Sip coffee (3×)
Intro 3: frames 9–12  → Pick up newspaper (1×)
Loop:    frames 13–18 → Page flip (forever)
