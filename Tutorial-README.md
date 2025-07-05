<div align="center">
  <img src="website/public/images/logo.png" alt="HoneyBee Logo" width="200">

  # HoneyBee Tutorial Notebooks  
  **Quick-Start Guides for Clinical, Radiology & Pathology Workflows**

  [Documentation](https://lab-rasool.github.io/HoneyBee/) | [Paper](https://arxiv.org/abs/2405.07460) | [Issues](https://github.com/lab-rasool/HoneyBee/issues)
</div>

---

## 1 · Prerequisites

| Requirement | Minimum Version | Notes |
|-------------|----------------|-------|
| **Python**  | 3.8 | Tested on CPython; Conda or venv recommended |
| **PyTorch** | 2.0 | CUDA 11.7+ optional but strongly advised |
| **JupyterLab / Notebook** | ≥ 3.6 | Launch interface for `.ipynb` files |
| **System Libraries** | OpenSlide, Tesseract-OCR | Needed only for pathology & PDF OCR |

> **Tip** All three tutorials run comfortably on a modern laptop; GPU is recommended for the Radiology and Pathology notebooks.

### 1.1 Install Core Dependencies
```bash
# ❶ Clone the repository
git clone https://github.com/lab-rasool/HoneyBee.git && cd HoneyBee

# ❷ Create & activate a virtual environment
python -m venv venv            # or: conda create -n honeybee python=3.10
source venv/bin/activate       # Windows: venv\Scripts\activate

# ❸ Install Python packages
pip install -r requirements.txt
pip install -e .

# ❹ System packages (Ubuntu example)
sudo apt-get update && \
sudo apt-get install -y openslide-tools tesseract-ocr
```
> For macOS use Homebrew (`brew install openslide tesseract`). Windows binaries are linked on the [OpenSlide](https://openslide.org/download/) and [UB-Mannheim Tesseract](https://github.com/UB-Mannheim/tesseract/wiki) pages.

### 1.2 Environment Variables
Create a `.env` file in the project root if you intend to connect to a MINDS database or HuggingFace Hub:
```dotenv
HOST=your_server
PORT=5433
DB_USER=postgres
PASSWORD=your_password
DATABASE=minds
HF_API_KEY=your_huggingface_api_key
```
_Leave the file blank if these services are not required._

---

## 2 · Launching the Notebooks
```bash
# From the repo root
jupyter lab              # or: jupyter notebook
```
The tutorials are located at:

| Tutorial | Path | Purpose |
|----------|------|---------|
| **Clinical Processing** | `examples/clinical_processing_tutorial.ipynb` | NLP pipeline → embedding → survival & retrieval demos |
| **Radiology Workflow**  | `examples/radiology_tutorial.ipynb` | 3-D DICOM loading, windowing, REMEDIS embedding & patient-level aggregation |
| **Pathology (WSI)**     | `examples/wsi/wsi.ipynb` | Whole-slide tiling, tissue detection, patch embedding & MIL pooling |

Double-click the notebook in the Jupyter file browser, then execute cells top-to-bottom (⌘/Ctrl + ↵).

> **Colab** Upload the notebook or open directly via the GitHub URL (`File › Open Notebook › GitHub`) if you prefer a cloud environment. Ensure GPU runtime is enabled (`Runtime › Change runtime type › GPU`).

---

## 3 · Per-Tutorial Checklists

### 3.1 Clinical Processing
1. **Sample Data** — Place tab-separated clinical notes and CSV demographics in `./data/clinical/`.
2. **Tokenizer Cache** — First run downloads `bert-base-uncased` weights (≈ 1 GB).
3. **Runtime** — ≈ 10 min on CPU for 1 k patients.
4. **Output** — `clinical_embeddings.parquet` + survival curves.

### 3.2 Radiology Workflow
1. **Input** — DICOM or NIfTI exams in `./data/radiology/<PatientID>/`.
2. **GPU Memory** — ≥ 8 GB VRAM recommended for 3-D inference.
3. **Slice Selection** — Demo auto-detects axial abdomen; edit cell #5 to change rules.
4. **Output** — `radiology_embeddings.h5` + similar-patient search widget.

### 3.3 Pathology (WSI)
1. **Slides** — SVS/TIFF files in `./data/wsi/`.
2. **Tissue Detection** — Adjustable Otsu threshold in cell #7.
3. **Patch Size** — Default 256 px @ level 0; modify `PATCH_SIZE` constant.
4. **Runtime** — Whole slide ≈ 90 s on RTX A6000; CPU fallback ~10 × slower.
5. **Output** — `wsi_embeddings.h5` + UMAP visualisation.

---

## 4 · Troubleshooting

| Symptom | Likely Cause | Fix |
|---------|--------------|-----|
| `openslide.OpenSlideError` | Slide format unsupported | Install latest OpenSlide ≥ 4.0 |
| CUBLAS/CUDA errors | Out-of-memory | Reduce batch size or use CPU mode (`USE_GPU=False`) |
| `ModuleNotFoundError: honeybee` inside notebook | Repo not installed in editable mode | `pip install -e .` from repo root |
| Notebook hangs on first cell | Large model download in progress | Wait; progress visible in terminal |

---

## 5 · Next Steps
- Extend tutorials with your own datasets by updating the `DATA_DIR` variables.  
- Combine embeddings from multiple modalities using the `honeybee.integration` module.  
- Share issues & feature requests on the [issue tracker](https://github.com/lab-rasool/HoneyBee/issues).  

---

## 6 · Citation
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
