<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&pause=1000&color=7AA2F7&center=true&vCenter=true&width=600&lines=Hitarth+Khatiwala;AI%2FML+Engineer+%C2%B7+DL+Researcher;State-Space+Models+%C2%B7+Video+Forensics;Go+Backend+%C2%B7+End-to-End+ML+Systems" alt="Typing SVG"/>

`BTech AI/ML @ CSPIT, CHARUSAT` &nbsp;•&nbsp; `BS Data Science & Applications @ IIT Madras`

<a href="https://www.linkedin.com/in/hitarth-khatiwala-926b69318"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/hitarth1812"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="mailto:hitarthkhatiwala@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://huggingface.co/hitarth1812"><img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/></a>

</div>

---

## About

```yaml
name:      Hitarth Khatiwala
location:  Surat, India
roles:
  - Backend Developer Intern   @ Dezai AI        # Go, Python, FastAPI, AWS
  - AI/ML Research Intern      @ SVNIT           # video deepfake forensics
education:
  - BTech AI/ML                @ CSPIT, CHARUSAT
  - BS Data Science & Apps     @ IIT Madras      # concurrent dual degree
focus:     [state-space models, vision, multimodal forensics, ML systems]
```

I build AI systems end-to-end — dataset design → architecture → training → evaluation → deployment.
Right now: **Mamba-based video forgery detection** at SVNIT and **Go backend infrastructure** at Dezai AI.

---

## Publication

> **Mental Health Analysis using Fine-Tuned BERT-Based Text Classification Model**
> *Lead author* · 5th World Conference on Information Systems for Business Management (**ISBM 2026**), Bangkok
> Selected for proceedings · Publication partner: **Springer Nature**

---

## Current Research & Builds

| Project | What | Stack | Status |
|---|---|---|---|
| **Video Deepfake Detection** | Research (SVNIT) |
| **ATLAS** | Engineering-intelligence backend — staged architecture, JWT + AWS KMS/Secrets Manager, Terraform | `Go` `AWS` `Terraform` | In progress |

---

## Featured Work

<table>
<tr>
<td width="50%" valign="top">

### [X-Ray Pathology Classifier](https://github.com/hitarth1812/X-ray-pathology-classifier)
Multi-label classification across 20 thoracic pathologies (NIH ChestX-ray14).

- EfficientNet-B0 + custom two-layer MLP head
- Two-phase transfer learning (frozen → fine-tune)
- Asymmetric Loss w/ sqrt-scaled positive weights for **6,815×** imbalance
- AMP training on Tesla T4 · GradCAM explainability
- **Val Macro-AUC: 0.8114**

[![HF Space](https://img.shields.io/badge/🤗_Live_Demo-Spaces-FFD21E?style=flat-square)](https://huggingface.co/spaces/hitarth1812/chest-xray-classifier)

`PyTorch` `timm` `Gradio`

</td>
<td width="50%" valign="top">

### Plant Super-Resolution GAN
ESRGAN-style SR model built for a competition.

- RRDB generator (16–23 blocks) + PatchGAN discriminator
- VGG perceptual loss · tuned adversarial weight (λ=0.001)
- Multi-phase training: warmup → GAN → fine-tune
- Cosine LR schedule · 8-fold TTA

`PyTorch` `GANs`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Arka Energy Nexus](https://github.com/hitarth1812/arka-energy-nexus)
Full-stack energy auditing & ESG intelligence platform.

- Django REST backend · React + Vite + Tailwind
- AI-powered parser for pivot-format Excel audit data
- Carbon calculator on India grid factor (0.82 kg CO₂/kWh)
- Automated ESG PDF reports via ReportLab
- 3D globe dashboard · Framer Motion UI

`Django` `React` `pandas`

</td>
<td width="50%" valign="top">

### [Crack Detection](https://github.com/hitarth1812/Crack-Detection)
Structural defect classification for infrastructure inspection.

- EfficientNet-B0 transfer learning
- **99.72% test accuracy**
- GradCAM heatmaps for defect localization

`PyTorch` `OpenCV`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### [Comment Category Prediction](https://github.com/hitarth1812)
Multi-class NLP pipeline — transformer-based classification with class-weighted training on imbalanced labels · **Macro F1 ≈ 0.62** · `Transformers` `scikit-learn`

</td>
</tr>
</table>

---

## Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**ML / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square&logo=gradio&logoColor=white)

**Backend, Cloud & Web**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

</div>

---

## GitHub Activity

<div align="center">

<img src="https://streak-stats.demolab.com/?user=hitarth1812&hide_border=true&theme=tokyonight" alt="GitHub streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=hitarth1812&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph" width="95%"/>

</div>

---

<div align="center">

**Open to:** research collaborations · ML engineering internships · state-space / forensics discussions

*Build things that matter.*

<img src="https://komarev.com/ghpvc/?username=hitarth1812&color=blueviolet&style=flat-square" alt="Profile views"/>

</div>
