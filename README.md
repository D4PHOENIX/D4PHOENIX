# 👻 Daud Noman Haider · aka GHOST
 
> *"May the --force be with you."* ✨
 
ML engineer working in medical imaging. I build systems that have to survive contact with real data — then I go find out why they broke.
 
---
 
## 🩻 [MediScanX](https://github.com/D4PHOENIX/MediScanX)
 
A microservice platform for medical imaging triage across chest X-ray, ECG and skin lesions, with a clinical RAG assistant on top. Built with a team of three. My part:
 
- **Chest X-ray pipeline** — SE-block DenseNet-121, a hierarchical loss over an 18-pair label taxonomy, CLAHE preprocessing, per-class Youden's J thresholds, capped `pos_weight` for minority classes, and Grad-CAM++ explanations.
- **Clinical RAG** — a LangGraph agent with MedCPT retrieval, cross-encoder reranking and 768-d embeddings in pgvector (HNSW).
- **Backend & CI** — five FastAPI services on Docker Compose, inference pipelines for every model, 321 pytest tests and five path-filtered GitHub Actions workflows.
- **Throughput** — Kaggle epochs down from ~48 min to ~11 min by caching preprocessing and replacing `nn.DataParallel` with a tuned single-GPU loop.


| CheXpert val | CheXpert test | VinDr-CXR | NIH ChestX-ray14 | Indiana OpenI |
|:-:|:-:|:-:|:-:|:-:|
| **0.912** | **0.881** | 0.858 | 0.706 | 0.680 |
 
<sub>Mean AUC. VinDr, NIH and OpenI are external datasets the model never saw in training. The drop is the interesting part.</sub>
 
---
 
## 🛠️ More Work
 
- **[CppCheck-Py](https://github.com/D4PHOENIX/CppCheck-Py)** — a C++ syntax checker in Python with a Streamlit front end, shipped as a Docker container on Hugging Face Spaces. Team lead.
- **[Hand Gesture Recognition](https://github.com/D4PHOENIX/Hand-Gesture-Recognition-Project)** — media playback controlled by hand gestures, trained on a dataset I built myself.
- **[WiseUp](https://github.com/D4PHOENIX/WiseUp)** — an NLP assistant for chat, quiz generation and text summarization.
- **Freelance ML** — a comparative object-detection study (YOLOv5/v8, Faster R-CNN, RetinaNet on COCO128), a BERT study review and a license-plate detector.
---
 
## 🧭 In the Queue
 
- **Senkaimon-Bridge** — reverse-engineering a smartwatch.
- **Ghost in the Machine** — name reserved. Embedded systems. Not yet.
---
 
## 🧰 Stack
 
- **Languages:** Python (primary), C++
- **ML:** PyTorch, TensorFlow / TFLite, ai-edge-torch, scikit-learn, OpenCV, Pandas
- **Retrieval & agents:** LangGraph, MedCPT, pgvector
- **Backend:** FastAPI (async), Supabase (Postgres + auth), MySQL
- **Infra:** Docker, Docker Compose, GitHub Actions, pytest, Git
- **Platforms:** Kaggle, Google Cloud, Hugging Face Spaces, Weights & Biases
- **Daily driver:** Arch Linux + Hyprland, on a machine named GHOUL
---
 
## 📈 Stats
 
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=D4PHOENIX&show_icons=true&theme=dark)
 
---
 
🥋 Away from the terminal: boxing, karate, piano, and Yoshikawa's *Musashi*.
 
---
 
## 📫 Connect
 
- 🌐 [LinkedIn](https://www.linkedin.com/in/daudnoman/)
- 🐦 [X / Twitter](https://twitter.com/dash_bacha)
---
 
*Fortis Fortuna Adiuvat*
