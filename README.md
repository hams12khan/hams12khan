<div align="center">

# Hi there, I'm Hammad Khan 👋
### **AI Researcher & Applied Scientist**
**Master of Science by Research in CSE @ IIT Bhubaneswar** *(Collab with KIST, South Korea)*  
*Former Applied Scientist Intern @ Amazon (Central ML)*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hammad-khan-141818211/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/)
[![arXiv](https://img.shields.io/badge/arXiv-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hammadkh241202@gmail.com)

---

> *My research focuses on the intersection of **Robust Representation Learning (Low-Light Vision Transformers)**, **Grounded Multimodal AI (Vision-Language Models & Hallucination Mitigation)**, and **Verifiable Compound Agent Systems (Deterministic DAG Orchestration & RLHF Alignment)**.*

</div>

---

## 🔬 Key Research Areas

```text
┌──────────────────────────────┬──────────────────────────────┬──────────────────────────────┐
│   Computer Vision & ViTs     │   Vision-Language Models     │  Agentic Systems & Alignment │
├──────────────────────────────┼──────────────────────────────┼──────────────────────────────┤
│ • Poisson-Gaussian Denoising │ • Open-Vocabulary Grounding  │ • Deterministic Tool DAGs    │
│ • Deep Metric Learning       │ • VLM Logit Verification     │ • Kahn's Topological Sort    │
│ • Hyperspherical Purity      │ • Hallucination Suppression  │ • PPO Reward Centering       │
│ • Nighttime Benchmark Design │ • Cross-Modal Feature Fusion │ • Enterprise Hierarchical RAG│
└──────────────────────────────┴──────────────────────────────┴──────────────────────────────┘
```

---

## 📚 Publications & Preprints

* **FACTDA: Fetch and Compile Tool DAG Agent**  
  **Hammad Khan**, Charul Paliwal, A. Sharma, S. Kaveri  
  *The ACM Web Search and Data Mining (WSDM) Conference 2027* / *Amazon Machine Learning Conference 2026* `[Submitted]`  
  *Scales tool orchestration over 16,000+ production APIs using a fixed 2-stage execution flow (DAG construction + parallel execution + synthesis), slashing LLM calls by 2.6× over ReAct.*

* **LLCR: Learning Re-Ranking-Friendly Embeddings for Nighttime Person Re-ID**  
  **Hammad Khan**, R. K. Giri, K. V. Thakare, H. Choi, H. Jung, D. P. Dogra, I.-J. Kim  
  *Proceedings of the 40th AAAI Conference on Artificial Intelligence (AAAI 2027)* `[Submitted]`  
  *Proved Proposition 1 via Jensen’s inequality on von Mises-Fisher distributions that SupCon monotonically bounds k-reciprocal neighborhood purity (0.730); achieves SOTA +14.9% mAP on NightReID.*

* **VAST-ReID: A Low-Light Benchmark Dataset for Person Re-Identification with Visual and Attribute-Rich Semantic Tracking**  
  **Hammad Khan**, R. K. Giri, K. V. Thakare, H. Choi, H. Jung, D. P. Dogra, I.-J. Kim  
  *IEEE/CVF Winter Conference on Applications of Computer Vision (WACV 2025)* `[Published]`  
  *Curated a large-scale multimodal benchmark: 1,441 surveillance videos, 12 cameras, 412,500+ bounding boxes, 25 attribute categories, and aligned LLM descriptions.*

* **Modelling Personalized Book Recommendation using Hybrid Filtering**  
  **Hammad Khan**, R. Nath, R. Yadav, S. Tyagi  
  *Proceedings of the IEEE International Conference (2024)* `[Published]`

---

## 💼 Industry & Research Experience

### 🏢 **Amazon — Applied Scientist Intern** *(Central ML Team | Jan 2026 – June 2026)*
* **Visual Defect Verification (SAM 3 + Qwen2.5-VL):** Built a 3-tier multimodal localization pipeline fusing SAM dense segmentation masks with Qwen2.5-VL next-token logit verification, calibrated in log-odds space to achieve **0.000 Harmful Rate** and **0.987 Detection Usefulness Score (DUS)** on noisy seller images.
* **Autonomous Analytical Agent:** Designed a Brain-Hands-Memory topology using Kahn’s topological sort for deterministic DAG scheduling over 11 DuckDB tools, slashing multi-step latency by **4×** and API costs by **~8×**.
* **Enterprise Policy RAG (`AutoChunker`):** Deployed a tree-structured chunking engine for multi-tiered legal documentation, securing **93.5% target hit rate** and **4.83 / 5.0** LLM-as-a-Judge evaluation.

### 🏛️ **IIT Bhubaneswar — Graduate Researcher** *(July 2024 – Present)*
* *Joint research collaboration with the Korea Institute of Science and Technology (KIST).*
* Developed dual-branch Vision Transformers (ViT-B/16) and Task-Aware Enhancers (TAE) to filter sensor-level Poisson-Gaussian noise and recover identity clusters under extreme darkness.

### 🛡️ **Vehant Technologies — Research Intern** *(Security & Surveillance | Sep 2025 – Nov 2025)*
* Built real-time Scene Change Detection (SCD) edge architectures and designed a zero-shot VLM pseudo-labeling pipeline for surveillance video processing.

---

## 🛠️ Featured Open-Source Repositories & Systems

<table>
  <tr>
    <td width="50%">
      <h3 align="center">⚡ FACTDA Agent</h3>
      <p>Training-free compile-and-execute DAG agent scaling to 16,000+ APIs with a fixed 2-LLM call budget, TDWA dense retriever, and Seeded ReAct continuation tail.</p>
      <p align="center">
        <a href="https://github.com/hams12khan"><b>View Code & Paper →</b></a>
      </p>
    </td>
    <td width="50%">
      <h3 align="center">👁️ LLCR Framework</h3>
      <p>Dual-branch ViT-B/16 with Task-Aware Enhancer (TAE), learnable ISP inverse gamma/gain, and metric losses optimizing hyperspherical neighborhood purity under noise.</p>
      <p align="center">
        <a href="https://github.com/hams12khan"><b>View Code & Paper →</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">🎯 End-to-End RLHF with PPO</h3>
      <p>Complete 3-stage alignment engine (SFT → Reward Model → PPO) from scratch in PyTorch. Includes Bradley-Terry reward-centering regularizer (γ=0.01) to eliminate score-shift divergence.</p>
      <p align="center">
        <a href="https://github.com/hams12khan"><b>Explore Repo →</b></a>
      </p>
    </td>
    <td width="50%">
      <h3 align="center">🎨 Modular Latent Diffusion</h3>
      <p>From-scratch PyTorch implementation of Stable Diffusion: custom UNet, VAE, DDPM noise scheduler, and cross-attention conditioning modules.</p>
      <p align="center">
        <a href="https://github.com/hams12khan/Stable-Diffusion-From-Scratch-"><b>Explore Repo →</b></a>
      </p>
    </td>
  </tr>
</table>

---

## 💻 Technical Arsenal

* **Languages & Core:** Python, C++, C, SQL, Bash, LaTeX
* **Deep Learning & Vision:** PyTorch, Torchvision, Vision Transformers (ViT), SAM, OpenCV, Contrastive Metric Learning (SupCon), Zero-DCE, Diffusion Models (DDPM)
* **LLMs & Multimodal:** Hugging Face (Transformers, TRL, PEFT), Vision-Language Models (Qwen2.5-VL, CLIP), RLHF (PPO, DPO), LangChain, LlamaIndex, FAISS
* **Data & Systems:** DuckDB, NumPy, Pandas, Scikit-Learn, Multiprocessing, Kahn's Topological Sorting, AST Parsing
* **MLOps & Infrastructure:** AWS (Bedrock, S3, EC2), Linux, Docker, Git, Weights & Biases (W&B), MLflow, DVC, Tmux, CUDA / Mixed-Precision (AMP)

---

## 📈 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hams12khan&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hams12khan&layout=compact&theme=tokyonight&hide_border=true" width="48%" />
</p>

---

## 📬 Let's Connect & Collaborate

* **Email:** [hammadkh241202@gmail.com](mailto:hammadkh241202@gmail.com)
* **LinkedIn:** [linkedin.com/in/hammad-khan-141818211](https://www.linkedin.com/in/hammad-khan-141818211/)
* **Location:** IIT Bhubaneswar, Odisha, India *(Open to global PhD & Research Scientist opportunities)*

