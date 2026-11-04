
# Hi, I'm Mia 

**Machine learning engineer** building, evaluating, and deploying LLM systems: RAG, agents, fine-tuning, and the MLOps that ships them.

- 🎓 MS in Computer Engineering at **NYU** · BS in Computer Science (ML specialization) from **University of Maryland**
- Two summers as an ML Research Intern at **Johns Hopkins Applied Physics Laboratory**, working on multi-agent RAG, GraphRAG, and LLM evaluation
- Looking for **AI/ML engineering** and **AI-focused** software roles

---

## Featured projects

### [FinQA-RAG-LoRA](https://github.com/miandfetter/FinQA-RAG-LoRA)
**Distilling a frontier model's financial reasoning into a 4B open model.**
`Qwen3` `LoRA` `FAISS` `GCP Vertex AI` `Docker` `pytest`

- Distilled reasoning from Gemini into **Qwen3-4B** with LoRA, training 0.8% of parameters on ~1,900 rejection-sampled examples in 5 hours on a single L4 GPU
- Raised financial-QA accuracy from **58% → 65% (p = 0.002)**, matching the teacher model within the margin of error
- RAG over financial reports with text and tables (Gemini embeddings + FAISS, **Recall@3 = 0.92**)
- Training and eval jobs on Vertex AI with Docker, GCS checkpointing, and 97 pytest tests

### [ML Debugging Agent](https://github.com/miandfetter/ml-debugging-agent)
**A two-agent system that diagnoses broken ML training runs.**
`LangGraph` `MLflow` `AWS ECS Fargate` `Terraform` `GitHub Actions`

- Reads MLflow run data and correctly identified **29 of 30 injected bugs with zero false positives**
- Deployed on AWS ECS Fargate with Terraform-managed infrastructure and S3-backed MLflow artifacts
- CI/CD with GitHub Actions pushing images to ECR via OIDC (no long-lived keys)


---

## 🛠️ Tech stack

| | |
|---|---|
| **Languages** | Python, Java, C |
| **ML frameworks** | PyTorch, TensorFlow, scikit-learn, NumPy |
| **LLMs & agents** | LangGraph, CrewAI, smolagents, PydanticAI, FAISS, Neo4j |
| **MLOps & cloud** | GCP Vertex AI, AWS (ECS, S3, ECR), Docker, Terraform, MLflow, GitHub Actions, pytest |
| **Techniques** | RAG, GraphRAG, LoRA fine-tuning, distillation, LLM-as-a-judge evaluation, computer vision |

---



## Get in touch
[LinkedIn](https://www.linkedin.com/in/mia-ndfetter/) · [Email](mailto:miandfetter@gmail.com) · [Resume](https://drive.google.com/file/d/1D4Vsa4L7TL1aZZS2hcINVg855NmCz_Df/view?usp=sharing)


