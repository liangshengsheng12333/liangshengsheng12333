<div align="center">

<!-- 顶部动态渐变横幅 -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:3b82f6&height=205&section=header&text=Liang%20Sheng%20%C2%B7%20%E5%87%89%E7%AC%99&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineering%20Student%20%7C%20AI-Assisted%20Developer%20%7C%20Open%20Source%20Learner&descAlignY=62&descSize=15" width="100%" />

<!-- 动态打字机 -->
<a href="https://github.com/liangshengsheng12333">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&duration=3000&pause=1200&color=3B82F6&center=true&vCenter=true&width=820&lines=Software+Engineering+Undergraduate+%40+TUST;Open+Source+Contributor+%7C+openKylin+SIG+163+(Oak+Video+Editor);AI-Assisted+Engineering+%7C+Test-Driven+%26+Rigorous+Verification;Exploring+Computer+Systems+(408)+%26+Interactive+Web" alt="Typing SVG" />
</a>

<p align="center">
  <a href="mailto:liangshengsheng06@gmail.com"><img src="https://img.shields.io/badge/Email-liangshengsheng06%40gmail.com-2563EB?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/liangshengsheng12333?tab=repositories"><img src="https://img.shields.io/badge/Repositories-Browse%20All-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repos" /></a>
  <img src="https://img.shields.io/badge/Affiliation-TUST%20SE%20'25-0284C7?style=for-the-badge" alt="Affiliation" />
  <img src="https://img.shields.io/badge/Open%20Source-openKylin%20SIG%20163-10B981?style=for-the-badge" alt="Open Source" />
  <img src="https://img.shields.io/badge/Location-Tianjin%2C%20China-059669?style=for-the-badge" alt="Location" />
</p>

</div>

---

### 👨‍💻 个人简介 (About Me)

你好，我是**任潇宇（凉笙）**，目前是天津科技大学 2025 级软件工程本科在读学生。

在学习与开发路径上，我坚持**“计算机底层理论（面向 408）夯实 + 现代 AI 协同敏捷开发（AI-Assisted / Vibe Coding）”**的双轨模式：
- **善用工具，但不做黑盒搬运工**：坚守**“AI 辅助生成的每一行代码，自己必须逐行彻底理解底层逻辑与语法”**的开发底线。
- **重规范与测试先行**：擅长将模糊需求转化为严谨的**产品需求规范（PRD）**与**接口契约**，习惯以**表驱动单元测试（Unit Testing）**与回归验证把控代码质量。
- **在实践中磨砺基础**：积极参与真实开源社区（openKylin SIG 163）与大学创新实践，从单元测试、边界防范与外围生态切入，逐步加深对系统级软件与现代工程协作的理解。

---

### 🏆 核心实践与开源项目 (Projects & Contributions)

#### 1. 🎬 开源多媒体社区贡献 ·《Oak Video Editor》(openKylin SIG 163)
> **涉及技术**：`Rust (学习与单测实践)` · `表驱动测试` · `浮点数边界防御` · `社区 PR 协同`  
> **个人归档**：[liangshengsheng12333/oak-contributions](https://github.com/liangshengsheng12333/oak-contributions) · **上游仓库**：[OakVideoEditorCommunity/oak](https://github.com/OakVideoEditorCommunity/oak)

- **社区背景**：Oak 是一款基于 Olive 用 Rust 重写的现代化开源非线性视频剪辑软件，由天科大开源俱乐部核心学长主导并入驻 openKylin 官方 SIG 163。
- **我的贡献（Issue #83 / PR #89）**：作为初入组的 Contributor，从 Good First Issue 切入。针对示波器底层数学计算（`oak-app::scopes::math`），排查并解决了极端 HDR 异常数据或插件导致的 `NaN` / `±Inf` 无法被 `.clamp()` 截断的数值漏洞；编写了五重防御逻辑并补充 4 组极端边界表驱动单元测试（10/10 通过），确保不破坏正常像素渲染。
- **实践收获**：深入理解了 IEEE 754 浮点数特异值、Rust 模式匹配安全机制以及大型开源项目的标准 Fork-Branch-PR 协作流。

---

#### 2. 🍽️ 校园多目标就餐规划 ·《天科食客》(Tianke Canteen Planner)
> **涉及技术**：`C++20` · `WebAssembly` · `微信小程序` · `动态规划与剪枝`  
> **开源仓库**：[liangshengsheng12333/tianke-canteen-planner](https://github.com/liangshengsheng12333/tianke-canteen-planner)

- **项目定位**：大一阶段针对西院食堂多档口菜品研发的端侧离线就餐规划小程序原型，解决预算与营养多目标权衡问题。
- **工程实现**：为避免服务器运维成本，采用 C++20 编写求解算法并编译为 WebAssembly 部署于小程序前端离线推演。
- **算法调优实践**：在 AI 协同开发中针对高维状态组合爆炸问题进行定向攻坚：通过**网格状态桶（Grid-Bucketized DP）**与**分支限界（Branch & Bound）剪枝**优化搜索空间，将初版高延迟大幅压缩至数十毫秒，并编写了覆盖 2 万余次状态的回归验证用例。

---

#### 3. 🎙️ 智能交互语音系统协作 ·《LingoCue》(华北五省计算机应用大赛)
> **涉及技术**：`Android / Kotlin` · `sherpa-onnx (端侧 ASR)` · `3D-Speaker (声纹)` · `LLM 异步复核`  
> **团队角色**：系统原型构建、后端接口协同与测试验证 · 天津科技大学 TTQ 团队

- **项目定位**：面向跨境交流真实场景的轻量交互辅助系统，探索在智能终端及轻量 AR 设备上的无感提示形态。
- **协作分工**：参与端侧开源语音识别引擎（sherpa-onnx）与声纹特征聚合接口联调；负责多源意图锚定逻辑的测试验证，确保外部大模型建议句式时不偏离用户原本核心意图。

---

#### 4. 🎨 传统非遗数字化 Web 交互 ·《津彩入画》(Jincai Ruhua)
> **涉及技术**：`HTML5 Canvas` · `TypeScript / JavaScript` · `Web Audio API`  
> **开源仓库**：[liangshengsheng12333/jincai-ruhua](https://github.com/liangshengsheng12333/jincai-ruhua)

- **项目定位**：国家级非遗“天津杨柳青木版年画”的数字化互动体验网站，通过现代 Web 技术降低传统文化传播门槛。
- **核心实现**：利用 Canvas 多图层叠加模拟传统套印流程；结合按压音效与自选调色板，在浏览器免安装环境下还原“选稿、套印、彩绘、钤印”四道手工交互流程。

---

#### 5. 🤖 规范化 AI 辅助开发套件 · Agent Skills 体系
> **涉及技术**：`Python 3.10+` · `自动化回归测试 (Pytest)` · `API 联调` · `工作流编排`  
> **开源仓库**：[humanities-writing](https://github.com/liangshengsheng12333/humanities-writing) · [liangsheng-workflow](https://github.com/liangshengsheng12333/liangsheng-workflow-friend)

- **工程化探索**：为了避免 AI 辅助编码过程中的“幻觉”与无序发散，编写并固化了一批工程规则与自动化测试套件。
- **严格测试守门**：在辅助写作与文献检索工具中嵌入 27 项自动化用例，用代码逻辑与门禁脚本对大语言模型输出进行格式和事实约束。

---

### 🛠️ 技术积累与工具掌握 (Skills & Tooling)

> 💡 *以实事求是为准绳：标注清晰真实掌握层级，拒绝虚标堆砌。*

<div align="center">

| 维度 | 掌握情况与主要实践领域 |
| :--- | :--- |
| **编程语言 (Languages)** | **C / C++**（数据结构与课业基础，掌握基本指针与面向对象）<br>**Python**（数据脚本、API 联调与自动化测试）<br>**TypeScript / JavaScript**（现代前端与 Canvas 交互开发）<br>**Rust**（*学习与实践中*，能读懂基础代码、编写单元测试与边界补丁） |
| **工程协同与测试 (Engineering)** | **Git & GitHub**（熟练的分支管理、PR 提交与 Issue 追踪规范）<br>**测试驱动思想**（表驱动测试、极端边界测试、回归测试集设计）<br>**需求契约梳理**（PRD 编写、接口边界对齐、工程文档撰写） |
| **现代开发方法 (AI-Assisted)** | **Vibe Coding 敏捷实践**（结合 Cursor / AI 工具链加速原型开发）<br>**代码审计与可解释性**（坚持对 AI 生成的逻辑逐行推演验证） |
| **基础理论在学 (408 Focus)** | **数据结构与算法** · **计算机组成原理** · **操作系统**（持续深化中） |

</div>

---

### 📦 个人公开仓库目录 (Repositories Directory)

| 仓库名称 | 领域分类 | 真实定位与技术内容 |
| :--- | :--- | :--- |
| 🎬 **[oak-contributions](https://github.com/liangshengsheng12333/oak-contributions)** | 开源多媒体 / Rust | openKylin SIG 163 个人贡献追踪归档。收录 Issue #83 浮点数边界防御及 PR #89 单元测试集。 |
| 🍽️ **[tianke-canteen-planner](https://github.com/liangshengsheng12333/tianke-canteen-planner)** | C++20 / WebAssembly | 校园离线就餐规划小程序核心。C++ 动态规划算法调优及 2 万次状态回归测试集。 |
| ✍️ **[humanities-writing](https://github.com/liangshengsheng12333/humanities-writing)** | Python / 规范化 Agent | 面向学术写作的 AI 约束技能库。配置 27 项自动化单测与离线审校脚本。 |
| 🎨 **[jincai-ruhua](https://github.com/liangshengsheng12333/jincai-ruhua)** | HTML5 Canvas / 前端 | 杨柳青木版年画数字化交互工坊，纯前端 Canvas 多图层印压交互实现。 |
| 🎭 **[liangsheng-workflow](https://github.com/liangshengsheng12333/liangsheng-workflow-friend)** | 敏捷研发流程模板 | 规范个人与 AI 协同的结构化任务拆解与上下文状态流转模版。 |
| 🎯 **[career-planning-contest](https://github.com/liangshengsheng12333/career-planning-contest)** | Python 数据处理 | 职业规划大赛参赛素材整理与辅助分析脚本。 |
| 🧠 **[obsidian-codex-starter](https://github.com/liangshengsheng12333/obsidian-codex-knowledge-base-starter)** | 个人知识管理 (PKM) | 极简双链知识库架构模板，用于沉淀 408 理论与工程学习笔记。 |
| 🎥 **[oak](https://github.com/liangshengsheng12333/oak)** | 上游同步 Fork | 保持与 OakVideoEditorCommunity 上游社区同步的日常开发分支。 |

---

### 🤝 交流与联系 (Contact)

我非常欢迎师长、开源社区前辈及同学们在**算法逻辑实践、跨平台轻量应用、现代 AI 协同开发工作流**等方向交流指导：

- **GitHub**: [@liangshengsheng12333](https://github.com/liangshengsheng12333)
- **Email**: [liangshengsheng06@gmail.com](mailto:liangshengsheng06@gmail.com)
- **院校信息**: 天津科技大学 · 软件工程专业 (TUST SE)

---

# 🌍 English Summary

<details open>
<summary><b>Read in English</b></summary>

<br/>

**Liang Sheng (任潇宇)** is an undergraduate software engineering student (Class of 2025) at Tianjin University of Science and Technology (TUST), China. 

He adopts an **AI-assisted engineering workflow (Vibe Coding)** grounded in rigorous engineering practices:
- **Understand Every Line**: Strictly adheres to fully verifying and understanding every line of AI-assisted code before committing.
- **Specification & Test-Driven**: Focuses on clarifying PRDs, interface contracts, and authoring table-driven unit test suites to guarantee code stability.
- **Open Source Learner**: Active contributor to **Oak Video Editor** (openKylin SIG 163), starting from numerical safety hardening and unit testing in Rust.

### Key Projects
- **[oak-contributions](https://github.com/liangshengsheng12333/oak-contributions)**: Open-source contributions to Oak Video Editor. Authored **[PR #89](https://github.com/OakVideoEditorCommunity/oak/pull/89)** fixing non-finite (`NaN` / `±Inf`) sample propagation in scopes math routines with full unit tests.
- **[tianke-canteen-planner](https://github.com/liangshengsheng12333/tianke-canteen-planner)**: Client-side offline meal optimization engine in C++20 / WebAssembly for WeChat MiniProgram with 20k regression test cases.
- **[humanities-writing](https://github.com/liangshengsheng12333/humanities-writing)**: Rule-based verification skill with 27 automated integration tests constraining LLM hallucinations.
- **[jincai-ruhua](https://github.com/liangshengsheng12333/jincai-ruhua)**: Interactive HTML5 Canvas interactive preservation project for traditional Chinese intangible cultural heritage (Yangliuqing Woodblock Printing).

Always eager to learn from mentors and community developers in systems fundamentals (408), test automation, and pragmatic developer workflows.

</details>

---

### 📊 数据看板 (Live Metrics)

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=liangshengsheng12333&theme=tokyonight" width="96%" alt="Profile Summary Details" />
  <br/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=liangshengsheng12333&theme=tokyonight" width="47%" alt="GitHub Stats" />
  <img src="https://streak-stats.demolab.com?user=liangshengsheng12333&theme=tokyonight&hide_border=true" width="47%" alt="GitHub Streak" />
  <br/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=liangshengsheng12333&theme=tokyonight" width="47%" alt="Repos Per Language" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=liangshengsheng12333&theme=tokyonight&utcOffset=8" width="47%" alt="Productive Time" />
</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3b82f6,50:1e3a8a,100:0f172a&height=110&section=footer" width="100%" />
  <sub>Engineering with Precision & Honesty · Liang Sheng (凉笙) · TUST</sub>
</div>
