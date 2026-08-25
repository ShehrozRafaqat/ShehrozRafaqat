<div align="center">

# Shehroz Ali

### Computer Vision & AI Engineer · MS Data Science Researcher

**Computer Vision · Applied Machine Learning · NLP/LLMs · AI Platforms · Reproducible Research**

[LinkedIn](https://www.linkedin.com/in/shehroz-rafaqat/) ·
[Hugging Face](https://huggingface.co/shehrozrafaqat) ·
[Email](mailto:shehrozrafaqat9@gmail.com)

</div>

---

## About

I build end-to-end AI systems across computer vision, OCR, machine learning,
NLP/LLMs, and deployment. My work ranges from research design and data-quality
engineering to model evaluation, APIs, containers, and cloud infrastructure.

I am currently pursuing an **MS in Data Science at the University of the
Punjab** (CGPA **3.52/4.00**) after completing a **BSc in Computer Science at
UET Lahore**. I value careful evaluation, explicit limitations, and software
that remains understandable and reproducible after the first demo.

## What I Work On

- **Computer Vision & OCR:** object detection, multilingual text recognition,
  annotation systems, ONNX inference, and efficient CPU-oriented pipelines.
- **Machine Learning Research:** leakage-aware evaluation, dataset integrity,
  uncertainty analysis, reproducible experiments, and cross-domain validation.
- **NLP, LLMs & Retrieval:** embeddings, RAG, parameter-efficient fine-tuning,
  grounded generation, and classical information retrieval.
- **AI Platform Engineering:** FastAPI services, Docker/Compose, relational and
  document databases, object storage, CI, and Azure deployment.

## Selected Research & Engineering

### Efficient End-to-End ANPR Research Platform

My MS thesis develops a high-accuracy ANPR system for commodity CPU deployment,
with Qatar licence plates as the primary research domain. The completed
engineering foundation includes:

- readiness and integrity auditing for **14 ANPR/traffic datasets** covering
  **723,887 in-scope image records**;
- SHA-256 and perceptual-hash analysis, provenance/licensing registries, and
  duplicate/leakage controls;
- resumable YOLO/ONNX plus Latin/Arabic PP-OCRv5 machine preannotation over
  **1,012 canonical target-domain images**, with deterministic crop lineage and
  zero processing errors;
- a versioned Label Studio workflow, strict human-export validation,
  COCO/YOLO/OCR converters, conflict-aware merging, leakage-safe split gates,
  and automated pytest/Ruff/GitHub Actions validation.

Machine suggestions remain separate from human ground truth. Training,
distillation, OpenVINO/INT8 comparison, and final accuracy-efficiency evaluation
follow the human-verification and split-freeze gates.

### Participant-Text Depression Screening Research

Built a leakage-controlled cross-condition screening pipeline using
MiniLM/BGE/MPNet embeddings, PCA, ridge models, cross-fitted calibration,
participant-bootstrap uncertainty, and shortcut controls. The frozen endpoint
reached **AUROC 0.8694** and **F1 0.7755** on a disjoint 56-participant official
test. Manuscript in preparation; this is screening research, not a clinical
diagnostic.

### Structured Policy-Transfer Research

Co-developed a reproducible benchmark spanning **2,300 movie-policy
decisions**, controlled target variants, three holdout settings, and
movie-clustered bootstrap intervals. The analysis showed that apparent transfer
gains were split-sensitive rather than universal. Manuscript in preparation.

## Selected AI Projects

### [ClearClause — Explainable Contract Intelligence](https://github.com/ShehrozRafaqat/ClearClause-NLP-Project)

Led the NLP pipeline, risk scoring, calibration, and Streamlit architecture for
a 17-clause contract analyzer with document-grounded retrieval Q&A, offline
fallback, optional Groq generation, and multi-format exports. Achieved **F1
0.957 on one held-out contract** with **21/21 tests** passing.

### Football-Domain LLM Fine-Tuning

Created a 9,600-example ChatML dataset and fine-tuned:

- [TinyLlama-1.1B with TRL + LoRA](https://huggingface.co/shehrozrafaqat/football-tinyllama-trl-lora)
- [Llama-3.1-8B with Unsloth + QLoRA](https://huggingface.co/shehrozrafaqat/football-llama31-8b-qlora)

Published PEFT adapters with held-out evaluation and Gradio comparison
interfaces.

### [FastAPI Data Platform & Azure Model Service](https://github.com/ShehrozRafaqat/reddit-bigdata-project)

Co-developed a FastAPI/React platform with JWT authentication, PostgreSQL,
MongoDB, MinIO, event logs, Dockerfiles, and Docker Compose. Separately packaged
a MobileNetV2 ONNX classifier behind FastAPI endpoints and deployed it to an
Azure Ubuntu VM with Uvicorn/systemd, plus CLI and Streamlit clients.

### [NLP Desktop Search Engine](https://github.com/ShehrozRafaqat/NLP_Desktop_Search_Engine)

Implemented persistent inverted indexing, Boolean/count/TF-IDF retrieval,
cosine ranking, and phrase/proximity queries; indexed **50,000 documents** and
**2.75 million tokens** into an **11 MB compressed index**.

## Current Research Threads

- efficient computer vision and multilingual OCR under CPU constraints;
- reliable participant-text screening and longitudinal mobile-sensing methods;
- causal mechanisms behind long-context LLM decision instability;
- dependable RAG, model adaptation, and evaluation for applied AI systems.

Early-stage work is described as research in progress rather than as completed
experimental results.

## Technical Toolkit

**Vision & OCR:** `OpenCV` · `YOLO` · `PaddleOCR / PP-OCRv5` · `ONNX Runtime` ·
`Label Studio` · object detection · annotation pipelines · image hashing

**ML, LLM & NLP:** `PyTorch` · `scikit-learn` · `Transformers` ·
`Hugging Face` · `PEFT` · `LoRA / QLoRA` · embeddings · `RAG` · `LangChain` ·
`MLflow` · `LangGraph` familiarity

**Engineering & MLOps:** `Python` · `C++` · `C#` · `SQL` · `FastAPI` · `Flask` ·
`Docker / Compose` · `Azure` · `GitHub Actions` · `pytest` · `Ruff` · `Linux` ·
Kubernetes fundamentals

**Data & Applications:** `PostgreSQL` · `MongoDB` · `MinIO` · `NumPy` ·
`Pandas` · `Pydantic` · `Streamlit` · `React` · `JavaScript`

## Engineering Principles

- Preserve provenance, deterministic artifacts, and explicit failure records.
- Treat leakage, annotation quality, uncertainty, privacy, and licensing as
  engineering concerns—not documentation afterthoughts.
- Separate exploratory work, machine suggestions, and planned experiments from
  verified results.
- Build across the full lifecycle: data, models, evaluation, APIs, deployment,
  tests, and technical documentation.

## Contact

I am open to opportunities and collaboration in computer vision, applied AI,
machine learning, NLP/LLMs, and AI platform engineering.

- **Email:** [shehrozrafaqat9@gmail.com](mailto:shehrozrafaqat9@gmail.com)
- **LinkedIn:** [linkedin.com/in/shehroz-rafaqat](https://www.linkedin.com/in/shehroz-rafaqat/)
- **Hugging Face:** [huggingface.co/shehrozrafaqat](https://huggingface.co/shehrozrafaqat)
