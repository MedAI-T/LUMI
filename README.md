# LUMI

**Towards Real-World Ultrasound Understanding Large Vision-Language Models from Multi-Image Examinations with Long-Form Reports**

This repository contains the project page for our work on real-world ultrasound understanding with large vision-language models (LVLMs).

## Overview

Large vision-language models have achieved strong performance across many medical imaging tasks, but ultrasound remains challenging because of its high variability, operator dependence, multi-organ coverage, and examination-level clinical workflow. In this work, we study what is truly needed to enable practical ultrasound understanding.

Instead of relying on complex model architectures or task-specific training pipelines, we show that two factors are especially important:

1. **Data scale**: training on a large number of real-world ultrasound examinations.
2. **Clinically faithful data alignment**: organizing data at the examination level, where multiple ultrasound images are aligned with their corresponding long-form clinical reports.

We construct a large-scale ultrasound dataset consisting of **1.5M real-world examinations** and **17.7M images**, covering multiple organs and paired with uncurated clinical reports. We then fine-tune a standard LVLM using **LoRA** without task-specific architectural modifications.

Despite its simplicity, this recipe achieves strong performance across diverse ultrasound understanding tasks and outperforms prior methods that rely on more complex pipelines. We further provide model and data scaling analyses to better understand the role of scale in ultrasound LVLMs.

## Project Page

The project page includes:

- Paper information
- Abstract
- Project video
- BibTeX citation

After deployment with GitHub Pages, the website will be available at:

```text
https://<your-github-username>.github.io/<repository-name>/
```

## Repository Structure

```text
.
├── index.html              # Main project page
├── README.md               # Repository description
└── static/
    ├── css/
    │   └── index.css       # Page styling
    ├── images/
    │   └── LOGO.png     # Website favicon
    └── videos/             # Optional local videos
```

## Paper

```text
Towards Real-World Ultrasound Understanding:
Large Vision-Language Models from Multi-Image Examinations with Long-Form Reports
```

arXiv link:

```text
https://arxiv.org/abs/XXXX.XXXXX
```

Please replace the placeholder arXiv identifier after the paper is online.

## Video

The project page currently embeds the following YouTube video:

```text
https://www.youtube.com/embed/JkaxUblCGz0
```

## Dataset and Model Availability

The dataset used in this work consists of real-world clinical ultrasound examinations and reports. Due to patient privacy, data governance, and clinical compliance requirements, the raw clinical data are not directly released in this repository.

Model checkpoints, code, or additional resources may be released separately when available.

## Citation

```bibtex
@article{ultrasound_lvlm_2026,
  title   = {Towards Real-World Ultrasound Understanding: Large Vision-Language Models from Multi-Image Examinations with Long-Form Reports},
  author  = {Team},
  journal = {arXiv preprint arXiv:XXXX.XXXXX},
  year    = {2026}
}
```

Please update the author list and arXiv identifier after the official paper release.

## License

This repository is intended for hosting the academic project page. Please update this section with the appropriate license before public release.
