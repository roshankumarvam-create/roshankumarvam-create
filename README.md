<h1 align="center">Roshan Kumar</h1>
<p align="center">
  <b>AI / ML Engineer, Applied Deep Learning and Full-Stack Product</b><br>
  I take research-grade ML from raw data to shipped, served systems.<br>
  <sub>@ Sudha Gopalakrishnan Brain Centre, IIT Madras</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/roshan-kumar-v-a-m/"><img src="https://img.shields.io/badge/LinkedIn-Roshan%20Kumar-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:roshaniitmsgbc@gmail.com"><img src="https://img.shields.io/badge/Email-roshaniitmsgbc%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Deep%20Learning-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/CV-YOLO%20%7C%20UNet%20%7C%20DeepLabV3%2B-00897B?style=flat-square">
  <img src="https://img.shields.io/badge/SSL-SimCLR%20%7C%20Contrastive-6A1B9A?style=flat-square">
  <img src="https://img.shields.io/badge/MLOps-MLflow%20%7C%20FastAPI%20%7C%20CUDA-009688?style=flat-square">
  <img src="https://img.shields.io/badge/Product-Next.js%20%7C%20NestJS%20%7C%20Postgres-000000?style=flat-square&logo=nextdotjs&logoColor=white">
</p>

### About

I work at the intersection of applied deep learning and production software, and I own the whole path rather than a slice of it. On the research side I build pipelines over gigapixel medical and biological imaging: detection, self-supervised representation learning, segmentation, and quantification. On the product side I ship multi-tenant SaaS and real-time desktop applications that real users depend on.

What I am good at is the hand-off that usually breaks: turning a model that works in a notebook into something served, monitored, and trusted by a domain expert. Pre-trained backbones, contrastive self-supervised learning, class-imbalanced segmentation, GPU inference services, typed APIs, and safe production migrations. I have had to make all of it actually run.

I like messy, open-ended problems where the spec is not written yet, and I learn whatever the problem needs.

> A note on code: several of these projects were built under institutional or client agreements. The repos document the architecture, methods, and measured results, and the source stays private. Code or a live walkthrough is available on request under NDA.

### Selected impact

- Best model at 0.717 mIoU in a controlled three-architecture region-segmentation benchmark (Mask2Former, Attention U-Net, DeepLabV3+).
- 0.0352 validation loss segmenting cells with a SimCLR-pretrained UNet, beating a MedSAM baseline, trained from detection-derived masks with no manual pixel labels.
- Gigapixel scale, pipelines designed for an archive standard of roughly 10,000 serial sections per specimen.
- Live production SaaS, a multi-tenant platform carrying real client workloads, hardened against destructive-migration data loss.

### Featured work

| Project | What it does | Stack |
|---|---|---|
| [Self-Supervised Cell Segmentation](https://github.com/roshankumarvam-create/self-supervised-cell-segmentation) | Detection, then self-supervised SimCLR, then UNet segmentation over gigapixel medical images, served via MLflow and FastAPI | YOLOv5, SimCLR, UNet, MLflow |
| [Medical-Image Region Segmentation](https://github.com/roshankumarvam-create/medical-image-region-segmentation) | Three-model benchmark for whole-section anatomical region segmentation, best mIoU 0.717 | DeepLabV3+, Attn-UNet, GeoJSON |
| [Unsupervised Cell Phenotyping](https://github.com/roshankumarvam-create/unsupervised-cell-phenotyping) | Label-free discovery of cell phenotypes from thousands of cells, mapped to a spatial atlas | SSL, UMAP, clustering |
| [Multi-Tenant B2B SaaS Architecture](https://github.com/roshankumarvam-create/multi-tenant-saas-architecture) | Production multi-tenant SaaS system design: tenant isolation, async pipelines, billing, observability, with diagrams and ADRs | NestJS, Next.js, Postgres |
| [Cuepilot](https://github.com/roshankumarvam-create/cuepilot) | Real-time desktop assistant, live transcription and AI summaries | Electron, Whisper, OpenAI |

### What I bring

Research and ML: WSI pipelines, instance and semantic segmentation, self-supervised and contrastive learning, class-imbalance and long-tail handling, curriculum learning, transfer learning, morphometric analysis.

Product and engineering: FastAPI and NestJS services, multi-tenant Postgres, GPU inference and MLOps (MLflow, mixed precision), Next.js and React front-ends, safe production deployment.

### Reach me

[roshaniitmsgbc@gmail.com](mailto:roshaniitmsgbc@gmail.com), [LinkedIn](https://www.linkedin.com/in/roshan-kumar-v-a-m/), Sudha Gopalakrishnan Brain Centre, IIT Madras
