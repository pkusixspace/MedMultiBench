# MedMultiBench

---
<div align="center">

**Beyond Single View: A Comprehensive Benchmark for Medical Multimodal Large Language Models on Multi-Image Understanding**

</div>

## 📖 Overview
 
Real-world clinical diagnosis is intrinsically a **multi-view process** — radiologists scroll through volumetric slices, compare longitudinal scans, and correlate findings across imaging modalities. Yet existing medical VQA benchmarks evaluate models only on isolated single images, creating a fundamental gap between benchmark performance and clinical utility.
 
**MedMultiBench** is the first large-scale benchmark specifically designed for **medical multi-image understanding**, comprising **11,392 expert-curated samples** across **13 subtasks**. It evaluates Multimodal Large Language Models (MLLMs) on four core clinical reasoning dimensions.

## 🏥 Tasks & Dimensions
 
| Task | Subtasks | Samples |
|------|----------|---------|
| **Joint Reasoning** | Organ Recognition, Disease Detection, Segmentation Mask Analysis, Multi-image Description | 3,600+ |
| **Comparative Analysis** | Visual Choice, Visual Retrieval, Difference Description | 2,800+ |
| **Comprehensive Perceptions** | Temporal Analysis, Spatial Ordering, Medical Counting, Video Understanding | 2,800+ |
| **In-Context Learning** | Closed VQA (1/3/5-shot), Open VQA (1/3/5-shot) | 2,000+ |

## 📂 Data Sources
 
MedMultiBench integrates data from publicly available medical datasets:
 
| Source | Description |
|--------|-------------|
| GMAI-MMBench | 284 datasets, 38 modalities, 18 clinical tasks |
| SAM-Med2D | 4.6M images, 31 major organs, segmentation masks |
| IU-Xray | 7,470 chest X-rays with frontal/lateral pairs |
| MedPix | 12,000+ expert-curated patient cases |
| OmniMedVQA | 118,010 images, 12 modalities |
| MMMU (Health & Medicine) | Expert-level multimodal reasoning |
| Med-MIM | Multi-image instruction-following |
| MedFrameQA | Medical video frames (laparoscopy, endoscopy) |

## 📝 Citation
 

 
```bibtex
@article{medmultibench2025xu,
  title     = {Beyond Single View: A Comprehensive Benchmark for Medical Multimodal Large Language Models on Multi-Image Understanding},
  author    = {Dexuan Xu, Jiayin Yuan, Jianing Wang, Yanyuan Chen, Hanpin Wang, Yu Huang},
  journal   = {ACL},
  year      = {2026}
}
```