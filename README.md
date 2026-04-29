<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Basmala%20Pasmala&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Applied%20AI%20Engineer%20%7C%20Building%20Real%20Systems%20with%20Real%20Models&descAlignY=60&descColor=94a3b8" />

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](www.linkedin.com/in/basmala-hesham-86099a1a8)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail)](mailto:basmala.hesham2004@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=pasmala2004&color=2c5364&style=flat-square)

</div>

---

## `$ whoami`

```python
engineer = {
    "name"        : "Basmala",
    "role"        : "Applied AI / ML Engineer",
    "location"    : "Egypt",
    "current"     : "Building Etbaly — AI-powered 3D printing platform (prod deployment on GPU)",
    "stack"       : ["PyTorch", "Diffusers", "Flask", "trimesh", "Lightning.ai"],
    "seeking"     : "Junior ML Engineer | AI Engineer | Data roles in Egypt & Remote",
    "superpower"  : "Taking a research model from HuggingFace → production API in <48h"
}
```

> I build AI systems that go beyond notebooks — deployed APIs, GPU-served models, real pipelines.

---

## 🚀 Flagship Project — Etbaly AI Platform

> **The problem:** Making 3D printing accessible requires translating creative ideas (text or images) into print-ready files — a process that was entirely manual.
> **The solution:** An end-to-end AI platform that takes a description or photo and returns a validated, sliced, print-ready STL file.

```
┌─────────────────────────────────────────────────────────────────┐
│                     ETBALY SYSTEM ARCHITECTURE                  │
├──────────────┬──────────────────────────────┬───────────────────┤
│  INPUT LAYER │      AI INFERENCE LAYER       │   OUTPUT LAYER    │
├──────────────┼──────────────────────────────┼───────────────────┤
│  Text Prompt │──▶ HunyuanDiT (T2I)          │                   │
│              │    Text → Image generation   │  STL Validation   │
│              │         │                    │  Printability     │
│              │         ▼                    │  Check            │
│  Image Input │──▶ Hunyuan3D-2mini           │         │         │
│              │    Image → 3D Mesh           │         ▼         │
│              │         │                    │  3-Profile Slicer │
│              │         ▼                    │  (fine/standard/  │
│              │    Flask REST API            │   draft quality)  │
│              │    (GPU-served, T4)          │         │         │
│              │                              │         ▼         │
│              │    Lightning.ai Hosting      │  Print-Ready File │
└──────────────┴──────────────────────────────┴───────────────────┘
```

| Component | Tech | What I built |
|-----------|------|--------------|
| **3D Generation** | Hunyuan3D-2mini (Tencent) | Image → mesh pipeline with trimesh post-processing |
| **Image Generation** | HunyuanDiT | Text-to-image as preprocessing stage |
| **API Layer** | Flask REST | GPU-aware endpoints with model loading/unloading |
| **Validation** | trimesh + custom logic | STL printability checks, manifold repair |
| **Slicer** | Custom Python | 3-profile slicer (fine / standard / draft) |
| **Deployment** | Lightning.ai T4 GPU | Free-tier GPU serving with persistent model cache |

**Engineering challenges solved:** Cold-start latency on T4, VRAM management across two large models, handling non-manifold mesh outputs from generation model, slicer profile calibration for consumer printers.

**Repos:** [`etbaly-ai-backend`](https://github.com/pasmala2004) · [`etbaly-model-integration`](https://github.com/pasmala2004) · [`etbaly-3d-printing`](https://github.com/pasmala2004)

---

## 📂 Featured Projects

| Project | Description | Stack | Key Metric |
|---------|-------------|-------|------------|
| 🏭 **[Etbaly AI Platform](https://github.com/pasmala2004)** | End-to-end AI pipeline: text/image → validated 3D printable STL | PyTorch · Flask · Hunyuan · Lightning.ai | GPU-deployed, 2 models in production |
| 🎬 **[Movie Revenue Predictor](https://github.com/pasmala2004/movie-revenue)** | ML model predicting box office revenue from pre-release features | Scikit-learn · Pandas · Feature Engineering | Regression pipeline with EDA |
| 📊 **[Sales Analytics Dashboard](https://github.com/pasmala2004/sales-analysis-project)** | End-to-end sales pipeline analysis with business insight extraction | Python · Seaborn · Matplotlib · SQL | Actionable business findings from raw data |

---

## 🛠 Technical Skills

**Machine Learning & AI**
`PyTorch` `Scikit-learn` `Diffusers` `Transformers (HuggingFace)` `Computer Vision` `Regression` `Classification` `Feature Engineering`

**Deep Learning & Generative AI**
`Text-to-Image` `Image-to-3D` `Diffusion Models` `Hunyuan3D` `HunyuanDiT` `Model Fine-tuning`

**MLOps & Deployment**
`Flask REST APIs` `GPU Serving` `Lightning.ai` `Model Optimization` `VRAM Management` `Containerization (learning)`

**Data Science & Analytics**
`Pandas` `NumPy` `EDA` `Statistical Analysis` `Hypothesis Testing` `SQL`

**Visualization & BI**
`Matplotlib` `Seaborn` `Power BI` `Tableau` `Excel`

**Programming & Tools**
`Python` `SQL` `Git` `GitHub` `OOP` `Algorithms & Data Structures`

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=pasmala2004&show_icons=true&theme=dark&bg_color=0f2027&border_color=2c5364&title_color=94a3b8&text_color=cbd5e1&icon_color=38bdf8&hide_border=false&count_private=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pasmala2004&layout=compact&theme=dark&bg_color=0f2027&border_color=2c5364&title_color=94a3b8&text_color=cbd5e1&hide_border=false&langs_count=6" />

</div>

---

## 🌱 Currently

- 🔧 Shipping Etbaly's production API (v1 milestone)
- 📚 Deepening: MLOps fundamentals, Docker, model quantization
- 🧪 Building: NLP project to add to portfolio (intent classification / RAG)
- 📝 Writing technical notes on Hunyuan3D integration (blog coming soon)

---

## 💬 Let's connect

I'm actively looking for **junior ML / Applied AI roles in Egypt and remote opportunities**. If you're building something with AI and need an engineer who can take a model from HuggingFace to a working API — let's talk.

📬 **[basmala.hesham2004@gmail.com](mailto:basmala.hesham2004@gmail.com)** · [LinkedIn](www.linkedin.com/in/basmala-hesham-86099a1a8)

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" />
</div>
