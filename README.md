<h1 align="center">Hitarth Khatiwala</h1>

<p align="center">
  <b>AI/ML undergraduate working on deep learning research and developer tooling</b><br/>
  BTech AI &amp; ML, CSPIT (CHARUSAT) &nbsp;·&nbsp; BS Data Science &amp; Applications, IIT Madras &nbsp;·&nbsp; Surat, India
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/hitarth-khatiwala"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://huggingface.co/hitarth1812"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/></a>
  <a href="mailto:hitarthkhatiwala@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## About

- **Research:** video deepfake-forgery detection with state-space models (Mamba), medical imaging, and NLP.
- **Engineering:** static-analysis tooling for AI-written code, and backend services.
- **Currently:** preparing a manuscript from my SVNIT research internship, building [AI-Gate](https://github.com/hitarth1812/AI-Gate), and working on ATLAS.
- **Open to:** research collaborations and applied ML / backend internships.

## Experience

| Role | Organisation | Period | Work |
| :-- | :-- | :-- | :-- |
| AI/ML Research Intern, Image Forensics | SVNIT, Surat | May – Jul 2026 | Mamba-based spatio-temporal model for video deepfake-forgery detection; leakage-free, identity-disjoint evaluation protocol with baselines, ablations, and cross-dataset testing. Manuscript in preparation. |
| Backend Developer Intern | [Dezai AI](https://dezai.org) | Jun – Oct 2026 | Production backend features (Next.js, Node.js) for RBAC, file uploads, and audit logging; 40+ QA test cases and validation reports. |
| UGSF Scholar, PDPIAS | CHARUSAT | 2026 – Present | Built the ICCS-CIRCLE 2027 conference website (HTML/CSS/JS, Node.js/Express, Google Sheets backend); configured Microsoft CMT for submission and double-blind review. |

## Publications & Patents

- **Mental Health Analysis using Fine Tuned BERT Based Text Classification Model**
  H. Khatiwala, P. Jotania, M. Joshi, M. Patel, H. Jayswal, et al. — *5th World Conference on Information Systems for Business Management (ISBM 2026), Bangkok, Thailand.* First author. Presented and selected for the Springer Nature proceedings.
  Fine-tuned BERT on three combined mental-health corpora, reaching up to 98.2% accuracy on Twitter data.

- **Modular Augmented Reality Drone Pilot Assistance System with 3D UAV Visualization and Non-Invasive Overlay Rendering**
  M. J. Panchal, K. K. Singh, H. Khatiwala, et al. — Indian Patent Application No. 202621082775 A, published in The Patent Office Journal No. 39/2026 (applicant: CHARUSAT).

## Projects

### [AI-Gate (aigate-lite)](https://github.com/hitarth1812/AI-Gate) — commit gate for AI-written code
`Python` `Git hooks` `CI` `PyPI`

- Zero-dependency git-hook CLI that blocks hallucinated packages, weakened tests, and leaked secrets before they are committed.
- AST/lexer analysis for Python, Go, and JS/TS, verified by 1,000+ tests on cross-platform CI.

```bash
pip install aigate-lite
```

### [Multi-Label Chest X-Ray Classification](https://github.com/hitarth1812/X-ray-pathology-classifier)
`PyTorch` `EfficientNet-B0` `Grad-CAM` `Gradio`

- EfficientNet-B0 trained on 20 thoracic classes (51K images) with Asymmetric Loss to handle a 6,815× class imbalance.
- 0.8114 validation macro-AUC; Grad-CAM explanations in a [live demo on Hugging Face Spaces](https://huggingface.co/spaces/hitarth1812/chest-xray-classifier).
- Research and educational use only; not a diagnostic tool.

### [Smart MCQ Solver](https://github.com/hitarth1812/24f2001535-dl-genai-project)
`PyTorch` `Transformers` `LoRA` `W&B`

- From-scratch Transformer, BERT + LoRA, and DeBERTa-v3 + LoRA for ranked MCQ prediction (IIT Madras course competition).
- Ensembled with Nelder-Mead weighting and a stacker: 0.8012 offline MAP@3, 0.748 on the Kaggle leaderboard.

### [Plant Leaf Image Enhancement GAN](https://github.com/hitarth1812/Plants_Super_Resolution)
`PyTorch` `ESRGAN` `PatchGAN` `AMP`

- 4× ESRGAN-style GAN with a 16-block RRDB generator, PatchGAN discriminator, and VGG19 perceptual loss.
- Phased training (pixel warm-up, then adversarial) with a tuned adversarial weight, cosine LR schedule, and 8-fold TTA.

### ATLAS — engineering-intelligence platform (in development)
`Go` `PostgreSQL` `AWS KMS` `Secrets Manager` `Terraform` `Docker`

- Co-founded project. Go backend built in stages with constructor injection and a standard-library-first approach.
- JWT issuance with signing keys held in AWS KMS / Secrets Manager; infrastructure defined in Terraform.

### More

| Project | Summary | Stack |
| :-- | :-- | :-- |
| [Arka Energy Nexus](https://github.com/hitarth1812/arka-energy-nexus) | Energy-audit and ESG reporting app: parses utility spreadsheets, computes Scope-2 emissions (CEA grid factor 0.82 kg CO₂/kWh), exports PDF reports. | Django REST, React, Pandas |
| [Crack Detection](https://github.com/hitarth1812/Crack-Detection) | Concrete crack classification with Grad-CAM localisation; 99.72% test accuracy. | PyTorch, EfficientNet-B0 |

## Skills

| Area | Tools |
| :-- | :-- |
| Languages | Python, C, C++, SQL, JavaScript, TypeScript, Go |
| ML & DL | PyTorch, Hugging Face Transformers, LoRA, scikit-learn, Mamba/SSMs, GANs, transfer learning, Grad-CAM |
| Backend & Cloud | Node.js, Express, FastAPI, Django REST, PostgreSQL, Docker, AWS, Terraform |
| Tools | Git, GitHub Actions, Weights & Biases, Gradio, Hugging Face Spaces, Kaggle |

## Achievements

- Class topper in first year, AIML department, CSPIT.
- Winner, college hackathon "AI Bot Roast & Repair" (2026), as team lead.
- National finalist, IIT Gandhinagar Codeversity (2026), selected from 500+ teams.
- Shortlisted team leader representing IIT Madras BS at Smart India Hackathon.
- NPTEL Elite (DBMS); NVIDIA: AI Deployment on Edge Devices (Jetson Nano).

---

<p align="center">
  <a href="mailto:hitarthkhatiwala@gmail.com">hitarthkhatiwala@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/hitarth-khatiwala">LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://huggingface.co/hitarth1812">Hugging Face</a>
</p>
