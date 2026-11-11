<div align="center">

<!-- DYNAMIC HEADER -->
<a href="https://github.com/hitarth1812">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=3200&pause=900&color=7AA2F7&center=true&vCenter=true&width=750&lines=Hitarth+Khatiwala;AI%2FML+Engineer+%C2%B7+Deep+Learning+Researcher;State-Space+Models+(Mamba)+%C2%B7+Video+Forensics;Go+Backend+Architecture+%C2%B7+End-to-End+ML+Systems" alt="Typing SVG" />
</a>

**`BTech AI/ML @ CSPIT, CHARUSAT`** &nbsp;•&nbsp; **`BS Data Science & Applications @ IIT Madras`**

<br/>

<!-- SOCIAL & PROFILE LINKS -->
<p align="center">
  <a href="https://www.linkedin.com/in/hitarth-khatiwala-926b69318">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/hitarth1812">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://huggingface.co/hitarth1812">
    <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="HuggingFace" />
  </a>
  <a href="mailto:hitarthkhatiwala@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=hitarth1812&label=Profile%20Views&color=7aa2f7&style=for-the-badge" alt="Profile Views" />
</p>

</div>

---

## ⚡ System Architecture (`whoami.yaml`)

```yaml
engineer:
  name: "Hitarth Khatiwala"
  location: "Surat, Gujarat, India"
  philosophy: "Dataset Design → Architecture → Training → Evaluation → Production"

active_roles:
  - role: "Backend Developer Intern"
    org: "Dezai AI"
    stack: ["Go", "Python", "FastAPI", "AWS", "Terraform"]
  - role: "AI/ML Research Intern"
    org: "SVNIT"
    domain: "Mamba-based Video Deepfake & Manipulation Forensics"

education:
  - degree: "BTech in AI & Machine Learning"
    institute: "CSPIT, CHARUSAT"
  - degree: "BS in Data Science & Applications (Concurrent Dual Degree)"
    institute: "IIT Madras"

research_interests:
  - "State-Space Models (Mamba / Vision Mamba)"
  - "Multimodal & Spatio-Temporal Video Forensics"
  - "High-Throughput Backend & ML Inference Systems"
```

---

## 📄 Selected Publication

<table>
  <tr>
    <td>
      <b>Mental Health Analysis using Fine-Tuned BERT-Based Text Classification Model</b><br/>
      <i>Lead Author</i> &nbsp;·&nbsp; 5th World Conference on Information Systems for Business Management (<b>ISBM 2026</b>), Bangkok<br/>
      <img src="https://img.shields.io/badge/Status-Accepted%20for%20Proceedings-2ea44f?style=flat-square" />
      <img src="https://img.shields.io/badge/Publisher-Springer%20Nature-00599C?style=flat-square" />
      <img src="https://img.shields.io/badge/Domain-Clinical%20NLP%20%26%20Transformers-7AA2F7?style=flat-square" />
    </td>
  </tr>
</table>

---

## 🔬 Active Research & Systems in Flight

| Initiative | Focus & Architecture | Core Stack | Status |
| :--- | :--- | :--- | :--- |
| **Video Deepfake Forensics** *(SVNIT)* | Spatio-temporal forgery detection leveraging **State-Space Models (Mamba)** to capture long-range temporal inconsistencies across compressed video streams. | `PyTorch` `Mamba` `OpenCV` `CUDA` | 🟢 Active Research |
| **ATLAS** *(Dezai AI)* | Engineering-intelligence backend built on a staged microservice architecture with custom JWT auth, cryptographic key management via AWS KMS/Secrets Manager, and IaC provisioning. | `Go` `AWS KMS` `Terraform` `PostgreSQL` | 🟡 In Progress |

---

## 🚀 Featured Engineering & Research Work

<table>
<tr>
<td width="50%" valign="top">

### 🩻 [X-Ray Pathology Classifier](https://github.com/hitarth1812/X-ray-pathology-classifier)
**Multi-label thoracic disease diagnosis across 20 pathologies (NIH ChestX-ray14).**
- **Architecture:** `EfficientNet-B0` backbone with custom 2-layer MLP classification head.
- **Training Strategy:** Two-phase transfer learning (frozen head warmup → full unfreeze) with mixed precision (`AMP`) on Tesla T4.
- **Imbalance Handling:** Custom Asymmetric Loss with $\sqrt{\text{pos\_weight}}$ scaling to combat a **6,815×** class imbalance.
- **Impact:** Achieved **0.8114 Validation Macro-AUC** with integrated **GradCAM** clinical explainability.

<p>
  <a href="https://huggingface.co/spaces/hitarth1812/chest-xray-classifier"><img src="https://img.shields.io/badge/🤗_Live_Space-FFD21E?style=flat-square&logoColor=black" alt="HF Space"/></a>
  <a href="https://github.com/hitarth1812/X-ray-pathology-classifier"><img src="https://img.shields.io/badge/Code-PyTorch%20%7C%20timm%20%7C%20Gradio-181717?style=flat-square&logo=github" alt="Repo"/></a>
</p>

</td>
<td width="50%" valign="top">

### 🛡️ [AI-Gate](https://github.com/hitarth1812/ai-gate)
**High-performance static analysis & real-time code review engine for developers and AI coding agents.**
- **Core Engine:** Lightweight, zero-bloat single-file architecture delivering **sub-second feedback** loops across `Python`, `Go`, and `JavaScript`.
- **Security & Quality Gates:** Automated secret detection, dependency vulnerability auditing, and structural AST/lint verification before code hits production.
- **Agentic & CI/CD Integration:** Built as a cost-optimized deterministic guardrail for autonomous AI coding agents and automated pull-request pipelines.

<p>
  <a href="https://github.com/hitarth1812/ai-gate"><img src="https://img.shields.io/badge/Code-Python%20%7C%20Go%20%7C%20CI%2FCD-181717?style=flat-square&logo=github" alt="Repo"/></a>
</p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌿 [Plant Super-Resolution GAN](https://github.com/hitarth1812/Plants_Super_Resolution)
**ESRGAN-inspired perceptual super-resolution pipeline built for fine-grained botanical recovery.**
- **Architecture:** Residual-in-Residual Dense Block (**RRDB**, 16–23 blocks) generator paired with a multiscale **PatchGAN** discriminator.
- **Optimization:** Composite loss blending pixel L1, VGG-19 perceptual features, and tuned adversarial loss ($\lambda = 0.001$).
- **Inference:** Multi-stage curriculum (PSNR warmup → GAN fine-tune) with cosine annealing and **8-fold Test-Time Augmentation (TTA)**.

<p>
  <a href="https://github.com/hitarth1812/Plants_Super_Resolution"><img src="https://img.shields.io/badge/Code-PyTorch%20%7C%20ESRGAN%20%7C%20CV-181717?style=flat-square&logo=github" alt="Repo"/></a>
</p>

</td>
<td width="50%" valign="top">

### ⚡ [Arka Energy Nexus](https://github.com/hitarth1812/arka-energy-nexus)
**Full-stack enterprise energy auditing & automated ESG intelligence platform.**
- **Ingestion Engine:** AI-assisted parser transforming unstructured, pivot-heavy Excel utility audits into normalized relational schemas.
- **Domain Modeling:** Automated Scope-2 carbon accounting calibrated to the Indian grid emission factor (**0.82 kg CO₂/kWh**).
- **Deliverables:** Interactive 3D WebGL globe telemetry dashboard + automated board-ready ESG PDF synthesis via `ReportLab`.

<p>
  <a href="https://github.com/hitarth1812/arka-energy-nexus"><img src="https://img.shields.io/badge/Code-Django%20DRF%20%7C%20React%20%7C%20Pandas-181717?style=flat-square&logo=github" alt="Repo"/></a>
</p>

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 💬 [Imbalanced Comment Category Prediction](https://github.com/hitarth1812)
End-to-end multi-class transformer classification pipeline engineered for heavily skewed user-generated text distributions. Combines inverse-frequency class-weighted cross-entropy, dynamic tokenization padding, and stratified folds to reach **Macro F1 ≈ 0.62** · `HuggingFace Transformers` `PyTorch` `scikit-learn`

</td>
</tr>
</table>

---

## 🛠️ Technical Arsenal

<div align="center">

| Domain | Technologies & Tools |
| :--- | :--- |
| **Core Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Deep Learning & AI** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Transformers](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square&logo=gradio&logoColor=white) |
| **Backend & Cloud Infra** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) |
| **Research & DevOps** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white) ![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) |

</div>

---

## 📈 GitHub Telemetry

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=hitarth1812&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats" />
  <img height="165em" src="https://streak-stats.demolab.com/?user=hitarth1812&hide_border=true&theme=tokyonight" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=hitarth1812&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Velocity" width="96%" alt="Contribution Graph" />
</div>

---

<div align="center">

**Open to:** Deep Learning Research Collaborations · Applied ML / Backend Internships · State-Space & Forensics Discussions

*“Architect systems that scale. Train models that generalize.”*

</div>
