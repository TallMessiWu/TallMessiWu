[![Website](https://img.shields.io/badge/🌐_tallmessiwu.com-black?style=for-the-badge)](https://tallmessiwu.com)

[![en](https://img.shields.io/badge/lang-en-blue.svg)](https://github.com/TallMessiWu/TallMessiWu/blob/main/README.md)
[![zh](https://img.shields.io/badge/lang-zh-red.svg)](https://github.com/TallMessiWu/TallMessiWu/blob/main/README-zh.md)

# Hi there! 👋 I'm Junlin Wu

> *AI Engineer · Agent Developer · Open Source Builder*

## 👨🏻‍💻 About Me

AI Engineer at Huawei, owning quantization and adaptation of multi-modal diffusion models and LLMs on Ascend chips. I build at the intersection of RAG, ReAct agents, and low-level inference optimization — turning ideas into verifiable, reusable engineering pipelines.

- 🤖 AI Engineer based in Shanghai, China — specializing in LLM inference, Agent systems, and model quantization.
- 🐱 Cat lover · ⚽ Football · 🎸 Guitar · 🎹 Keyboard · 🎥 Videography.
- ✈️ Travel · ♟️ Chess · ⌨️ DOTA 2 — always up for a good game or adventure.

## 🎓 Education

- 🦁 **Columbia University** — M.S. in Data Science (Sep 2023 - Dec 2024)
    - Focus: Generative AI & LLM Applications. Coursework: Computer Vision, NLP, Statistical Modeling, ML in Practice.
- 🔱 **University of California San Diego** — B.S. in Data Science, Minor in Economics (Sep 2019 - Mar 2023)
    - GPA 3.9/4.0 · Cum Laude · Provost Honors (2019-2023)
- 🏫 **The Derryfield School** — High School Diploma (Sep 2017 - Jun 2019)
- 📚 **Linfield Christian School** — High School (Aug 2015 - Jun 2017)

## 🏢 Work Experience

- 🤖 **AI Engineer** at **Huawei Technologies Co., Ltd.** (Aug 2025 - Present | Shanghai)
    - **Multi-modal Diffusion Model Quantization & Optimization:** Led quantization adaptation for Flux, Wan 2.2, and Hunyuan models on next-gen Ascend chips. Achieved **1.5×** inference speedup for Wan 2.2 & Hunyuan, and **2×+** for Flux (exceeding the 1.6× target) through operator-level profiling, precision tuning, and fused operator integration. Built automated DiT-block profiling analysis tool (pandas-based), saving ~50% analysis time and adopted as team standard across 5+ projects.
    - **Qwen3.5 End-to-End Adaptation (Model Owner):** Fully owned Qwen3.5 adaptation on vLLM framework for next-gen Ascend chips — covering functionality validation, quantization, operator fusion, PD separation deployment, and end-to-end performance tuning. Coordinated cross-team efforts across operator, framework, and quantization teams to ensure on-time delivery.
    - **SGLang MXFP Quantization:** Contributed MXFP4 & MXFP8 quantization support to SGLang across three model scenarios — Diffusion, Dense LLM, and MoE LLM. Leveraged Claude Code for AI-assisted development, completing the originally estimated 2-month workload in ~1 week (~75% efficiency gain), validating AI-assisted engineering for complex framework-level tasks.
    - **Engineering Efficiency & Team Impact:** Early adopter and advocate of AI-assisted development (Claude Code) within the team — led 2 internal tech talks, authored the team's AI-assisted coding guide. Built a web-based server whitelist management system to improve team resource utilization. Contributed technical documentation and led multiple internal knowledge-sharing sessions on quantization, performance tuning, and AI-assisted development.

- 🧬 **Data Analyst** at **Columbia University Medical Center** (Nov 2023 - Dec 2024 | New York)
    - Designed end-to-end neuronal activity analysis pipeline for in vivo recording data. Quantified temporal relationships between neural activity and feeding behavior through statistical modeling, supporting identification of key neuropeptidergic neurons regulating satiation.
    - Co-author on *"Brainstem neuropeptidergic neurons link a neurohumoral axis to satiation"* (under review at *Cell*). Built automated data processing scripts adopted for subsequent similar studies.

- 🎉 **Head of Development** at **UCSD CSSA** (Mar 2020 - Mar 2023 | San Diego)
    - Built the organization's official website with Vue.js, Vite, and Flask. Created programming tutorials for 15 team members and designed an internal knowledge-sharing portal.
    - [UCSD CSSA Website](https://www.ucsdcssa.com) · [Department Portal](https://www.wolai.com/tallmessiwu/rjeh4FU2Qrg9bXsL1SftA6)

## 💻 Technical Skills

| Level | Skills |
| --- | --- |
| **Expert** | Python (Pandas / NumPy / Matplotlib), PyTorch, LLM Inference & Serving (vLLM, SGLang), RAG (LangChain, Pinecone), Agent Development (ReAct, Function Calling, MCP) |
| **Proficient** | Model Quantization (MXFP / INT8), Prompt Engineering, OpenAI / DeepSeek API, Streamlit, OpenCV, Scikit-learn, SQL, Flask, asyncio / httpx, GitHub REST API |
| **Familiar** | TensorFlow, Vue.js, TypeScript, D3.js, Java / Spring, Redis, MongoDB, Docker, Git, Linux |

## 🚀 Featured Projects

| Project | Description |
| --- | --- |
| [react-agent](https://github.com/TallMessiWu/react-agent) | Production-grade ReAct Agent built from scratch — zero framework dependencies, DeepSeek API driven. Five-layer architecture with per-tool circuit breakers, exponential backoff with jitter, and graceful degradation. Chain-of-thought visualization via DeepSeek reasoning_content. |
| [TD LLM Streamlit](https://github.com/TallMessiWu/td-llm-streamlit) | Gen AI Executive Advisor for TD Bank — RAG-powered strategic Q&A with GPT-4o + LangChain + Pinecone Serverless. Semantic sliding window chunking, multi-stage retrieval, hallucination guard, and truLens LLM-as-Judge evaluation. |
| [SGLang Quant Eval](https://github.com/TallMessiWu/sglang_quant_eval) | MXFP8/MXFP4 quantization on SGLang for Huawei Ascend NPU — covering Diffusion, Dense LLM, and MoE scenarios with both online quantization and offline pre-quantized weight inference. |
| [DOTA 2 Drafting Backend](https://github.com/TallMessiWu/dota2-drafting-backend) | ML backend for DOTA 2 hero recommendation — 30K+ matches, 821-dim feature engineering, PyTorch / XGBoost / Random Forest ensemble. 51.8% overall accuracy, 58.3% on known counter subsets. |
| [DOTA 2 Drafting Frontend](https://github.com/TallMessiWu/dota2-drafting-frontend) | Vue 3 + Element Plus frontend with captain-mode hero selection interface for DOTA 2 match prediction. |
| [Personal Website](https://tallmessiwu.com) | Modern responsive portfolio built with Vue 3, TypeScript, and Element Plus — VS Code-inspired design with i18n and dark/light themes. |
| [agent-building](https://github.com/TallMessiWu/agent-building) | Progressive 4-week AI Agent system build — ReAct loops, MCP protocol tooling, resilient fault tolerance, and LangGraph state machines. |
| [Iris Recognition](https://github.com/TallMessiWu/iris-recognition) | Deep learning-based iris recognition with PyTorch. |
| [Climate Analysis](https://github.com/TallMessiWu/climate_change_data_analysis) | 100 years of climate data analysis and global warming visualization with Python & D3.js. |

## 📄 Publications

- Chowdhury, S., Kamatkar, N. G., Wang, W. X., Akerele, C. A., Huang, J., **Wu, J.**, Kane, C. M., Bhave, V. M., Huang, H., Wang, X., & Nectow, A. R. (under review). *Brainstem neuropeptidergic neurons link a neurohumoral axis to satiation.* Cell.
- Wu, J. (2022). *A WeChat Application Combined with Convolutional Neural Network for Skin Cancer Recognition.* International Conference on Artificial Intelligence in Education (ICAIE).

## 📱 Contact Me

- 🌐 **Website**: [tallmessiwu.com](https://tallmessiwu.com)
- 📧 **Email**: junlin-wu@foxmail.com
- 🐙 **GitHub**: [TallMessiWu](https://github.com/TallMessiWu)
- 📸 **Instagram**: [@tallmessiwu](https://www.instagram.com/tallmessiwu/)
- 📝 **Weibo**: [@tallmessiwu](https://www.weibo.com/tallmessiwu/)
