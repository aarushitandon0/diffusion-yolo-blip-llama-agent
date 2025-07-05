 
A full-stack Vision-Language AI pipeline that simulates realistic human activity scenes using Stable Diffusion, labels them with YOLOv8, captions them with BLIP, and reasons about them with LLaMA-3.  
Built entirely using synthetic data for ethical, flexible, and scalable scene understanding.

> No real-world data.  
> No manual annotation.  
> Fully AI-generated, AI-labeled, and AI-reasoned.


## Overview

This project builds a synthetic Vision-Language dataset and uses it to power an agent capable of understanding and reasoning about suspicious or benign scenes using only AI-generated content.

### Goal:
> Generate synthetic images → Detect objects → Caption scenes → Reason using LLMs

## 🧠 Architecture Summary

| Phase | Task | Tool Used |
|-------|------|-----------|
| 1️ | Image generation | `Stable Diffusion v1.5` |
| 2️ | Image captioning | `BLIP` |
| 3️ | Object detection | `YOLOv8n` |
| 4️ | Scene reasoning | `LLaMA-3 8B Instruct` via `Together.ai` API |
