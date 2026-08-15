<div align="center">

# Orhan Cenk Akcadoğan

<a href='https://cenkakcadogan.com/'>cenkakcadogan.com

### Applied AI / Machine Learning Engineer

I build end-to-end machine learning systems that move beyond notebooks and into usable products: data pipelines, model training and evaluation, APIs, real-time processing, observability, deployment, and user-facing applications.

My background also spans mobile and full-stack product development, which I use to turn ML work into complete systems rather than isolated models.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Orhan%20Cenk%20Akcadoğan-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/orhancenkakcadogan)
[![Email](https://img.shields.io/badge/Email-cenkakcadogan%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:cenkakcadogan@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-@imcenkk-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/imcenkk)

</div>

## Focus

- **Applied Machine Learning:** classification, NLP, embeddings, semantic search, computer vision, audio ML, model evaluation
- **ML Engineering:** feature pipelines, experiment tracking, model serving, reproducibility, drift monitoring, explainability
- **Real-Time & Backend Systems:** event-driven architectures, Kafka-compatible streaming, low-latency APIs, durable job processing
- **Product Engineering:** React Native, Expo, React, Next.js, Supabase, PostgreSQL, cloud-backed applications

## Featured Projects

### [Real-Time Fraud Detection Platform](https://github.com/CenkAk/Real-Time-Fraud-Detection-Platform)

A production-style fraud detection platform covering the full ML lifecycle, from leakage-safe feature engineering and temporal evaluation to real-time scoring, monitoring, and operational decisioning.

- Trained and compared multiple model and imbalance strategies on **249,992 chronologically split transactions**
- Selected an **XGBoost** champion using business-cost optimization rather than accuracy alone
- Achieved **0.3139 PR-AUC**, **0.9000 precision**, and **0.4235 F1** on an untouched temporal test partition
- Implemented configurable **APPROVE / REVIEW / BLOCK** decisioning with separate review and block thresholds
- Built idempotent Kafka consumers and a transactional outbox for retry-safe event processing
- Added SHAP explainability, delayed-label monitoring, drift detection, MLflow tracking, Prometheus/Grafana observability, and automated tests

**Stack:** Python · XGBoost · scikit-learn · FastAPI · PostgreSQL · Kafka/Redpanda · MLflow · SHAP · Docker · Prometheus · Grafana

---

### [Neural Singing Voice Platform](https://github.com/CenkAk/Neural-Singing-Voice-Platform)

A modular, consent-based Audio ML platform for personalized singing voice conversion using authorized singer recordings and authorized music.

- Built audio validation, silence-aware segmentation, deterministic dataset manifests, and content-addressed artifact workflows
- Designed pluggable **Demucs** source-separation and **Seed-VC** voice-conversion adapters so pretrained systems remain isolated behind clear interfaces
- Added F0 analysis with TorchCREPE/PyWORLD-compatible paths, conservative post-processing, gain-safe mixing, and repeatable audio/pitch evaluation
- Implemented durable SQLite-backed jobs, a **FastAPI** service, local worker architecture, model registry, and **React/Vite** interface
- Designed backend-portable ML setup for CUDA, ROCm, DirectML, MPS, and CPU environments where supported by dependencies
- Validated the dependency-light vertical slice with generated audio and automated tests; real singer quality and hardware-specific performance are reported only after measurement

**Stack:** Python · PyTorch · Audio ML · FastAPI · Demucs · Seed-VC · TorchCREPE · React/Vite · SQLite · MLflow

## Other ML Work

### Skin Condition Classification & Detection

Built a computer-vision pipeline around the SCIN dermatology dataset, trained an Ultralytics YOLO model across seven categories, and exported the resulting model to ONNX for portable inference.

### Semantic Banking Assistant

Built an NLP-based banking assistant using the Banking77 dataset, Sentence Transformers, semantic embeddings, cosine-similarity ranking, confidence thresholds, and top-k retrieval.

## Current Direction

I'm currently expanding further into production ML and deep learning, with upcoming work focused on:

- recommendation and ranking systems
- personalized feed modeling and embeddings
- scalable ML inference and evaluation
- practical MLOps and model observability

## Technology Stack

**Machine Learning & AI**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5B28?style=flat-square&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)

**Backend, Data & MLOps**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Product Engineering**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

---

<div align="center">
  <sub>Building ML systems that are measurable, deployable, and useful.</sub>
</div>
