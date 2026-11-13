<div align="center">

<!-- 顶部动态渐变横幅 -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:3b82f6&height=205&section=header&text=Liang%20Sheng%20%C2%B7%20%E5%87%89%E7%AC%99&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20Interactive%20System%20Builder%20%7C%20Indie%20Game%20Dev&descAlignY=62&descSize=15" width="100%" />

<!-- 动态打字机 -->
<a href="https://github.com/liangshengsheng12333">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&duration=3000&pause=1200&color=3B82F6&center=true&vCenter=true&width=780&lines=Software+Engineer+%7C+C%2B%2B20+%2F+WebAssembly+%2F+Python+%2F+TypeScript;Indie+Game+Developer+%7C+Building+STARBREAK;Applied+AI+Engineering+%7C+Agent+Skills+%26+Developer+Workflows" alt="Typing SVG" />
</a>

<p align="center">
  <a href="mailto:liangshengsheng06@gmail.com"><img src="https://img.shields.io/badge/Email-liangshengsheng06%40gmail.com-2563EB?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/liangshengsheng12333?tab=repositories"><img src="https://img.shields.io/badge/Repositories-Browse%20All-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repos" /></a>
  <img src="https://img.shields.io/badge/Affiliation-TUST%20CS-0284C7?style=for-the-badge" alt="Affiliation" />
  <img src="https://img.shields.io/badge/Location-Tianjin%2C%20China-059669?style=for-the-badge" alt="Location" />
</p>

</div>

---

### 👨‍💻 个人简介 (Profile Summary)

专注于系统工程、算法优化、现代 Web 交互及 AI 工程化落地。在高性能计算（C++20 / WebAssembly）、原创独立游戏架构、前沿 Web 交互应用以及多智能体（Agent Skills）确定性工具链开发领域拥有多项完整落地项目经验。

注重代码工程质量、模块化解耦与可量化的性能指标，坚持以工程规范与自动化测试驱动交付。

---

### 🏆 核心项目与研发成果 (Featured Projects)

#### 1. 🍽️ 校园离线算法系统 ·《天科食客》(Tianke Canteen Planner)
> **技术栈**：`C++20` · `WebAssembly (Emscripten)` · `WeChat MiniProgram` · `CMake/Clang`  
> **开源仓库**：[liangshengsheng12333/tianke-canteen-planner](https://github.com/liangshengsheng12333/tianke-canteen-planner)

- **业务背景**：针对我校西院食堂多档口复杂餐品，解决学生在预算受限条件下的多目标营养均衡规划痛点。
- **架构创新**：摒弃传统中心化服务器架构，采用纯 **C++20** 构建多维离线求解内核，编译为 **WebAssembly** 嵌入微信客户端沙箱离线推演，实现零云端运维成本与端侧瞬时响应。
- **性能攻坚**：面对高维状态空间爆炸问题（初版求解卡顿耗时 23.46 秒），主导重构算法引擎：设计**网格状态桶（Grid-Bucketized DP）**并结合**分支限界剪枝（Branch & Bound）**，将极端算力场景下的求解延迟大幅压缩至 **71 毫秒（提速 330.4 倍）**，并在工程内固化 2.1 万次跨状态回归测试集。

---

#### 2. 🎙️ 智能终端与端侧语音系统 ·《LingoCue》(华北五省计算机应用大赛作品)
> **技术栈**：`Android / Kotlin` · `sherpa-onnx (端侧流式 ASR)` · `3D-Speaker (声纹辨识)` · `LLM 异步复核` · `AR/智能眼镜前沿交互`  
> **团队角色**：系统架构与核心后端协作 · 天津科技大学 TTQ 团队

- **项目定位**：面向跨境交流与外语学习真实场景构建的“即时理解 → 动态表达 → 持续复练”三位一体智能交互辅助系统，探索轻量级 AR / 智能眼镜前台沉浸式辅助形态。
- **混合 ASR 与双轨纠偏机制**：端侧基于开源 **sherpa-onnx** 实现毫秒级离线流式出字，同步引入 **3D-Speaker 声纹特征聚类**实现本人与对方说话人自适应区分；云端通过异步 LLM API 执行语义级纠偏，攻破噪声环境下的识别断裂痛点。
- **语义锚定与意图不变性**：提出基于严格语义锚定的 A/B/C 三重表达梯度生成方案，在确保用户原始交流意图不变的前提下提供地道句式建议，配合悬浮窗即时点读与本地生词库无感沉淀，形成长效学习闭环。

---

#### 3. 🎨 创意 Web 与数字非遗交互 ·《津彩入画》(Jincai Ruhua)
> **技术栈**：`HTML5 Canvas` · `TypeScript / JavaScript` · `Web Audio API` · `响应式现代 Web`  
> **开源仓库**：[liangshengsheng12333/jincai-ruhua](https://github.com/liangshengsheng12333/jincai-ruhua)

- **项目定位**：将首批国家级非物质文化遗产“天津杨柳青木版年画”进行数字化活化的高品质 Web 交互创作站点。
- **图形渲染管线**：摒弃扁平模板，利用 **HTML5 Canvas** 自研多图层叠加渲染引擎，完整数字化复刻杨柳青年画“勾描选稿、刻版套印、人工彩绘、落款钤印”四大传统手工流程。
- **细腻交互人机工效**：结合 Web Audio 声效仿真、印压物理回弹动效与自定义调色系统，使来访者无需安装插件即可在浏览器端沉浸式体验传统非遗技艺，兼顾文化传承与现代 Web 交互美学。

---

#### 4. 🎮 原创独立游戏研发 ·《碎星：绝响》(STARBREAK: The Final Resonance)
> **技术栈**：`C++ / 游戏引擎` · `分层有限状态机 (HFSM)` · `数值仿真系统` · `物理与打击感判定`  
> **研发状态**：核心玩法原型迭代中（私有仓库持续集成）

- **项目定位**：个人独立主导推进的原创科幻动作独立游戏，全权负责底层架构、战斗交互手感、数值系统与世界观叙事设计。
- **战斗与状态机架构**：设计严密的分层有限状态机（HFSM）驱动角色动作、受击定格（Hitstop）、霸体判定与帧同步输入缓存，确保动作反馈精准硬核。
- **数值与闭环平衡**：建立模块化数值配置与推演脚本，针对角色成长曲线、精力消耗与敌人 AI 行为树进行系统性推演验证，专注于打造具备高可玩性与扎实操作反馈的完整独立作品。

---

#### 5. 🤖 规范化 AI 工程工具链 · Agent Skills 体系
> **技术栈**：`Python 3.10+` · `Pytest / 自动化集成测试` · `OpenAlex / CNKI API` · `Multi-Agent Workflow`  
> **开源仓库**：[humanities-writing](https://github.com/liangshengsheng12333/humanities-writing) · [liangsheng-workflow](https://github.com/liangshengsheng12333/liangsheng-workflow-friend) · [liangsheng-theater](https://github.com/liangshengsheng12333/liangsheng-theater)

- **《人文写作与学术论证》技能套件**：拒绝不可控的黑盒 Prompting，使用软件工程手段硬性约束大模型输出。集成 **27 项自动化集成测试**、Python 离线保守审校脚本及学术文献多源检校接口，彻底杜绝引文虚构与套话生成。
- **《凉笙工作流》与《凉笙歌剧院》**：面向工程研发协作构建的多智能体角色调度架构，实现结构化需求确认（PRD）、任务拓扑依赖派发与进度断点恢复。

---

### 🛠️ 技术栈与工具矩阵 (Skills Matrix)

<div align="center">

| 技术领域 | 核心语言、框架与环境 |
| :--- | :--- |
| **底层系统与高性能计算** | ![C++20](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **客户端与现代 Web 开发** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![HTML5 Canvas](https://img.shields.io/badge/HTML5%20Canvas-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![WeChat MiniProgram](https://img.shields.io/badge/微信小程序-07C160?style=flat-square&logo=wechat&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) |
| **工程构建、工具与测试** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Clang/MSVC](https://img.shields.io/badge/Clang%20/%20MSVC-262B30?style=flat-square) ![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white) ![Pytest](https://img.shields.io/badge/Pytest%20/%20CI-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) |
| **智能应用与工程知识体系** | ![sherpa-onnx](https://img.shields.io/badge/sherpa--onnx-FF6B6B?style=flat-square) ![Agent Skills](https://img.shields.io/badge/Agent%20Skills-0EA5E9?style=flat-square) ![Obsidian PKM](https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white) |

</div>

---

### 📦 核心公开仓库速览 (Repositories Directory)

| 仓库名称 | 领域分类 | 核心特性与技术指标 |
| :--- | :--- | :--- |
| 🍽️ **[tianke-canteen-planner](https://github.com/liangshengsheng12333/tianke-canteen-planner)** | C++20 / WASM | 客户端离线多约束膳食优化系统。网格动态规划与剪枝优化，求解延迟由 23.46 秒降至 71 毫秒（提速 330 倍）。 |
| ✍️ **[humanities-writing](https://github.com/liangshengsheng12333/humanities-writing)** | Agent Skill / Python | 学术论证与文本规范 AI 技能套件。配备 27 项自动化集成测试、离线保守审校脚本及知网/OpenAlex 学术文献多源检索。 |
| 🎨 **[jincai-ruhua](https://github.com/liangshengsheng12333/jincai-ruhua)** | HTML5 Canvas | 天津杨柳青木版年画数字化交互体验网站。在浏览器端完整还原选稿、套印、彩绘与钤印全工序。 |
| 🎭 **[liangsheng-theater](https://github.com/liangshengsheng12333/liangsheng-theater) & [workflow](https://github.com/liangshengsheng12333/liangsheng-workflow-friend)** | AI 工作流规范 | 面向软件研发的多智能体协作框架。实现需求确认、任务拆解与上下文管理的确定性流转。 |
| 🎯 **[career-planning-contest](https://github.com/liangshengsheng12333/career-planning-contest)** | Python 数据分析 | 大学生职业规划大赛辅助材料量化分析与评估工具脚本。 |
| 🧠 **[obsidian-codex-starter](https://github.com/liangshengsheng12333/obsidian-codex-knowledge-base-starter)** | PKM 知识架构 | 借鉴 Andrej Karpathy 个人知识库理念构建的极简模板，面向高密度技术积累与本地 AI 协同。 |
| 🎙️ **LingoCue (比赛作品)** | 智能交互 Android/AR | 华北五省计算机应用大赛参赛作品，基于 sherpa-onnx 与 3D-Speaker 声纹辨识的智能交流辅助系统。 |
| 🌌 **STARBREAK: The Final Resonance** *(研发中)* | 原创独立游戏 | 原创科幻题材独立游戏作品，正在私有仓库进行核心状态机与战斗机制原型迭代。 |

---

### 🤝 开源理念与社区合作 (Community & Connect)

持续致力于将实践中验证有效的工程方案与工具链开源共享，注重清晰的文档规范、可复现的基准测试与长期的代码维护。

欢迎开源社区同行、指导教师及技术开发者在**高性能系统架构、游戏开发工程、创意 Web 交互或端侧 AI 规范化工具链**等方向交流与协作。
- **GitHub**: [@liangshengsheng12333](https://github.com/liangshengsheng12333)
- **Email**: [liangshengsheng06@gmail.com](mailto:liangshengsheng06@gmail.com)
- **Institution**: Tianjin University of Science and Technology (TUST)

---

# 🌍 English Overview

<details open>
<summary><b>Read in English</b></summary>

<br/>

**Liang Sheng (凉笙)** is a software engineer and computer science student at Tianjin University of Science and Technology (TUST), China. His engineering work spans high-performance systems, algorithm optimization, interactive Web graphics, and deterministic on-device AI workflows.

He was a core developer on competition projects including the **North China Five Provinces Computer Application & Design Competition** (Mobile Internet Innovation Track) and the **National College Career Planning Competition**.

- **Systems & Performance Engineering**: Architected **[Tianke Canteen Planner](https://github.com/liangshengsheng12333/tianke-canteen-planner)**, a client-side multi-constraint meal solver implemented in **C++20** and compiled to **WebAssembly** for WeChat MiniProgram. Re-engineered the dynamic programming algorithm using grid-bucketized states and branch-and-bound pruning, reducing solve latency from **23.46s to 71ms (330x speedup)** with 21k regression test cases.
- **On-Device Speech & Smart Interfaces**: Co-developed **LingoCue** for the North China Computer Competition, an intelligent communication assistance system featuring on-device streaming ASR (**sherpa-onnx**), acoustic speaker verification (**3D-Speaker**), semantic intention anchoring, and lightweight AR/smart glasses interface design.
- **Creative Web & Interactive UX**: Dedicated to rich interactive graphics over boilerplate forms. Created **[Jincai Ruhua](https://github.com/liangshengsheng12333/jincai-ruhua)**, implementing an HTML5 Canvas interactive multi-stage rendering pipeline for traditional Chinese Yangliuqing woodblock printmaking.
- **Indie Game Development**: Solo developer of ***STARBREAK: The Final Resonance***, an original sci-fi action indie game project currently in private prototype iteration covering hierarchical finite state machines (HFSM), combat feel, and numerical balancing.
- **Applied AI & Agent Toolchains**: Open-sourced **[humanities-writing](https://github.com/liangshengsheng12333/humanities-writing)** (backed by 27 automated integration tests, conservative review scripts, and CNKI/OpenAlex citation lookup), **[Liangsheng Opera House](https://github.com/liangshengsheng12333/liangsheng-theater)**, and **[Liangsheng Workflow](https://github.com/liangshengsheng12333/liangsheng-workflow-friend)**.

Always open to technical discussions and collaboration across systems optimization, game engineering, and robust developer tooling.

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
  <sub>Engineering with Precision · Liang Sheng (凉笙) · TUST</sub>
</div>
