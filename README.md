<div align='center'>

# Shehroz Ali

### Computer Vision & AI Engineer · MS Data Science Researcher

**CPU-oriented ANPR/OCR · Reproducible ML · LLM/RAG · FastAPI & Docker**

[LinkedIn](https://www.linkedin.com/in/shehroz-rafaqat/) ·
[Portfolio](https://shehrozrafaqat.github.io/ShehrozRafaqatPortfolio/) ·
[Hugging Face](https://huggingface.co/shehrozrafaqat) ·
[Email](mailto:shehrozrafaqat9@gmail.com)

</div>

---

## About

I am a second-year **MS Data Science** researcher at the University of the
Punjab, Lahore, with a **BSc in Computer Science from UET Lahore**. My work sits
at the intersection of computer vision, dependable machine learning, and
production-minded AI engineering.

My thesis focuses on **Qatar-specific Automatic Number Plate Recognition
(ANPR/ALPR)** for commodity CPUs. Beyond computer vision, I build and evaluate
LLM fine-tuning pipelines, grounded RAG applications, NLP systems, FastAPI
services, and containerized data platforms.

- **Current degree:** MS Data Science, University of the Punjab — CGPA 3.52/4.00
- **Research focus:** ANPR/ALPR, OCR, efficient inference, dataset integrity, and reproducible evaluation
- **Engineering focus:** Python AI services, FastAPI, Docker Compose, Azure deployment, and testable ML systems

## Current Thesis — CPU-Oriented Qatar ANPR

**Qatar-Specific End-to-End Automatic Number Plate Recognition with
Reproducible CPU Optimization**

```text
dataset provenance & leakage audit
        → machine preannotation
        → YOLOv9-S ONNX + Latin/Arabic PP-OCRv5
        → Label Studio human review
        → leakage-safe splits
        → training, evaluation & matched CPU benchmarking
```

What is implemented so far:

- Audited **14 ANPR/traffic datasets** spanning 881,730 files and 723,887
  in-scope image records.
- Applied SHA-256 across 746,785 paths and perceptual hashing across 723,554
  decodable images; identified 65,980 within-dataset duplicate groups.
- Processed **1,012 deduplicated Qatar images** through a CPU-only
  preannotation workflow in 496.01 seconds, producing 1,034 candidate regions
  with zero processing errors.
- Built deterministic provenance, resumable inference, multi-plate handling,
  multilingual OCR, strict annotation gates, COCO/YOLO/OCR converters, and
  group-disjoint split tooling.

The project is currently in the human-review stage. Final Qatar training,
frozen evaluation splits, and accuracy reporting follow verified annotations;
I do not report premature model-accuracy claims.

## Selected Engineering & Research

### [ClearClause — Offline Contract Intelligence](https://github.com/ShehrozRafaqat/ClearClause-NLP-Project)

Contract-risk analysis across 17 clause categories with regex + TF-IDF
extraction, explainable scoring, grounded retrieval Q&A, optional Groq
rewriting, and multi-format exports. The pipeline achieved **F1 0.957 on a
held-out contract** and is covered by 21 tests.

### Football-Domain LLM Fine-Tuning

Created a 9,600-example ChatML dataset and fine-tuned:

- [TinyLlama-1.1B with TRL + LoRA](https://huggingface.co/shehrozrafaqat/football-tinyllama-trl-lora)
  — validation loss 0.0762 and validation token accuracy 0.9785.
- [Llama-3.1-8B with Unsloth + QLoRA](https://huggingface.co/shehrozrafaqat/football-llama31-8b-qlora)
  on an NVIDIA T4, with published adapter and comparison artifacts.

### [FastAPI + Docker Data Platform](https://github.com/ShehrozRafaqat/reddit-bigdata-project)

Co-developed a FastAPI/React platform with JWT authentication,
communities/posts/comments/media APIs, PostgreSQL, MongoDB, MinIO, event-log
analytics, Dockerfiles, and Docker Compose. In separate MLOps work, deployed a
MobileNetV2 ONNX FastAPI service to an Azure Ubuntu VM using Uvicorn and systemd;
five-call remote validation averaged **40.95 ms server inference latency**.

### [NLP Desktop Search Engine](https://github.com/ShehrozRafaqat/NLP_Desktop_Search_Engine)

Implemented inverted indexing, Boolean/count/TF-IDF retrieval, cosine ranking,
and phrase/proximity queries. Indexed 50,000 documents and 2.75M tokens into an
11 MB compressed index.

### Cross-Condition Depression-Screening Research

Built a leakage-controlled participant-text screening pipeline using
MiniLM/BGE/MPNet embeddings, PCA, ridge components, source-only cross-fitted
calibration, bootstrap uncertainty, and interviewer-shortcut controls. The
frozen endpoint achieved **AUROC 0.8694** and **F1 0.7755** on a disjoint
56-participant official test. Manuscript in preparation; this is screening
research, not a clinical diagnostic.

## Technical Toolbox

**Computer Vision & OCR**

`OpenCV` · `YOLO` · `ONNX Runtime` · `PaddleOCR / PP-OCRv5` · `Label Studio` ·
object detection · multilingual OCR · image hashing · annotation QA ·
CPU benchmarking

**Machine Learning, LLM & NLP**

`PyTorch` · `scikit-learn` · `Transformers` · `Hugging Face` · `PEFT` ·
`LoRA / QLoRA` · `TRL` · `Unsloth` · embeddings · grounded RAG · `LangChain` ·
`LangGraph` (familiarity)

**AI Engineering & MLOps**

`FastAPI` · REST APIs · `Docker / Compose` · `Azure VM` · Uvicorn · systemd ·
`MLflow` · GitHub Actions · `pytest` · Ruff · Linux · Kubernetes fundamentals

**Languages & Data**

`Python` · `C++` · `C#` · `SQL` · `JavaScript` · Flask · Streamlit · React ·
Node/Express · PostgreSQL · MongoDB · MinIO · NumPy · Pandas · Pydantic

## How I Work

- Prefer deterministic artifacts, explicit failure records, and reproducible
  evaluation over one-off demos.
- Treat dataset provenance, duplicate leakage, annotation quality, and
  uncertainty as first-class engineering problems.
- Build end-to-end: research design, data pipelines, model evaluation, APIs,
  deployment, tests, and technical documentation.

## Contact

I am open to computer-vision, ANPR/OCR, applied-AI, and ML-engineering
opportunities.

- **Email:** [shehrozrafaqat9@gmail.com](mailto:shehrozrafaqat9@gmail.com)
- **LinkedIn:** [linkedin.com/in/shehroz-rafaqat](https://www.linkedin.com/in/shehroz-rafaqat/)
- **Portfolio:** [shehrozrafaqat.github.io/ShehrozRafaqatPortfolio](https://shehrozrafaqat.github.io/ShehrozRafaqatPortfolio/)
- **Hugging Face:** [huggingface.co/shehrozrafaqat](https://huggingface.co/shehrozrafaqat)
