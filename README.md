<div align="center">

<img src="assets/taha-banner.svg" alt="Muhammad Taha Nasir Header Banner" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=16&duration=2500&pause=800&color=38BDF8&center=true&vCenter=true&width=780&lines=Building+production+AI+systems+that+understand%2C+reason%2C+and+act.;LLMs+%7C+Hybrid+RAG+%7C+Agentic+DAGs+%7C+Real-Time+Voice+AI;From+voice+to+vector%2C+from+data+to+decisions.;Build+systems%2C+not+just+demos." />

</div>

# 👨💻 Executive Summary

> **Computer Science student at FAST-NUCES specializing in Generative AI, LLM applications, real-time Voice AI agents, and intelligent software architectures.**

Experienced in building production-grade AI applications including Retrieval-Augmented Generation (RAG) systems, voice agents, and machine learning solutions using LangGraph, LangChain, FastAPI, React, and Python. Strong foundation in machine learning, backend engineering, and scalable software development.

```python
from dataclasses import dataclass
from typing import List, Dict

@dataclass
class GenerativeAIEngineer:
    name: str = "Muhammad Taha Nasir"
    role: str = "Generative AI Engineer & Systems Architect"
    education: str = "BS Computer Science @ FAST-NUCES (2023 - Present)"
    leadership: str = "President @ FAST Innovation Club"
    mindset: str = "Build scalable systems, not just standalone demos."

    core_stack: Dict[str, List[str]] = None

    def __post_init__(self) -> None:
        self.core_stack = {
            "ai_orchestration": ["LangGraph", "LangChain", "Pipecat", "LlamaIndex"],
            "models_retrieval": ["PyTorch", "Hybrid RAG", "ChromaDB", "Re-Rankers"],
            "backend_infra": ["Python", "FastAPI", "Django", "Docker", "gRPC", "Redis"]
        }

    def execute_pipeline(self, user_input: str) -> str:
        """Processes real-time audio/text through multi-agent DAGs & vector stores."""
        voice_stream = self.stt_convert(user_input)
        context = self.hybrid_rag_search(voice_stream, top_k=5)
        agent_action = self.langgraph_agent.reason(context)
        return self.tts_stream(agent_action)

    def say_hi(self) -> None:
        print("Salaam 👋! Welcome to my GitHub!")

me = GenerativeAIEngineer()
me.say_hi()
```

## 🚀 01 / FEATURED PROJECTS & SYSTEMS

<div align="center">

| SYSTEM / ARCHITECTURE                                                   |       CATEGORY & DOMAIN        | HIGHLIGHTS & METRICS                                                                                                 | STACK & LINKS                                                                                                          |
| :---------------------------------------------------------------------- | :----------------------------: | :------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------- |
| **🎙️ AI Dental Receptionist**<br>_Real-Time Conversational Voice Agent_ |    `VOICE AI`<br>`AGENTIC`     | • Sub-300ms speech latency<br>• Automated clinic scheduling<br>• `STT → LLM → Tools → TTS`                           | `Pipecat` `LangGraph`<br>`WebRTC` `ChromaDB`<br>[**Source Code**](https://github.com/muhammadtahanasir)                |
| **🚨 RescueAI**<br>_Emergency Response Intelligence Platform_           |  `AI / VOICE`<br>`LIVE DEMO`   | • Real-time emergency routing<br>• GPS-based SOS workflows<br>• Async microservice backend                           | `FastAPI` `React`<br>`Llama 3` `Twilio`<br>[**Live Demo**](https://rescueai-pakistan.vercel.app)                       |
| **🧠 DeepFoundry**<br>_Deep Learning Archive & PyTorch Masterclass_     |  `RESEARCH`<br>`OPEN SOURCE`   | • 18-week masterwork curriculum<br>• 98 standalone PyTorch modules<br>• First-principles proofs                      | `PyTorch` `Python`<br>`Torch-Geometric`<br>[**Explore Masterclass**](https://github.com/MuhammadTahaNasir/DeepFoundry) |
| **🔍 VeriFlow**<br>_Revenue Intelligence & Compliance Engine_           |    `ANALYTICS`<br>`FINTECH`    | • **$21M+ financial volume audited**<br>• **5,500+ transactions analyzed**<br>• **86 overcharge fraud cases caught** | `Python` `Pandas`<br>`Scikit-Learn` `FastAPI`<br>[**Source Code**](https://github.com/muhammadtahanasir)               |
| **⚡ ApexKV**<br>_High-Performance Key-Value Cache Engine_              |      `INFRA`<br>`SYSTEMS`      | • Multi-threaded TCP socket handling<br>• Redis-inspired architecture<br>• Write-Ahead Logging (WAL)                 | `Java` `TCP Sockets`<br>`TTL` `LRU Eviction`<br>[**Source Code**](https://github.com/muhammadtahanasir)                |
| **📡 Genetron**<br>_5G Base Station Placement Optimizer_                | `EVOLUTIONARY`<br>`ALGORITHMS` | • NSGA-II multi-objective AI<br>• Signal propagation modeling<br>• **99.4% simulated coverage**                      | `NSGA-II` `SciPy`<br>`FastAPI` `React`<br>[**Source Code**](https://github.com/muhammadtahanasir)                      |

</div>

## 🛠️ 02 / ENGINEERING TECH MATRIX

### Generative AI & Orchestration

<p>
  <img src="https://img.shields.io/badge/LangGraph-0F172A?style=flat-square&logo=python&logoColor=38BDF8" />
  <img src="https://img.shields.io/badge/LangChain-0F172A?style=flat-square&logo=chainlink&logoColor=38BDF8" />
  <img src="https://img.shields.io/badge/LlamaIndex-0F172A?style=flat-square&logo=meta&logoColor=38BDF8" />
  <img src="https://img.shields.io/badge/Pipecat_Voice_AI-0F172A?style=flat-square&logo=webrtc&logoColor=38BDF8" />
  <img src="https://img.shields.io/badge/ChromaDB-0F172A?style=flat-square&logo=database&logoColor=38BDF8" />
  <img src="https://img.shields.io/badge/Hybrid_RAG-0F172A?style=flat-square&logo=search&logoColor=38BDF8" />
  <img src="https://img.shields.io/badge/Multi_Agent_DAGs-0F172A?style=flat-square&logo=git&logoColor=38BDF8" />
</p>

### Core AI / ML Frameworks

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv&theme=dark" />
</p>
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" />
</p>

### High-Performance Backend & Databases

<p>
  <img src="https://skillicons.dev/icons?i=fastapi,django,postgres,mongodb,redis&theme=dark" />
</p>
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white" />
  <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" />
</p>

### Cloud, Containers & Web

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,docker,aws,git,github&theme=dark" />
</p>

## 🏆 03 / HONORS, LEADERSHIP & CAREER

<div align="center">

<table>
<tr>
<td align="center" width="25%">
  <h3>🌏 ICPC REGIONALIST</h3>
  <b>Ranked 86th in Asia</b><br>
  <code>GIKI 2024</code><br>
  <small>Top Algorithmic Performance</small>
</td>
<td align="center" width="25%">
  <h3>🥇 1ST PLACE WINNER</h3>
  <b>CodeJail Championship</b><br>
  <code>NaSCon · FAST-NUCES</code><br>
  <small>Intense Solo Arena Competition</small>
</td>
<td align="center" width="25%">
  <h3>🥉 3RD PLACE</h3>
  <b>FAST Problem Solving</b><br>
  <code>Competitive Programming</code><br>
  <small>Algorithmic Speed Optimization</small>
</td>
<td align="center" width="25%">
  <h3>🎓 96.04% TOP SCORE</h3>
  <b>GenAI Developer</b><br>
  <code>Application Developer</code><br>
  <small>Generative AI Distinction</small>
</td>
</tr>
</table>

</div>

- 🚀 **Voice AI Engineering Intern** @ **Verxeon** _(2026)_: Sub-300ms AI voice agents, `LangGraph` DAGs, Twilio & Google Calendar voice scheduling.
- 🛡️ **Enterprise Security Intern** @ **Central Depository Company of Pakistan** _(2026)_: Enterprise IAM governance, risk management & audit controls.
- 🔬 **Software Engineering Intern** @ **NUSyS Lab · FAST-NUCES** _(2026)_: Built Student Society Management Module for NUtomate digital platform.
- 💻 **Frontend Engineering Intern** @ **hwhelp.me** _(2025)_: Responsive UI components with HTML, CSS, JS, PHP & MySQL backend integration.
- 🤖 **AI/ML Engineering Intern** @ **Advtrix** _(2025)_: ML pipelines, K-Means customer segmentation (40% effort reduction) & `MLflow`.
- 🎓 **AI Software Engineering Fellow** @ **Headstarter AI** _(2024)_: Generative AI apps, RAG pipelines, FastAPI microservices & React.

### 📜 Key Certifications & Specializations

- 🏆 **Generative AI Application Developer** (NCEAC-HEC & ULEF - Top Score Distinction: 96.04%)
- 🧠 **Deep Learning Specialization** (DeepLearning.AI)
- 📊 **Machine Learning Specialization** (Coursera / Stanford University)
- 🇵🇰 **NAVTTC Artificial Intelligence Program** (Government of Pakistan)

## 📊 04 / GITHUB STATS & ACTIVITY ENGINE

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=muhammadtahanasir&show_icons=true&rank_icon=github&theme=tokyonight&hide_border=true" height="175" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=muhammadtahanasir&theme=tokyonight&hide_border=true" height="175" />
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammadtahanasir&layout=compact&theme=tokyonight&hide_border=true" />
</p>
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=muhammadtahanasir&theme=react-dark&hide_border=true" width="850px"/>
</div>

## 🌍 05 / CONNECT WITH ME

<div align="center">

<a href="https://muhammadtahanasir.github.io"><img src="https://img.shields.io/badge/PORTFOLIO-0F172A?style=for-the-badge&logo=googlechrome&logoColor=38BDF8"/></a>
<a href="https://www.linkedin.com/in/muhammadtahanasir"><img src="https://img.shields.io/badge/LINKEDIN-0F172A?style=for-the-badge&logo=linkedin&logoColor=38BDF8"/></a>
<a href="mailto:m.tahanasir.cs@gmail.com"><img src="https://img.shields.io/badge/EMAIL-0F172A?style=for-the-badge&logo=gmail&logoColor=38BDF8"/></a>
<a href="https://github.com/muhammadtahanasir"><img src="https://img.shields.io/badge/GITHUB-0F172A?style=for-the-badge&logo=github&logoColor=38BDF8"/></a>

</div>

## ✍️ 06 / QUOTE I LIVE BY

> _"The future belongs to those who learn more skills and combine them in creative ways."_ : Robert Greene

<div align="center">

<p align="center"><i>Made with 💻, ☕, and lots of curiosity in Karachi 🇵🇰</i></p>

</div>
