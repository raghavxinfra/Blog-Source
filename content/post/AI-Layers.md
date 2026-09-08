---
title: "AI Layers"
date: 2026-09-08T10:39:32Z
categories: ["AI", "Infra"]
draft: false
---

#### **In Progress..**


AI Stack Layers at High Level

The full tech stack layers at high level

| Layer | Tools / Tech | Purpose |
|---|---|---|
| **1. Application Layer** | LangChain, LlamaIndex, custom code | RAG pipelines, agents, tool use, memory |
| **2. Retrieval / Data Layer** | Embedding models (Voyage, OpenAI, CLIP); Vector DBs (Pinecone, Qdrant, Milvus, Chroma) | Gives the model relevant, up-to-date context |
| **3. Model Layer** | Claude, GPT, Llama, Gemini | The "brain" that reasons and generates |
| **4. Serving / Inference Layer** | vLLM (inference engine) → llm-d (smart routing) → KServe (Kubernetes deployment, autoscaling) | Runs and scales the model efficiently in production |
| **5. Infrastructure Layer** | GPUs/TPUs, Kubernetes, cloud (AWS/GCP/Azure) | The physical/virtual hardware everything runs on |