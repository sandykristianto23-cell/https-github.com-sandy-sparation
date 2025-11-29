# sparation — Automatic Color Separation App (FastAPI + SAM + rembg Fallback)

A lightweight and production-ready **Automatic Color Separation Web App** built with:

- **FastAPI backend**
- **Segment-Anything (SAM) CPU-optimized**
- **Automatic fallback to rembg**
- **Tailwind UI**
- **Multi-swatch color picker**
- **Color tolerance control**
- **Live preview**
- **Dockerfile (CPU only)**
- **GitHub Actions (auto build to Docker Hub)**

This project is ideal for:
- Print shops (sablon)
- T-shirt separation workflow
- AI-based color extraction
- Automated image masking
- Photo editing automation

---

## ✨ Features

### ✅ SAM segmentation (CPU-optimized)  
Runs on CPU-only using `segment-anything` + ONNX runtime.

### ✅ Automatic fallback to rembg  
If SAM fails or is not installed, system switches automatically to rembg.

### ✅ Multi-swatch color picker  
Pick multiple colors from image using visual palette UI.

### ✅ Color Tolerance (range)  
Controls how wide the color extraction range is.

### ✅ Live Preview  
Shows results instantly before exporting.

### ✅ Batch Mode  
Upload multiple images at once — backend processes them sequentially.

### ✅ Docker-ready  
CPU Dockerfile included.

### ✅ GitHub Actions → Docker Hub  
Auto-build pushes images on commits.

---

## 📦 Installation

### 1. Clone repository

```bash
git clone https://github.com/<yourname>/sparation
cd sparation
