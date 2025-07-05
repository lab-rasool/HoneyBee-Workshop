<div align="center">

  # HONeYBEE: Harmonized Oncology Biomedical Embedding Encoder
  # HoneyBee Tutorial Notebooks  
  **Quick-Start Guides for Clinical, Radiology, Pathology & Molecular Workflows**

   [Examples](examples/) | [Documentation](https://lab-rasool.github.io/HoneyBee/) | [Paper](https://arxiv.org/abs/2405.07460) | [Issues](https://github.com/lab-rasool/HoneyBee/issues)
</div>

---

## 🚀 Overview

HoneyBee is a comprehensive multimodal AI framework designed specifically for oncology research and clinical applications. It seamlessly integrates and processes diverse medical data types—clinical text, radiology images, pathology slides, and molecular data—through a unified, modular architecture. Built with scalability and extensibility in mind, HoneyBee empowers researchers to develop sophisticated AI models for cancer diagnosis, prognosis, and treatment planning.

> [!WARNING]
> **Alpha Release**: This framework is currently in alpha. APIs may change, and some features are still under development.

## ✨ Key Features

### 🏗️ Modular Architecture
- **3-Layer Design**: Clean separation between data loaders, embedding models, and processors
- **Unified API**: Consistent interface across all modalities
- **Extensible**: Easy to add new models and data sources
- **Production-Ready**: Optimized for both research and clinical deployment

### 📊 Comprehensive Data Support

#### Medical Imaging
- **Pathology**: Whole Slide Images (WSI) - SVS, TIFF formats with tissue detection
- **Radiology**: DICOM, NIFTI processing with 3D support
- **Preprocessing**: Advanced augmentation and normalization pipelines

#### Clinical Text
- **Document Processing**: PDF support with OCR for scanned documents
- **NLP Pipeline**: Cancer entity extraction, temporal parsing, medical ontology integration
- **Database Integration**: Native [MINDS](https://github.com/lab-rasool/MINDS) format support
- **Long Document Handling**: Multiple tokenization strategies for clinical notes

#### Molecular Data
- **Genomics**: Support for expression data and mutation profiles
- **Integration**: Seamless combination with imaging and clinical data

### 🧠 State-of-the-Art Embedding Models

#### Clinical Text Embeddings
- **GatorTron**: Domain-specific clinical language model
- **BioBERT**: Biomedical text understanding
- **PubMedBERT**: Scientific literature embeddings
- **Clinical-T5**: Text-to-text clinical transformers

#### Medical Image Embeddings
- **REMEDIS**: Self-supervised medical image representations
- **RadImageNet**: Pre-trained radiological feature extractors
- **UNI**: Universal medical image encoder
- **Custom Models**: Easy integration of proprietary models

### 🛠️ Advanced Capabilities

#### Multimodal Integration
- **Cross-Modal Learning**: Unified representations across modalities
- **Attention Mechanisms**: Interpretable fusion strategies
- **Patient-Level Aggregation**: Comprehensive patient profiles

#### Analysis Tools
- **Survival Analysis**: Cox PH, Random Survival Forest, DeepSurv
- **Classification**: Multi-class cancer type prediction
- **Retrieval**: Similar patient identification
- **Visualization**: Interactive t-SNE dashboards

#### Clinical Applications
- **Risk Stratification**: Patient outcome prediction
- **Treatment Planning**: Personalized therapy recommendations
- **Biomarker Discovery**: Multi-omic pattern identification

## 🚀 Quick Start (for the complete framework)

### Prerequisites 

- Python 3.8+
- PyTorch 2.0+
- CUDA 11.7+ (optional, for GPU acceleration)

---
## 🚀 Quick Start (for this Workshop)
## 1 · Prerequisites

Just login with your GMAIL account and launch [Google Colab](https://colab.research.google.com/).

---

## Launching the Notebooks
The tutorials are located at:

| Tutorial | Path | Purpose |
|----------|------|---------|
| **Clinical Processing** | `examples/clinical_processing_tutorial.ipynb` | NLP pipeline → embedding → survival & retrieval demos |
| **Radiology Workflow**  | `examples/radiology_tutorial.ipynb` | 3-D DICOM loading, windowing, REMEDIS embedding & patient-level aggregation |
| **Pathology (WSI)**     | `examples/wsi/wsi.ipynb` | Whole-slide tiling, tissue detection, patch embedding & MIL pooling |

Double-click the notebook in the Jupyter file browser, then execute cells top-to-bottom (⌘/Ctrl + ↵).

> **Colab** Upload the notebook or open directly via the GitHub URL (`File › Open Notebook › GitHub`) if you prefer a cloud environment. Ensure GPU runtime is enabled (`Runtime › Change runtime type › GPU`).

---

## Citation
If these notebooks assist your research, please cite:
```bibtex
@article{tripathi2024honeybee,
  title   = {HoneyBee: A Scalable Modular Framework for Creating Multimodal Oncology Datasets with Foundational Embedding Models},
  author  = {Aakash Tripathi and Asim Waqas and Yasin Yilmaz and Ghulam Rasool},
  journal = {arXiv preprint arXiv:2405.07460},
  year    = {2024}
}
```

---
<div align="center">
  Built with 🔬 and 🖤 by the <a href="https://github.com/lab-rasool">Lab Rasool</a> team
</div>
