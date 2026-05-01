---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👋 你好,我是张书瑶 (Shuyao Zhang)

> **用电化学读懂腐蚀,用增材制造重塑合金,用数据驱动材料发现。**

我是 [天津大学](https://www.tju.edu.cn/) 化工学院的博士候选人,师从 [陈旭教授](https://chemeng.tju.edu.cn/);自 2025 年 5 月起作为 CSC 国家公派联合培养博士在 [南洋理工大学 (NTU)](https://www.ntu.edu.sg/) 周琨教授课题组开展研究,预计 2026 年 7 月毕业。

我的研究关注 **极端环境下金属材料的腐蚀失效与防护**——从 HF 蒸汽到氯碱体系,从 SCC 到点蚀,从工艺优化到合金设计——用电化学、增材制造和机器学习的交叉视角,把"为什么会坏"和"怎么不坏"这两个老问题做出新的回答。

<a href='https://scholar.google.com/citations?user=KpBH4RIAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>
<img src="https://img.shields.io/badge/论文-13_篇-brightgreen?style=flat&logo=bookstack" alt="papers">
<img src="https://img.shields.io/badge/一作/共一-7_篇-orange?style=flat&logo=academia" alt="first-author">

---

<span class='anchor' id='news'></span>

# 🔥 最新动态

- **2026.04** &nbsp;🎉 共同一作论文 *Competitive adsorption and unexpected corrosion inhibition effect of 316L in NaClO₃/NaCl* 被 **Corrosion Science** 接收
- **2026.04** &nbsp;📨 一作论文 *Multi-ion governed passivation and breakdown of 316L in NaCl/NaClO₃/NaOH* 投稿 **Corrosion Science**(Under Review)
- **2025.05** &nbsp;✈️ 加入新加坡南洋理工大学 (NTU) 周琨教授课题组,开始 CSC 国家公派联合培养
- **2025**  &nbsp;&nbsp;&nbsp;&nbsp;📄 一作论文 *DED 316L vs Inconel 625 在 HF 蒸汽中的微液滴电化学分析* 发表于 **Electrochimica Acta**
- **2024**  &nbsp;&nbsp;&nbsp;&nbsp;📄 一作论文 *增材制造 SS316L/IN625 功能梯度材料在 HF 中的耐蚀性* 发表于 **Corrosion Science**
- **2024**  &nbsp;&nbsp;&nbsp;&nbsp;📄 共同一作 *不同增材工艺对 316L 在 HF 蒸汽中应力腐蚀开裂的影响* 发表于 **JMST**
- **2024**  &nbsp;&nbsp;&nbsp;&nbsp;📄 一作论文 *DED SS316L/IN625 混合合金的均匀腐蚀与局部腐蚀平衡* 发表于 **JMRT**

---

<span class='anchor' id='research'></span>

# 🔬 研究方向

<div class='paper-box'><div class='paper-box-image'><div><img src='images/research-corrosion.svg' alt="corrosion" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### 🌊 复杂环境下的材料失效
HF 蒸汽、氯碱(NaClO₃ + NaCl + NaOH)、应力耦合等极端体系中的均匀腐蚀、点蚀、SCC。把"宏观失效"拆解到"界面反应",再回到"工程预测"。

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/research-am.svg' alt="am" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### 🖨️ 金属增材制造与合金设计
DED / LPBF 工艺下的 316L、Inconel 625、GH4169、308L、镍铝青铜(NAB)等。功能梯度材料、第二相工程(TiC 强化)、热处理调控。

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/research-electrochem.svg' alt="electrochem" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### ⚡ 界面电化学与钝化机理
钝化膜的多离子调控、击穿机理、原位电化学诊断。微液滴电化学、电化学噪声、动电位/恒电位极化、EIS。

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/research-data.svg' alt="ml" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### 🤖 数据驱动的材料发现
用 ML 加速合金成分优化与腐蚀预测,把多年实验数据沉淀的直觉,变成可迁移、可复现的模型。

</div></div>

---

<span class='anchor' id='education'></span>

# 🎓 学历

- *2025.05 – 至今*&nbsp;&nbsp;<a href="https://www.ntu.edu.sg/"><img class="svg" src="/images/NTU_logo.svg" width="22pt"></a> **南洋理工大学 (NTU)**, 新加坡 — 联合培养博士 · 导师 Prof. Kun Zhou · CSC 国家公派
- *2020.09 – 2026.07 (预计)*&nbsp;&nbsp;<a href="https://www.tju.edu.cn/"><img class="svg" src="/images/TJU_logo.svg" width="22pt"></a> **天津大学**, 中国 — 化工过程机械 · 硕博连读 · 导师 [陈旭教授](https://chemeng.tju.edu.cn/)
- *2016.09 – 2020.06*&nbsp;&nbsp;<a href="https://www.tju.edu.cn/"><img class="svg" src="/images/TJU_logo.svg" width="22pt"></a> **天津大学**, 中国 — 过程装备与控制工程 · 学士 · GPA 3.53/4.0
- *2019.09 – 2019.12*&nbsp;&nbsp;**Carleton University**, 加拿大 — 优秀本科生交流项目 · CSC 资助
- *2019.07 – 2019.08*&nbsp;&nbsp;**Duke University**, 美国 — Summer Scholar (Probability and Statistics in Engineering, Final Grade: A)

---

<span class='anchor' id='publications'></span>

# 📝 学术论文

> **总计:** 13 篇同行评议论文(5 篇一作 / 共一已发表 + 2 篇在投/在写)。完整列表见 [Google Scholar](https://scholar.google.com/citations?user=KpBH4RIAAAAJ)。

### 一作 / 共同一作

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Corrosion Science 2024</div><img src='images/paper-cs2024.svg' alt="cs2024" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- **Zhang S**, Dai H, Li Y, Zhang Z, Chen S, He M, Zhang B, Ma Y, Chen X. **Additive manufactured corrosion-resistant SS316L/IN625 functionally graded multi-material in hydrofluoric acid (HF) environment.** *Corrosion Science*, 2024, 230: 111926.
[[DOI]](https://doi.org/10.1016/j.corsci.2024.111926)

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Electrochim. Acta 2025</div><img src='images/paper-ea2025.svg' alt="ea2025" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- **Zhang S**, Li Y, Zhao Y, Yu J, Zhang Z, Chen X. **Elucidating corrosion discrepancies between directed energy deposited 316L stainless steel and Inconel 625 via micro-droplet characterization and electrochemical analysis in hydrofluoric acid (HF) vapor environment.** *Electrochimica Acta*, 2025: 147357.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JMRT 2024</div><img src='images/paper-jmrt2024.svg' alt="jmrt2024" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- **Zhang S**, Li Y, Dai H, Zhang Z, Chen X. **Achieving balanced uniform and local corrosion performance of SS316L/IN625 hybrid alloy manufactured by directed energy deposition.** *Journal of Materials Research and Technology*, 2024, 32: 3937–3948.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JMST 2024 · 共一</div><img src='images/paper-jmst2024.svg' alt="jmst2024" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Dai H, **Zhang S** *(Co-first author)*, Li Y, Yu J, Kuang Y, Xuan F, Chen X. **Stress corrosion cracking behavior of 316L manufactured by different additive manufacturing techniques in hydrofluoric acid vapor.** *Journal of Materials Science & Technology*, 2024, 191: 33–48.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Corrosion Science 2026 · 共一</div><img src='images/paper-cs2026.svg' alt="cs2026" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Yao J, **Zhang S** *(Co-first author)*, Chen S, et al. **Competitive adsorption and unexpected corrosion inhibition effect of 316L stainless steel in NaClO₃ and NaCl environment of chlor-alkali industry.** *Corrosion Science*, 2026: 113777.

</div></div>

- **Zhang S**, Cheng Zhang. **Multi-ion governed passivation and breakdown of 316L stainless steel in NaCl/NaClO₃/NaOH alkaline environments.** *Corrosion Science.* **(Under Review, 2026)**

- **Zhang S**, Zhao, Niu P, Chen X. **TiC-enabled second-phase engineering in DED 316L stainless steel for simultaneous strength and corrosion resistance enhancement.** *(In Preparation, 2026)*

- **Zhang S**, Li B, Zhou K. **Heat-treatment-induced corrosion mode transition in DED-fabricated nickel-aluminium bronze: from uniform corrosion to selective dissolution.** *(In Preparation, 2026)*

### 合作论文

- Li Y, **Zhang S**, Yu W, Li B, Xuan F, Chen X. **Multiaxial low cycle fatigue behavior and life prediction of wire arc additive manufactured 308L stainless steel.** *International Journal of Fatigue*, 2024, 183: 108241.

- Zhao Y, **Zhang S**, Zhu J, et al. **Built-in electric field-driven interfacial charge transfer for boosted pseudocapacitance.** *Chemical Engineering Journal*, 2025: 166061.

- Zhao Y, Gao Z, **Zhang S**, et al. **Asymmetric-charge-distributed Co–Mn diatomic catalyst enables efficient oxygen reduction reaction.** *Advanced Functional Materials*, 2025, 35(37): 2504260.

- Li Y, Dai H, **Zhang S**, et al. **The enhanced high-temperature oxidation resistance of additively manufactured GH4169 by adding small amounts of 304L.** *Journal of Materials Research and Technology*, 2024, 30: 164–173.

- Guo C, Shi S, Yu J, **Zhang S**, Dai H, Sun X, Zhang Z, Chen X. **Addressing the strength–corrosion tradeoff in 316L stainless steel by introducing cellular ferrite via directed energy deposition.** *Additive Manufacturing*, 2024, 86: 104201.

---

<span class='anchor' id='skills'></span>

# 🛠️ 技能与专长

**🔋 腐蚀与电化学**&nbsp;&nbsp;CHI · Gamry · Bio-Logic 电化学工作站｜动电位/恒电位极化｜EIS｜电化学噪声｜微液滴电化学｜原位应力-腐蚀耦合测试

**🖨️ 金属增材制造**&nbsp;&nbsp;DED (定向能量沉积)｜LPBF (激光粉床熔融)｜EOS M290 操作

**🔬 微观结构表征**&nbsp;&nbsp;SEM (天津大学分析测试中心 FEI SEM **学生指导员**)｜EDS · EBSD · TEM · XRD · FIB · HR-DIC

**💻 仿真与数据分析**&nbsp;&nbsp;ABAQUS (弹塑性 / 疲劳)｜COMSOL Multiphysics｜Python (NumPy · Pandas · scikit-learn)｜MATLAB

**🌐 语言**&nbsp;&nbsp;普通话 (母语)｜English (TOEFL 100)

---

<span class='anchor' id='conferences'></span>

# 🏛️ 学术会议

- **2024**&nbsp;&nbsp;天津大学化工学院博士论坛, 中国天津 — *Oral Presentation*
- **2023**&nbsp;&nbsp;International Conference on Corrosion Protection and Application, 中国武汉 — *Oral Presentation*
- **2022**&nbsp;&nbsp;International Symposium on Structural Integrity (ISSI), 中国长沙 — *Oral Presentation* (Online)

---

<span class='anchor' id='global-experience'></span>

# 🌍 国际经历

- **2025–** &nbsp;南洋理工大学 (NTU), 新加坡 — CSC 国家公派联合培养
- **2019** &nbsp;Duke University, 美国 — 6 周 Summer Scholar (Final A)
- **2019** &nbsp;Carleton University, 加拿大 — 3 个月本科交流 · CSC 优秀本科生项目

---

<span class='anchor' id='contact'></span>

# 📫 联系方式

- 📧 **Email**&nbsp;&nbsp;[shuyao98.zhang@gmail.com](mailto:shuyao98.zhang@gmail.com) ｜ [N2409991B@e.ntu.edu.sg](mailto:N2409991B@e.ntu.edu.sg)
- 🎓 **Google Scholar**&nbsp;&nbsp;[KpBH4RIAAAAJ](https://scholar.google.com/citations?user=KpBH4RIAAAAJ)
- 🆔 **ORCID**&nbsp;&nbsp;[0009-0003-9231-6618](https://orcid.org/0009-0003-9231-6618)
- 💻 **GitHub**&nbsp;&nbsp;[@shuyao998](https://github.com/shuyao998)

> *欢迎对增材制造金属耐蚀性、界面电化学、ML 辅助合金设计感兴趣的同行交流合作 🤝*
