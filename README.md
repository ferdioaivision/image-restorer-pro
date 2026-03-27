# Image Restorer Pro Desktop v2.0

**Powerful single-file forensic image recovery tool — runs entirely in your browser.**

![Interface Preview](https://via.placeholder.com/800x450/0a1428/00e5ff?text=Image+Restorer+Pro+v2.0)

## ✨ Overview

Image Restorer Pro is a professional desktop-style tool developed by **FERDIO AI VISION** for restoring visually corrupted images and performing deep digital forensic analysis.

It works directly on raw pixel data, allowing you to reverse mathematical corruptions that standard image editors cannot fix (wrong width, channel swaps, XOR obfuscation, interleaved data, etc.).

**Version 2.0** brings major upgrades:
- Full **Forensics Pro** suite
- Advanced scientific filters
- PNG chunk & Alpha analysis
- Claude AI Assistant integration

## 🚀 Key Features

### Core Correction Modules (15 Modes)
- **Width Correction** — Manual or Auto-Scan (100 to 2000 px) with quality ranking
- **Flip & Rotation** — H/V/Both + 90°/180°/270° + "Try All" (6 variants)
- **Channel Permutation** — All 6 RGB orders + "Try All"
- **Value Transforms** — Invert, Shift (+N), XOR, Gamma, Deinterleave/Re-interleave + full scans
- **Block Reordering** — Reverse rows/cols, deinterleave, byte swap, raw offset scan (±100 px)
- **Auto-Detect** — Runs dozens of corrections automatically and ranks by quality score

### Visual & Scientific Filters (v2.0 New)
**Basic:** Contrast, Brightness, Sharpen, Denoise, Grayscale, Equalize, Median, Bilateral, Wiener  
**Advanced:** Wavelet denoising, Anisotropic diffusion (Perona-Malik), Inpainting, CLAHE, FFT Filter, Anomaly Fix

### Forensics Pro Toolkit (v2.0 New)
- **LSB Extractor** — Hidden data extraction (any channel/bit plane, text/binary/hex)
- **Magic Bytes Inspector** — Detects real file format signatures
- **Hex Viewer** — Raw byte inspection with pattern search
- **Bit Plane Visualizer** — All 8 bit planes per channel + luminance
- **Chi² Attack** — Statistical steganalysis
- **Histogram Visualizer** — Per-channel distribution analysis
- **PNG Chunk Parser** — Extracts hidden text from tEXt/zTXt chunks
- **Alpha Channel Extractor** — Reveals data hidden in transparency
- **EXIF Metadata Reader** — Full camera, GPS, comments extraction
- **Image Diff** — Pixel-by-pixel comparison (5 modes)
- **Hash Calculator + Audit Log** — CRC32, SHA-1/256/512 + full operation history

### AI Assistant
Integrated **Claude AI** (Anthropic) for intelligent diagnosis and restoration suggestions.  
Requires your own API key (saved locally in browser only).

### Other Tools
- Chain Transforms (combine multiple corrections)
- Quality Analysis (Smoothness, Variance, Edges, Score)
- Entropy Analysis per channel + automatic corruption diagnosis
- Visual History with thumbnails
- Undo stack + "Use as Input" for multi-pass work
- Export as PNG / JPG / WebP

## 🛠 How to Use

1. Open `index.html` in any modern browser (Chrome/Firefox/Edge recommended)
2. Drag & drop your corrupted image
3. Use the left panel for corrections or click **Auto-Detect**
4. Preview result on the right
5. Export when satisfied

**Everything runs locally** — your images never leave your computer.

## 📊 Technical Details
- Pure HTML5 + CSS3 + Vanilla JavaScript
- Canvas API for real-time pixel manipulation
- No external dependencies
- Bilingual interface (English / French)
- Single self-contained HTML file

## 📸 Screenshots
![interface_demo_v1](https://github.com/user-attachments/assets/f01dfa0e-aa5c-481f-9961-4c56f708af5e)
![demo](https://github.com/user-attachments/assets/91f2a866-5a5a-47ec-baea-146cc020e162)

---

**Developed with ❤️ by FERDIO AI VISION**  
For CTF players, digital forensic analysts, and anyone recovering corrupted or suspicious images.

Star ⭐ this repository if you find it useful!
