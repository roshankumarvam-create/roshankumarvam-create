<h1 align="center">Roshan Kumar</h1>
<p align="center">
  <b>AI / ML Engineer — Biomedical Deep Learning &amp; Full-Stack Product</b><br>
  I take research-grade ML from raw data to shipped, served systems.<br>
  <sub>@ Sudha Gopalakrishnan Brain Centre, IIT Madras</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/roshan-kumar-v-a-m/"><img src="https://img.shields.io/badge/LinkedIn-Roshan%20Kumar-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:roshaniitmsgbc@gmail.com"><img src="https://img.shields.io/badge/Email-roshaniitmsgbc%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Deep%20Learning-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/CV-YOLO%20%7C%20SAM%20%7C%20UNet%20%7C%20DeepLabV3%2B-00897B?style=flat-square">
  <img src="https://img.shields.io/badge/SSL-SimCLR%20%7C%20Contrastive-6A1B9A?style=flat-square">
  <img src="https://img.shields.io/badge/MLOps-MLflow%20%7C%20FastAPI%20%7C%20CUDA-009688?style=flat-square">
  <img src="https://img.shields.io/badge/Product-Next.js%20%7C%20NestJS%20%7C%20Postgres-000000?style=flat-square&logo=nextdotjs&logoColor=white">
</p>

---

### About

I work at the intersection of **biomedical deep learning** and **production software** — and I own the whole path, not a slice of it. On the research side I build whole-slide-image pipelines over **gigapixel human-brain histology**: detection, self-supervised representation learning, segmentation, and morphometric quantification. On the product side I ship **multi-tenant SaaS and real-time desktop AI** that real users depend on.

The thing I'm good at is the **hand-off that usually breaks**: turning a model that works in a notebook into something served, monitored, and trusted by a domain expert. Pre-trained backbones, contrastive SSL, class-imbalanced segmentation, GPU inference services, typed APIs, safe production migrations — I've had to make all of it actually run.

I like **messy, open-ended problems** where the spec isn't written yet, and I learn whatever the problem needs.

> **A note on code:** Several projects below were built under institutional or client IP agreements, so these repos document **architecture, methodology, and measured results** rather than source. Code or a live walkthrough is available on request under NDA.

---

### Selected impact

- **0.717 mIoU** best model in a controlled 3-architecture brain-region segmentation benchmark (Mask2Former · Attention U-Net · DeepLabV3+).
- **0.0352** validation loss segmenting astrocytes with a **SimCLR-pretrained UNet** — beating a MedSAM baseline, trained from detection-derived masks with no manual pixel labels.
- **Gigapixel scale** — pipelines designed for the centre's archive standard of **~10,000 serial sections per brain**.
- **Live production SaaS** — multi-tenant platform carrying real client workloads, hardened against destructive-migration data loss.

---

### Featured Work

| Project | What it does | Stack |
|---|---|---|
| 🧠 **[Astrocyte Detection & Segmentation](./astrocyte-detection-segmentation)** | Detection → self-supervised (SimCLR) → UNet segmentation over gigapixel GFAP histology; served via MLflow + FastAPI | YOLOv5 · SimCLR · UNet · MLflow |
| 🗺️ **[Brain Region Auto-Annotation](./brain-region-auto-annotation)** | 3-model benchmark for whole-section anatomical region segmentation; best **mIoU 0.717** | DeepLabV3+ · Attn-UNet · GeoJSON |
| 🔬 **[Astrocyte Signature Learning](./astrocyte-signature-clustering)** | Unsupervised discovery of astrocyte morphotypes from thousands of cell crops — no labels | SSL · UMAP · clustering |
| 🍽️ **[iBird — Catering SaaS](./ibird-catering-saas)** | Multi-tenant catering / commissary platform serving a live client | Next.js · NestJS · Postgres |
| 🎙️ **[Cuepilot](./cuepilot)** | Real-time desktop assistant: live transcription + AI summaries | Electron · Whisper · OpenAI |

---

### What I bring

**Research / ML** — WSI pipelines · instance & semantic segmentation · self-supervised / contrastive learning · class-imbalance & long-tail handling · curriculum learning · transfer learning · morphometric analysis

**Product / Engineering** — FastAPI & NestJS services · multi-tenant Postgres · GPU inference & MLOps (MLflow, mixed precision) · Next.js/React front-ends · safe production deployment

---

### Reach me

📧 [roshaniitmsgbc@gmail.com](mailto:roshaniitmsgbc@gmail.com) &nbsp;·&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/roshan-kumar-v-a-m/) &nbsp;·&nbsp; 🧠 Sudha Gopalakrishnan Brain Centre, IIT Madras
