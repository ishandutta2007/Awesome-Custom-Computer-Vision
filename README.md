# Awesome-Custom-Computer-Vision

# Awesome-Custom-Computer-Vision

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Custom Model Training, AutoML, Edge Deployment & Annotation Workflows*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Custom Computer Vision**. These tools help developers and businesses train custom object detection, classification, and segmentation models on their own image datasets—without requiring deep ML expertise.

**Examples** include Microsoft Custom Vision, Google Cloud AutoML Vision, AWS Rekognition Custom Labels, Roboflow, Clarifai, Landing AI, Edge Impulse, AlwaysAI, Ultralytics HUB, and V7 (the category leaders).

**Open-source emphasis**: The open-source custom vision ecosystem is **exceptionally mature**, anchored by **Ultralytics YOLO** (industry-standard object detection), **Roboflow Inference** (production-grade self-hosted serving, now free locally), and **NN-GPT** (LLM-driven AutoML from CVPR 2026). **Weights & Biases** provides free experiment tracking for academic research with unlimited tracking and 200GB storage .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ SaaS/Hosted Platforms

> **📊 Market Context**: The global custom computer vision market is estimated at **~$8B in 2026**, growing toward **~$25B by 2032** at a **~21% CAGR**. The sector is **moderately fragmented** — Microsoft, Google, and AWS bundle custom vision as value-adds, while specialized platforms (Roboflow, Ultralytics, Edge Impulse) compete on developer experience and edge deployment. **Critical lifecycle notice**: **Microsoft announced plans to retire Azure Custom Vision** with full support ending **September 25, 2028** . **Pricing varies dramatically**: Microsoft F0 is free with 10K predictions/month , AWS offers 2 free training hours/month , and **Ultralytics Free tier includes 100 models, 100GB storage, and $25 in signup credits** .

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Microsoft Custom Vision](https://azure.microsoft.com/en-us/services/cognitive-services/custom-vision-service/)** | **Retiring September 25, 2028.** Azure's custom image classification and object detection service. | **F0 (Free)**: 10K predictions/month; **S0 (Standard)**: Unlimited predictions  | **F0 tier**: 2 projects, 5,000 training images/project, 10K predictions/month, 50 tags/project  | **~$281B revenue (Microsoft FY2025)** |
| **[Google Cloud AutoML Vision](https://cloud.google.com/vision)** | Google's custom vision training platform (now Vertex AI). AutoML for image classification and object detection. | **Free version** available; **paid starts at $3.15** per unit  | **Free trial** available; Vertex AI achieved **94.37% accuracy with 1,230 training images** in pill recognition study  | **~$350B revenue (Alphabet FY2025)** |
| **[AWS Rekognition Custom Labels](https://aws.amazon.com/rekognition/custom-labels/)** | AWS custom object detection. Train models to detect business-specific objects and scenes . | **Training hours + inference hours**; exact rates via AWS pricing page  | **Free Tier**: **2 free training hours/month** + **1 free inference hour/month**  | **~$638B revenue (Amazon FY2025)** |
| **[Roboflow](https://roboflow.com/)** | **End-to-end CV platform: dataset management, annotation, training, serverless inference.** | **Serverless API**: Per-image pricing; **Core Plan**: Free tier with **10 credits**  | **Core Free Tier**: **10 credits/month** (~30 model trainings or **80,000 inferences** with RF-DETR Nano)  | **Private (~$80M+ raised)** |
| **[Clarifai](https://www.clarifai.com/)** | AI platform for computer vision, NLP, and custom model training. | **Freemium**: **$1.20/month** usage-based starting price | **Free account**: **1,000 free operations** + **1,000 free inputs per month**  | **Private (~$100M+ raised est.)** |
| **[Landing AI](https://landing.ai/)** | Agentic Document Extraction (ADE) for document processing. | **Explore**: Free with **1,000 credits**; **Team**: Subscription; **Enterprise**: Custom  | **Explore plan**: **1,000 free credits** (expire 90 days after account creation)  | **Private (Andrew Ng-backed)** |
| **[Edge Impulse](https://www.edgeimpulse.com/)** | **Edge AI development platform with AutoML for sensor-based ML on MCUs.** | **Developer Plan**: **Free** (formerly Pro)  | **Developer Plan**: **GPU access**, 60-min training jobs, **3 private projects**, up to **3 collaborators**, **production-ready licensing**  | **Private (~$50M+ raised)** |
| **[AlwaysAI](https://alwaysai.co/)** | Edge AI platform for Python developers. EdgeIQ API abstracts inference complexity. | **Custom pricing** — no public price list as of June 2026  | **Free trial** available on request | **Private (~$50M+ raised est.)** |
| **[Ultralytics HUB](https://hub.ultralytics.com/)** | **Cloud platform for YOLO model training and deployment.** | **Free Plan**: $0; **Pro**: Per-seat subscription  | **Free Plan**: Unlimited public/private projects, **100 models**, 3 concurrent trainings, 3 deployments, **100 GB storage**, **$5 signup credit** ($25 with verified company email)  | **Private (~$20M+ raised est.)** |
| **[V7](https://www.v7labs.com/)** | Darwin training-data platform and V7 Go document automation. | **Sales-led**: Quote per seat/workspace/usage  | **Trial on request** — time-limited evaluation access  | **Private (~$50M+ raised est.)** |

## 🔓 Open-Source GitHub Projects

Sorted by star count (descending). Star badge links to each repo's stargazers page.

| Repo | Description | Stars |
|---|---|---|
| **[Ultralytics YOLO](https://github.com/ultralytics/ultralytics)** — **The industry-standard real-time object detection framework.** YOLOv8/v11/v12 with training, validation, prediction, and export to 17+ formats. **Achieved 80.83% accuracy with 26,880 images** in pill recognition study . AGPL-3.0 (commercial license available). | [![Stars](https://img.shields.io/github/stars/ultralytics/ultralytics?style=social&color=white)](https://github.com/ultralytics/ultralytics/stargazers) | ~35,000 |
| **[Roboflow Inference](https://github.com/roboflow/inference)** — **Self-hosted, production-grade CV model serving.** **Now free for local use** on any plan . Supports RF-DETR, YOLO, SAM, and custom models. Apache-2.0. | [![Stars](https://img.shields.io/github/stars/roboflow/inference?style=social&color=white)](https://github.com/roboflow/inference/stargazers) | ~2,000 |
| **[NN-GPT](https://github.com/ABrain-One/NN-GPT)** — **LLM-driven AutoML for neural network development (CVPR 2026).** Turns an LLM into a closed-loop AutoML system. NN-RAG attains **73% executability** on 1,289 targets. Generated **over 10,000 trained models** . | [![Stars](https://img.shields.io/github/stars/ABrain-One/NN-GPT?style=social&color=white)](https://github.com/ABrain-One/NN-GPT/stargazers) | ~1,000 |
| **[Weights & Biases](https://github.com/wandb/wandb)** — **ML experiment tracking, model registry, and AI application evaluation.** **Free forever for academic research**: unlimited tracking, teams, projects, and **200GB cloud storage** . | [![Stars](https://img.shields.io/github/stars/wandb/wandb?style=social&color=white)](https://github.com/wandb/wandb/stargazers) | ~10,000 |
| **[Visionset](https://github.com/visionset/visionset)** — **Open-source computer vision dataset management.** Project creation, schema application, batch ingestion, annotation, release publishing with train/val/test splits, and export to YOLO11, COCO, VOC formats. CLI, SDK, REST API, and MCP server (56 agent tools) . | [![Stars](https://img.shields.io/github/stars/visionset/visionset?style=social&color=white)](https://github.com/visionset/visionset/stargazers) | ~500 |
| **[AndroGen](https://github.com/AndroGen/AndroGen)** — **Open-source synthetic data generation for automated sperm analysis.** Generates realistic labelled datasets without real images or generative training models. Customizable cell morphology and movement parameters . | [![Stars](https://img.shields.io/github/stars/AndroGen/AndroGen?style=social&color=white)](https://github.com/AndroGen/AndroGen/stargazers) | ~100 |

**Additional open-source options worth exploring:**

| Repo | Description |
|---|---|
| **[Label Studio](https://github.com/HumanSignal/label-studio)** — Open-source data labeling for vision, text, and audio. Apache-2.0. |
| **[CVAT](https://github.com/opencv/cvat)** — Computer Vision Annotation Tool. Mature image/video labeling with auto-annotation. MIT. |
| **[FiftyOne](https://github.com/voxel51/fiftyone)** — Dataset curation, visualization, and model debugging for vision. Apache-2.0. |
| **[Detectron2](https://github.com/facebookresearch/detectron2)** — Facebook AI's detection and segmentation library. Apache-2.0. |
| **[MMDetection](https://github.com/open-mmlab/mmdetection)** — OpenMMLab's detection toolbox. 50+ pre-trained models. Apache-2.0. |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Custom computer vision platforms handle potentially sensitive image data; ensure compliance with privacy regulations and obtain proper consent for face or personal data processing.
- **Critical lifecycle notice**: **Microsoft announced plans to retire Azure Custom Vision** with full support ending **September 25, 2028** . Users should plan migration to alternatives.
- **Open-source reality**: The open-source ecosystem for custom computer vision is **exceptionally mature**. **Ultralytics YOLO** is the industry-standard object detection framework, achieving **80.83% accuracy** in independent benchmarks . **Roboflow Inference** provides production-grade self-hosted model serving, now **free locally** . **NN-GPT** (CVPR 2026) demonstrates LLM-driven AutoML generating **over 10,000 trained models** . **Weights & Biases** offers **free academic research licenses** with 200GB storage . However, **commercial platforms** (Roboflow, Ultralytics HUB, Edge Impulse) provide **managed training infrastructure, annotation tools, and deployment pipelines** that open-source alternatives require significant setup to match. The open-source path is **genuinely viable** for organizations with ML engineering capacity.
- **Pricing caveat**: All pricing figures above are **verified against cited search results** but may change without notice. **Microsoft F0 free tier** caps at **10K predictions/month** . **Clarifai free tier** provides **1,000 operations + 1,000 inputs/month** . Always check the provider's official page for current terms.

---

**Made for ML engineers, computer vision developers, data scientists, and AI product teams.**
Let's make custom computer vision more open, transparent, and accessible.
