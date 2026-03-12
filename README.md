# Abhilash P Scaria

**ML Engineer · Production AI Systems · Cloud to Edge**

I ship ML systems with measurable results — not prototypes. Two production systems live at my current company: a computer vision pipeline running at 5ms inference and a serverless IoT forecasting system on AWS. Both owned end to end, from training to monitoring.

> Production code is proprietary. Architecture decisions and results are on [LinkedIn](https://www.linkedin.com/in/abhilash-p-scaria-04359531).

---

## 📊 What I've Shipped

| Result | How |
|---|---|
| **77% inference latency reduction** (22ms → 5ms) | TensorRT optimization on production CV system |
| **Precision 0.50 → 0.75** with recall held at 0.85 | Model iteration with offline eval framework |
| **F1 score 0.63 → 0.80** | Systematic benchmarking across model versions |
| **50% query latency reduction** on LLM pipeline | Dynamic routing — 8B model for simple queries, 70B for complex |
| **2–3% improvement over persistence baseline** | XGBoost/LSTM on IoT time-series sensor data |

---

## 🛠️ Tech Stack

```
ML & Inference     │ PyTorch · TensorFlow · TensorRT · ONNX · Scikit-learn · XGBoost
LLM & Retrieval    │ LangGraph · LangChain · RAG · Qdrant · Groq · vLLM · Prompt Engineering
MLOps & Backend    │ Docker · FastAPI · REST APIs · Prometheus · ELK Stack · Langfuse
Cloud & Data       │ AWS (Lambda · S3 · DynamoDB · API Gateway · ECR) · PostgreSQL · ETL
Edge & Embedded    │ TensorRT · ONNX Runtime · TFLite · ESP32 · TinyML
Languages          │ Python (Advanced) · SQL · C · Shell Scripting
```

---

## 📌 Featured Projects

### 🤖 [Agentic Analytics Copilot](https://github.com/ABhilashscaria)
Enterprise analytics assistant — answers data queries through semantic retrieval and multi-step reasoning.

- **50% query latency reduction** via dynamic model routing (Llama-3.1-8B → Llama-3.3-70B based on complexity)
- Qdrant vector retrieval with cosine similarity over document embeddings — semantic search for RAG
- Full production observability: Langfuse trace logging per query, token cost tracking, Prometheus latency metrics
- `LangGraph · FastAPI · Qdrant · RAG · Langfuse · Prometheus · Groq`

### 🔬 [Depth-Aware Object Detection](https://github.com/ABhilashscaria)
MSc thesis — first unified inference pipeline combining real-time object detection with monocular depth estimation.

- Integrated YOLOv3 and AdaBins into a single forward pass — eliminated the need for two separate inference calls
- Built custom benchmarking suite measuring detection accuracy degradation across 5 depth ranges
- `YOLOv3 · AdaBins · PyTorch`

---

## 📈 Currently Building

- **LLM eval harness** — 100-question test suite with RAGAS scoring to measure RAG quality before and after retrieval changes
- **TinyML on ESP32** — anomaly detection running fully on-device, no cloud dependency, targeting <10ms inference

---

## 🎓 Background

**MSc Artificial Intelligence** — University of Southampton, UK *(Advanced ML · Deep Learning · Computer Vision · Reinforcement Learning)*

**B.Tech Electronics & Communication Engineering** — TKM College of Engineering *(Thesis: Autonomous vehicle prototype with ResNet50 on TensorFlow)*

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abhilash%20P%20Scaria-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/abhilash-p-scaria-04359531)
[![Email](https://img.shields.io/badge/Email-abhilashscariapulickal%40gmail.com-D14836?style=flat&logo=gmail)](mailto:abhilashscariapulickal@gmail.com)

---

*Open to ML Engineering roles in production AI systems, LLM infrastructure, and edge deployment.*
