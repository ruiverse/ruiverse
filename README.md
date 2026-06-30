# Hi, I'm Ruiverse 👋

**遥感AI算法 / 图像算法 / 智能驾驶感知 / AI Agent 应用**
**Remote Sensing AI · Computer Vision · Autonomous Driving Perception · AI Agent Development**

中科院国家空间科学中心 · 硕士在读（保研）· 2027届
M.S. Student, National Space Science Center, Chinese Academy of Sciences (2027)

📍 北京 · 可京津冀 / 江浙沪 / 川渝 | Beijing · Open to relocation
📫 yangruixiaoio@163.com

---

## About Me

硕士课题围绕**月球遥感与反射光谱学**展开，独立搭建自动化光谱测量系统，累计采集万组光谱数据。参与国家自然科学基金面上项目，开发 Python 全流程自动化脚本处理遥感数据。近期独立开发 RAG Agent 原型，构建从文献解析到检索问答的完整链路。具备点云处理、LiDAR 数据分析、传感器融合相关基础。希望将科研中积累的数据处理与建模能力应用到工程落地场景。

My master's research focuses on **lunar remote sensing and reflectance spectroscopy**. I independently built an automated spectral measurement system, collecting 10,000+ spectral datasets. I contributed to a National Natural Science Foundation project, developing Python pipelines for end-to-end remote sensing data processing. Recently I built a RAG Agent prototype covering the full pipeline from PDF parsing to grounded Q&A. I also have background in point cloud processing, LiDAR data analysis, and sensor fusion. I'm looking to apply my data processing and modeling expertise in industry-oriented AI roles.

---

## Highlights

|  |  |  |
|--|------|---------|
| 🎓 | 中科院硕士（保研）· GPA 3.9 · 本科排名 1/84 | CAS Master's (direct admission) · GPA 3.9 · Ranked 1/84 in B.S. |
| 📜 | **发明专利**（第二发明人）· 自动化光谱测量系统 | **Invention Patent** (2nd inventor) · Automated spectral measurement system |
| 📝 | **SCI论文一作在投** · 多角度光谱折射率反演方法 | **1st-author SCI paper** under review · Refractive index inversion via multi-angle spectra |
| 💻 | **软件著作权**（第二作者）· 大熊猫生境分析软件 | **Software Copyright** (2nd author) · Panda habitat analysis software |
| 🏆 | **国家一等奖** · 全国大学生物理实验竞赛 (2022) | **National 1st Prize** · National Physics Experiment Competition |
| 🏅 | **国家三等奖** · 中国大学生物理学术竞赛 (2022) | **National 3rd Prize** · China Undergraduate Physics Tournament |
| 🏅 | **省级一等奖** · 西南地区物理学术竞赛 (2022) | **Provincial 1st Prize** · Southwest Physics Tournament |
| 🏅 | **省级二等奖** · 五一数学建模竞赛（队长）(2022) | **Provincial 2nd Prize** · May 1st Math Modeling (Team Leader) |
| 🎖️ | 四川省优秀毕业生 · 优秀毕业论文 · 校一等奖学金×3 | Provincial Outstanding Graduate · Outstanding Thesis · 1st-class Scholarship ×3 |

---

## Tech Stack

**Languages:** Python · C++ · MATLAB · SQL
**AI / ML:** PyTorch · TensorFlow · U-Net · SE-CNN · Siamese Network · Random Forest · SVM · RAG · LLM API
**Remote Sensing / Perception:** ENVI · ArcGIS · GDAL · Rasterio · Point Cloud · LiDAR · Sensor Fusion
**Dev Tools:** Git · Streamlit · Plotly · Cursor · Claude Code

---

## Projects

### 🔬 Spectral Explorer — 月球矿物光谱数据库检索与可视化系统
> Lunar Mineral Spectral Database Search & Visualization System

[![GitHub](https://img.shields.io/badge/GitHub-spectral--explorer-blue?logo=github)](https://github.com/ruiverse/spectral-explorer)

基于实测光谱数据，独立开发交互式 Web 数据库系统。支持多维检索、交互式光谱曲线、角度热力图、粒径效应对比、光谱特征参数自动提取、批量 CSV 导出。

Built an interactive web database system from lab-measured spectral data. Features multi-dimensional search, interactive spectral curves, angle heatmaps, grain-size comparison, automated feature extraction, and batch CSV export.

`Python` `Streamlit` `Plotly`

---

### 🐼 Panda Habitat Assessment — 大熊猫震后生境评价系统
> Post-Earthquake Habitat Assessment for Giant Pandas in Wolong

[![GitHub](https://img.shields.io/badge/GitHub-panda--habitat--assessment-blue?logo=github)](https://github.com/ruiverse/panda-habitat-assessment)

省级大创项目负责人（5人团队）。基于 PyTorch 构建 SE-CNN（注意力机制 + CNN）滑坡易发性评价模型，scikit-learn 随机森林（500棵树、11因子）生境评价模型。成果申请软件著作权。

Led a provincial-level research project (5-member team). Built an SE-CNN landslide susceptibility model in PyTorch and a Random Forest habitat assessment model (500 trees, 11 factors) with scikit-learn. Results led to a registered software copyright.

`PyTorch` `scikit-learn` `GDAL` `SE-CNN` `Random Forest`

---

### 🛰️ RS Change Detection — 遥感影像变化检测工具
> Remote Sensing Image Change Detection Tool

[![GitHub](https://img.shields.io/badge/GitHub-rs--change--detection-blue?logo=github)](https://github.com/ruiverse/rs-change-detection)

独立开发，基于 U-Net / Siamese Network 实现双时相遥感影像自动变化检测。在 LEVIR-CD+ 真实数据集上训练（T4 GPU），测试集 OA = 95.37%。

Independently developed a dual-temporal change detection tool using U-Net / Siamese Network. Trained on LEVIR-CD+ dataset (T4 GPU), achieving 95.37% overall accuracy on the test set.

`PyTorch` `U-Net` `Siamese Network` `Rasterio` `Streamlit`

---

### 🤖 AI Research Assistant — 科研文献智能分析与复现 Agent
> RAG Agent for Scientific Literature Analysis & Experiment Planning

[![GitHub](https://img.shields.io/badge/GitHub-ai--research--assistant-blue?logo=github)](https://github.com/ruiverse/ai-research-assistant)

面向科研论文调研与实验复现规划的 RAG Agent 原型。覆盖 PDF 解析 → 文本切分 → 混合检索 → RAG 问答 → 论文结构化总结 → 实验复现计划生成的完整链路，针对参考文献、作者信息、基金信息、公式和表格残留设计 chunk 噪声过滤机制，含 50+ 单元测试。

A RAG Agent prototype for scientific literature analysis and experiment planning. Covers PDF parsing, chunk splitting, hybrid retrieval, grounded Q&A, structured paper summarization, and reproduction-plan generation, with chunk-level PDF noise filtering and 50+ unit tests.

`Python` `PyMuPDF` `TF-IDF` `DeepSeek API` `RAG` `Streamlit` `pytest`

---

### 📋 Planned Projects

| 项目 / Project | 简介 / Description | 技术栈 / Stack |
|---|---|---|
| Hapke 模型参数反演交互工具 | 光谱数据上传 → 自动拟合 → 输出参数 + 拟合曲线 | Streamlit + SciPy + Plotly |
| 撞击坑自动识别工具 | 基于 LRO 遥感影像的目标检测与形态参数提取 | PyTorch + OpenCV |

---

## Research Experience

**独立科研 · 月表矿物反射光谱测量系统开发与空间风化速率评估** (2024.09 — Present)
*Independent Research · Lunar Spectral Measurement System & Space Weathering Assessment*
- 独立负责人 · 发明专利（第二发明人）· SCI论文一作在投
- 自主搭建自动化光谱测量系统，累计采集万组数据
- Python 实现 Hapke 辐射传输模型参数反演（数值优化 / 曲线拟合）
- 为多所高校及研究所提供光谱数据处理服务，单次交付上千组数据

**国家自然科学基金面上项目 · 月表撞击坑形态退化与地质定年模型研究** (2024.09 — 2025.06)
*NSFC Project · Lunar Crater Morphological Degradation & Geological Dating Model*
- 基于 LRO 卫星遥感影像，批量提取并分析 1000+ 个撞击坑的多维形态参数
- Python 开发批量处理脚本，实现遥感数据提取 → 统计分析 → 可视化全流程自动化

---

## Education

| | |
|--|--|
| 🎓 **中国科学院 国家空间科学中心** | 理学硕士（保研）· 2024–2027 · GPA 3.9 |
| | *National Space Science Center, CAS · M.S. (Direct Admission)* |
| 🎓 **成都理工大学（双一流）** | 空间科学与技术 · 工学学士 · 2019–2024 · 排名 1/84 |
| | *Chengdu University of Technology (Double First-Class) · B.E. · Ranked 1/84* |

---

*即时可到岗实习 · Available for immediate internship*
*2027届校招 · 2027 Campus Recruitment*
