
# Hi there, I'm Madiha Iqbal! 

<!-- Dynamic CSS Typing Display -->
<div align="left">
  <h1>
    I am an <br/>
    <a href="https://github.com">
      <img src="https://demolab.com" alt="Typing SVG" />
    </a>
  </h1>
</div>
---

## 🤖 Research & Engineering Focus
I am an AI Engineer specializing in **Computer Vision**, **Generative AI (Synthetic Data Generation)**, and **Agentic AI systems**. My focus spans the entire machine learning lifecycle—from fundamental research and model alignment to cloud-native production deployment.

- 🔭 **Current Focus:** Drafting a research manuscript on deep-learning-based Detection & Semantic Segmentation.
- 🔬 **Research Interests:** Multimodal alignment (CLIP), synthetic data generation (Stable Diffusion, StyleGAN3) with strict metrics evaluation, and trustworthy clinical AI systems.
- 🎓 **Goal:** To build a reliable AI systems.

---

## 🛠️ Technical Toolkit

| Domain | Tools, Frameworks & Libraries |
| :--- | :--- |
| **Programming & Core** | Python, C++, Jupyter, Anaconda |
| **Deep Learning & LLMs** | PyTorch, TensorFlow, Hugging Face (Transformers, Diffusers, PEFT, TRL) |
| **Computer Vision** | CLIP, YOLOv8, DeepLabV3, SegFormer, U-Net, OpenCV, Albumentations |
| **Generative Models** | GANs (StyleGAN3, pix2pix), Stable Diffusion, LoRA Fine Tuning |
| **LLM & Agentic Systems** | Llama 3.2, LangChain, LangGraph, Model Context Protocol (MCP), RAG, AI Agents |
| **LLM Fine-Tuning** | LoRA/PEFT, SFT, DPO, LLM-judged preference evaluation |
| **Evaluation Metrics** | RAGAS (faithfulness, relevancy, context), FID, SSIM, PSNR, LPIPS |
| **Deployment & Cloud** | FastAPI, Flask, Docker, AWS EC2, Nginx |

---

## 🚀 Featured AI Projects & Research

### 🔬 [Manuscript Under Review] Computer Vision & Structural Health Monitoring
*Unified deep learning pipelines combining structural object detection and multi-class semantic segmentation.*
- **Semantic Segmentation:** Trained **DeepLabV3** and **SegFormer** architectures on **HUST Rebar** and **APERI** datasets for concrete damage classification. Implemented class-wise IoU, F1-score, Precision, Recall tracking, and early stopping.
- **U-Net Pipeline:** Engineered an end-to-end 4-class U-Net segmentation system from scratch featuring custom dataset loaders and automated best-model checkpoint saving.
- **Object Detection:** Applied **YOLOv8** for real-time concrete crack and spalling detection, integrating outputs into downstream analysis workflows.
- **Tech Stack:** PyTorch, YOLOv8, DeepLabV3, SegFormer, U-Net, Albumentations, OpenCV.

###  [Generative AI & Biomedical Imaging](https://github.com/Knee-Xray-Generative-AI)
*Developed an end-to-end framework to synthesize high-fidelity knee X-ray images to tackle medical data scarcity while bypassing GDPR privacy constraints.*
- **Methodology:** Trained **StyleGAN3** on knee radiographs at 512×512 resolution for data augmentation. Fine-tuned **Stable Diffusion 1.5 using LoRA** for domain-specific target generation and experimented with **pix2pix** for image-to-image translation.
- **Quantitative Rigor:** Evaluated distributional similarity, structural similarity, and perceptual quality using **FID, SSIM, PSNR, and LPIPS metrics** over visual inspection alone.

###  [Trustworthy & Evidence-Grounded AI: Context-Aware Medical RAG Assistant](https://github.com/ContextAware-Medical-RAG)
*An intelligent clinical Q&A assistant featuring source-cited processing and fully local LLM inference.*
- **Pipeline Architecture:** Constructed a complete contextual Retrieval-Augmented Generation pipeline using recursive document chunking, semantic embeddings, and **FAISS vector search** for grounded medical question answering.
- **RAGAS Evaluation:** Validated generation quality on a curated medical QA benchmark, achieving **96.7% faithfulness, 91.2% answer relevancy, and 80.1% context precision** to directly target and minimize hallucinations.
- **Tech Stack:** LangChain, FAISS, Ollama (Llama 3.2), Flask, Docker.

### [LLM Fine-Tuning: SFT + DPO on Llama-3.2-3B](https://github.com/Preference-Aligned-Medical-LLM)
*Preference alignment framework optimizing small language models for reliable medical question answering.*
- **Alignment Strategy:** Fine-tuned Llama-3.2-3B-Instruct using LoRA-based Supervised Fine-Tuning (**SFT**) followed by Direct Preference Optimization (**DPO**).
- **LLM-Judged Evaluation:** Designed a pairwise preference assessment across 5 criteria (*accuracy, completeness, safety/harmlessness, clarity & conciseness, tone & helpfulness*) to evaluate alignment methods on held-out prompts.
- **Key Findings:** **DPO-tuned outputs were preferred in 90% of head-to-head comparisons** over SFT, showing massive gains in *clarity & conciseness* (2.90 → 4.10) and *tone & helpfulness* (3.60 → 4.30).
- **Tech Stack:** Hugging Face TRL, PEFT, LoRA.

###  [Agentic AI & Workflow Automation](https://github.com/multi-agent-inventory-system)
*Advanced autonomous orchestration systems built with multi-agent design patterns.*
- **Multi-Agent Platform:** Designed a platform routing user requests to specialized agents via **LangGraph workflow orchestration** and the **Model Context Protocol (MCP)** with an AI planner for tool execution. Supports FAISS document retrieval, real-time web search integration, voice interaction, and conversational AI end-to-end. [(Demo Repo)](https://github.com/voice-rag-ai-assistant)
- **AI Inventory Agent:** Built an AI-agent-based inventory monitoring decision support system for Low/Medium/High stock-risk classification, backed by a **FastAPI** backend with daily de-duplication logic and an interactive **Streamlit** dashboard.
- **Tech Stack:** LangGraph, MCP, FAISS, Ollama, Python, FastAPI, Streamlit, Pandas.

---

##  Git Metrics & Activity

<p align="left">
  <img src="https://vercel.app" alt="Madiha's GitHub Stats" height="150" />
  <img src="https://vercel.app" alt="Top Languages" height="150" />
</p>

---

## Let's Connect!
-  **LinkedIn:** https://www.linkedin.com/in/madiha-iqbal-3432a8277/ 
- **Email:** madihaiqbal786786@gmail.com
