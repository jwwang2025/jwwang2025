<h1 align="center">Hi 👋, I'm <a href="https://github.com/jwwang2025">Jingwen Wang</a></h1>
<h3 align="center">💻 AI Application Development | AI Agent & RAG Specialist 🤠</h3>

<p align="center">
  📍 Beijing, China &nbsp;|&nbsp; 📧 jwwang_mail@163.com &nbsp;|&nbsp; 📱 +86 15290613394
</p>

<div align="center">

![snake](https://raw.githubusercontent.com/jwwang2025/jwwang2025/output/github-contribution-grid-snake.svg)
</div>

- 🔭 I'm currently pursuing my Master's degree at Beijing Institute of Technology, focusing on Knowledge Graph, RAG, and Multi-Agent Systems.
- 🌱 I'm currently learning LangGraph, ChromaDB, and advanced RAG techniques.
- 👯 I'm looking to collaborate on AI Agent and RAG projects.
- 💬 Ask me about AI Agents, RAG, Knowledge Graphs, and Python.
- 📫 How to reach me: jwwang_mail@163.com
- ⚡ Fun fact: Building intelligent systems that combine structured knowledge graphs with vector databases for enhanced reasoning.

<h3 align="left">Languages and Tools:</h3>

<table>
  <tr>
    <td><a href="https://www.python.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://www.java.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://pytorch.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://fastapi.tiangolo.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://reactjs.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://www.typescriptlang.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://www.w3.org/html"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://www.w3schools.com/css"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://git-scm.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://github.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://www.linux.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://code.visualstudio.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" width="40" height="40"/></a></td>
    <td><a href="https://www.docker.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="40" height="40"/></a></td>
  </tr>
</table>

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=jwwang2025&column=8&row=1)](https://github.com/jwwang2025)

</div>

---

[English](#english) | [中文](#中文)

---

<a id="english"></a>

## 🌟 About Me

I'm a passionate AI engineer with a strong background in **Knowledge Graph**, **RAG (Retrieval-Augmented Generation)**, and **Multi-Agent Systems**. Currently pursuing my Master's degree at Beijing Institute of Technology, I specialize in building intelligent systems that combine structured knowledge graphs with vector databases for enhanced information retrieval and reasoning.

---

## 🎓 Education

| Degree | Institution | Major | GPA | Ranking | Period |
|--------|-------------|-------|-----|---------|--------|
| Master | Beijing Institute of Technology | Computer Technology | - | - | Sep 2026 - Jun 2029 |
| Bachelor | Xinjiang University | Software Engineering | 3.93/5.0 | Top 4% (29/896) | Sep 2022 - Jun 2026 |

**Key Courses:** Java Programming (95), Web Programming (94), Database Principles & Technology (92), Data Structures (91)

---

## 🚀 Projects

### ResearchSync-Agent: Intelligent Multi-Agent Research Assistant

**Dec 2025 - Present**

A cutting-edge intelligent research assistant system based on LangGraph multi-agent framework, enabling automatic workflow from research planning, information collection to report generation.

**Tech Stack:** LangGraph, LangChain, Multi-Agent, FastAPI, WebSocket, React, ChromaDB, RAG

**Key Achievements:**

- **Hybrid Memory Design:** Implemented short-term (session-level LRU via SessionMemory) + long-term (ChromaDB vector storage) memory architecture with automated sliding window management and knowledge reuse mechanisms
- **Multi-agent Collaboration:** Designed four core agents - Coordinator (task decomposition & scheduling), Planner (VectorMemory-based hierarchical planning), Researcher (multi-source information retrieval), Rapporteur (structured report generation)
- **Memory Integration:** Developed adaptive memory integration mechanism, persisting high-importance information (>0.7) to vector databases with TTL and LRU eviction strategies
- **Multi-source Retrieval:** Integrated Tavily Search, arXiv Academic, MCP protocol; unified retrieval interface combining RAG vector search for enhanced information acquisition
- **Multi-source Fusion:** Implemented multi-source retrieval result re-ranking and relevance scoring
- **LLM Integration:** Factory pattern supporting multiple LLM providers (DeepSeek, etc.) with runtime dynamic switching, token limiting configuration

### KnowledgeGraph-RAG: Knowledge Graph-Enhanced RAG System

**Jan 2026 - Present**

Designed and implemented a RAG system based on knowledge graph bi-tower generation, innovatively combining knowledge graphs with vector databases for dual-source retrieval.

**Tech Stack:** LangChain, ChromaDB, PyTorch, CoT, ChatGLM-6B, RRF, Cohere

**Key Achievements:**

- **Knowledge Graph Construction:** Based on PaddleNLP UIE entity extraction, SPN4RE relation triplet extraction; achieved end-to-end automatic knowledge graph construction from raw text
- **Bi-tower Indexing:** Built bi-tower indexing architecture - Omen3-Embedding text encoder + Multi-representation multi-vector technology; three-layer hierarchical vector indexing persisted in ChromaDB
- **Adaptive RAG Strategy:** Adopted Adaptive-RAG thinking, QueryRouter dynamically classifies question types and plans retrieval strategies; RetrievalDecider executes multi-path parallel retrieval with dynamic resource allocation for multi-turn Q&A
- **Multi-vector Optimization:** RRF fusion algorithm for multi-vector retrieval result combination; Cohere re-ranking for fine-grained semantic discrimination; Self-RAG evaluator for relevance scoring and quality filtering
- **Reasoning Enhancement:** CoT thinking chain module supporting three reasoning modes; Prompt construction guiding LLM multi-step reasoning; Citation linking generator with citation labels

---

## 💡 Technical Skills

| Category | Skills |
|----------|--------|
| **Programming** | Python (Proficient), Java, Data Structures, Algorithms |
| **RAG** | RAG Principles, Indexing, Retrieval, Generation, Optimization |
| **Agent** | Core Components (LLM+Planning+Memory+Function), React, Reflexion Patterns |
| **Languages** | CET-4 (450), CET-6 (442), English technical documentation |
| **Tools** | Cursor AI Engineering Tool |

---

## 📊 GitHub Stats

![Jingwen's GitHub stats](https://github-readme-stats.vercel.app/api?username=jwwang2025&show_icons=true&theme=dark)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jwwang2025&layout=compact&theme=dark)

---

## 📬 Contact

- **Email:** jwwang_mail@163.com
- **Phone:** +86 15290613394
- **Location:** Beijing, China

---

---

<a id="中文"></a>

# 王敬文

**AI应用开发 | AI Agent & RAG专家**

📍 中国北京 | 📧 jwwang_mail@163.com | 📱 +86 15290613394

---

## 🌟 关于我

我是一名充满热情的AI工程师，拥有扎实的**知识图谱**、**RAG（检索增强生成）**和**多智能体系统**背景。目前在北京理工大学攻读硕士学位，专注于构建结合结构化知识图谱与向量数据库的智能系统，以实现更高效的信息检索和推理能力。

---

## 🎓 教育背景

| 学位 | 院校 | 专业 | 时间 |
|--------|-------------|-------|-----|---------|--------|
| 硕士 | 北京理工大学 | 计算机技术 | 2026.09 - 2029.06 |
| 本科 | 新疆大学 | 软件工程 | 2022.09 - 2026.06 |

---

## 🚀 项目经历

### ResearchSync-Agent——智能多智能体研究助手

**2025.12 - 至今**

一个基于LangGraph多智能体架构的智能研究助手系统，通过Coordinator、Planner、Researcher、Rapporteur四个AI智能体的协作，自动完成从研究规划、信息检索到报告生成的全流程。

**技术栈：** LangGraph、LangChain、Multi-Agent、FastAPI、WebSocket、React、ChromaDB、RAG

**项目实现：**

1. **架构设计：** 设计并实现"短期缓存+长期向量检索"的混合记忆架构，通过SessionMemory（会话级LRU缓存）与VectorMemory（基于Chroma向量库）的双层构件智能体协作系统，Coordinator负责请求管理和会话知识复用。

2. **多智能体协作：** 基于LangGraph框架搭建四层构件智能体协作系统，Coordinator负责请求管理和会话知识复用，Planner生成研究计划并支持人工审批，Researcher执行多源信息检索，Rapporteur整合结果生成结构化报告。

3. **记忆整合：** 实现会话结束时的自适应记忆整合机制，提取高重要性条目（importance>0.7）持久化到向量数据库，结合TTL（生存时间）和LRU（最近最少使用）混合淘汰策略实现多特征自动淘汰与清理。

4. **多源检索：** 集成Tavily搜索、ArXiv学术文献、MCP协议等多种数据源，构建统一的检索接口，结合RAG向量检索增强信息获取能力，支持检索结果的去重与相关性排序。

5. **多源融合：** 实现多源检索结果的重排序与相关性排序

6. **LLM管理：** 通过工厂模式封装多种LLM提供商（DeepSeek等），支持运行时动态切换LLM和token限制等参数配置

### KnowledgeGraph-RAG——基于知识图谱增强的智能问答系统（RAG）

**2026.01 - 至今**

设计和实现了一个基于检索增强生成（RAG）的智能问答系统，创新性地融合知识图谱与向量数据库进行双源检索，结合自适应路由策略和思维链推理，为用户提供精准、可溯源的专业问答服务。

**技术栈：** LangChain、ChromaDB、PyTorch、CoT、ChatGLM-6B、RRF、Cohere

**项目实现：**

1. **知识图谱构建：** 基于PaddleNLP UIE实现自动化命名实体识别，采用SPN4RE模型进行关系三元组抽取，构建结构化知识网络，实现了从原始文本到图谱的端到端自动化构建流程。

2. **双塔索引建立：** 基于Omen3-Embedding的端到端自动化构建流程，采用Multi-representation多表征技术，对知识图谱构建阶段处理后的结构化数据进行向量化，构建三级层级向量索引，并持久化存储于ChromaDB向量数据库中。

3. **自适应检索架构：** 采用Adaptive-RAG思想，通过QueryRouter问题路由模块自动分类问题类型并规划检索策略，由RetrievalDecider执行多路径并行检索，动态分配知识源优先级，实现问题驱动的智能检索路由。

4. **多轮检索优化：** 实现RRF融合算法，对多源检索结果进行智能合并与去重；集成Cohere语义重排序，对融合结果进行精确的语义级别排序优化；引入Self-RAG评估机制，对检索结果进行相关性评估与质量打分，自动过滤低质量内容。

5. **推理增强与溯源：** 设计CoT思维链推理模块，支持三种推理模式，将思维链融入Prompt构建，引导大模型进行多步推理；实现Citation引用溯源机制，自动生成回答中的引用标注，确保每个回答都有据可查。

---

## 💡 专业技能

| 类别 | 技能 |
|----------|--------|
| **编程开发** | 熟练Python、Java语言特性，熟悉常见库，具有良好的数据结构和算法基础，能够编写规范的程序代码 |
| **RAG** | 熟悉RAG原理及流程，了解Indexing、Retrieval、Generation等关键部分的优化技术，了解提示词工程 |
| **Agent** | 熟悉Agent核心部分(LLM+Planning+Memory+Function)，熟悉React、Reflexion等常见架构模式 |
| **英语能力** | 通过四六级，CET-4: 450, CET-6: 442，能够阅读英文项目文档；能够使用Cursor等AI编程工具进行辅助开发 |

---

## 📊 GitHub统计

![王敬文的GitHub统计](https://github-readme-stats.vercel.app/api?username=jwwang2025&show_icons=true&theme=dark)

![主要语言](https://github-readme-stats.vercel.app/api/top-langs/?username=jwwang2025&layout=compact&theme=dark)

---

## 📬 联系方式

- **邮箱:** jwwang_mail@163.com
- **电话:** +86 15290613394
- **所在地:** 中国北京

---

*Built with passion for AI and technology 🔥*
