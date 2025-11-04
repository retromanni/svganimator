# SVG Animator — On-Chain NFT Animation Tool

**Upload PNG frames → Build intros + final loop (Tool 1) or playlist (Tool 2) → Export animated SVG**  
**Fully on-chain. Zero dependencies. Mint-ready.**

[![Live App](https://img.shields.io/badge/Live%20App-Open%20Tool-4CAF50?style=for-the-badge&logo=html5)](https://retromanni.github.io/svganimator/)  
[![GitHub](https://img.shields.io/github/stars/retromanni/svganimator?style=social)](https://github.com/retromanni/svganimator)  
[![Follow @retro_manni](https://img.shields.io/twitter/follow/retro_manni?label=%40retro_manni&style=social)](https://x.com/retro_manni)

---

## Live Tool

**Use it now**: [https://retromanni.github.io/svganimator/](https://retromanni.github.io/svganimator/)

No install. Works offline. Open in any browser.

---

## Features

| Feature | Description |
|--------|-------------|
| **Two Tools** |  
| **Tool 1** | Intros (play once) → **Final infinite loop** (required) |
| **Tool 2** | **Playlist mode** — sequence of sections loops forever |
| **Per-Segment FPS** | Custom FPS per intro, section, or loop |
| **Pixel-Perfect** | `image-rendering: pixelated`, `viewBox`-only scaling |
| **On-Chain Ready** | Single SVG with embedded sprite sheet |
| **Copy SVG** | One-click clipboard copy for instant minting |
| **Responsive Preview** | Full animation preview before export |
| **No Dependencies** | Pure HTML + CSS + JS |

---

## How to Use

1. **Upload** PNG frames (numbered: `1.png`, `2.png`, etc.)
2. **Set Global FPS** (default: 12)
3. **Choose Tool**:
   - **Tool 1**: Add intros → set **final loop** (required)
   - **Tool 2**: Add sections → entire sequence loops
4. **Optional**: Enable **Custom FPS** per segment
5. Click **Generate SVG**
6. **Preview** → **Download** or **Copy SVG**
7. Mint on **[ZeroUnbound.Art](https://zerounbound.art)**

---

## Example: Tool 1

```text
Frames: 1–5 (walk), 6–10 (wave), 11–20 (idle)
→ Intro: 1–5 (walk, 1×, 15 FPS)
→ Intro: 6–10 (wave, 1×, 24 FPS)
→ Final Loop: 11–20 (idle, 12 FPS)
