<h1 align="center">Hi, I'm Heejae Kwon (Hailey) 👋</h1>


<p align="center">
  <a href="https://www.linkedin.com/in/heejae-kwon-hailey/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:heejae.hailey@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/haileybaileyo">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

### 🔬 About Me

- 🎓 4th-year **AI Engineering** student at **Sookmyung Women's University** (expected graduation Feb 2027), double-majoring in **COSS Big Data**
- 🧫 Undergraduate researcher at **SISLAB** (RL-based Agentic AI Lab, advised by Prof. Yujin Lim)
- 🧬 Summer research intern at **University of Nevada, Las Vegas (UNLV)** — *Uncertainty-Aware Histopathology Survival Analysis*, under Dr. Mingon Kang (DataX Lab)
- 🩺 Core interest: **can we actually trust a single evaluation metric?** — I work on Uncertainty Quantification, Reliable AI Evaluation, and Computer Vision, diagnosing where evaluation itself can mislead — from WSI-based survival prediction to small-object detection and quantitative systems
- 🎯 Currently preparing for graduate school (targeting domestic top-tier programs / exploring US AI master's programs)

---

### 🧪 Research Focus

```
Whole-Slide Imaging (WSI) → Feature Extraction (UNI / UNI v2) → Attention-based MIL
        → Cox Survival Modeling → Multi-Axis Evaluation (C-index · IBS · Calibration · UQ)
```

- **Uncertainty Quantification for Survival Models** — benchmarking MC-Dropout, Deep Ensembles, and SNGP on TCGA glioma WSIs; diagnosing whether "uncertainty" is genuinely informative or just a re-packaged risk score
- **Beyond C-index** — solo research on why a single discrimination metric can hide systematic calibration bias; validated across TCGA-GBMLGG and TCGA-LUAD with 5-seed × 5-fold repeated cross-validation (25 independently trained models)
- **Multi-axis evaluation philosophy** — carried over from earlier object-detection work (mAP alone hides a lot too) into survival analysis

---

### 📄 Publications & Manuscripts

| Title | Venue | Status |
|---|---|---|
| Pest24 데이터셋 기반 소형 해충 탐지의 다축 성능 분석 연구 | ASK 2026 | 🥈 Silver Award |
| LLM 기반 기하학적 진단을 통한 연합학습 제어 변수 조정 기법 연구 | ASK 2026 | Presented |

---

### 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/SLURM-000000?style=flat-square&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
</p>

---

### 🚀 Featured Projects

<table>
<tr>
<td width="50%">

📎 <a href="https://github.com/RobertxPearce/uncertainty-aware-histopathology-survival-analysis"><b>Uncertainty-Aware Histopathology Survival Analysis</b></a>
<br/>
End-to-end WSI survival pipeline (UNI v2 → ABMIL → Cox) on 875 TCGA glioma patients (1,700+ slides), 5-fold CV on a SLURM GPU cluster. Implemented and benchmarked <b>Deep Ensembles</b> against MC-Dropout/SNGP, and designed the confound analysis showing 64% of SNGP's apparent uncertainty advantage was just its own risk score in disguise.
<br/><br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/TCGA-4B8BBE?style=flat-square" />
<img src="https://img.shields.io/badge/SLURM-000000?style=flat-square" />

</td>
<td width="50%">

📎 <a href="https://github.com/jwdebbie/quant-ai-server"><b>Quant AI Server</b></a>
<br/>
Multi-agent quantitative investing system built with LangGraph. Owned the AI/numerical branch — price collection (yfinance/KIS), 11 technical indicators, momentum strategy, and backtesting (MDD/Sharpe) across 10 domestic & international tickers.
<br/><br/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />

</td>
</tr>
</table>

<details>
<summary><b>🗂️ More Projects</b></summary>
<br/>

- **Genti** — Azure-based real-time AI assistant for call-center agents; verbal-abuse detection (Azure Content Safety) + GPT-4o-mini response scripting + RAG grounding (Azure Search)
- **DIGIRO** — Real-time assembly alert service for Jongno-gu; Seoul Police web crawling + Gemini parsing + AES-SIV encrypted SMS alerts (adopted toward commercialization by Jongno-gu Office)
- **Seocho-gu Last-Mile Bus Route Design** — PM & data analysis; transit-card big data + 50m-grid gap analysis + TSP routing, covering an estimated 71.8% of the elderly population

</details>

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=haileybaileyo&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=haileybaileyo&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=haileybaileyo&theme=tokyonight&hide_border=true" />
</p>

---

### 🏆 Highlights

- 🥈 **ASK 2026 Silver Award** — Pest24 multi-axis detection evaluation (invited for extended journal submission)
- 🥉 **3rd Place, MixUP AI Datathon** (TAVE × Bitamin) — hERG channel inhibition regression
- 🚌 **Community Problem-Solving Award (Dinjae's Pick)** — Last-Mile bus route design w/ Seocho-gu Office
- 🏅 **Individual Excellence Award**, Shinhan Bank Student Ambassador (+ November Team Excellence Award)
- ✈️ Selected for **UNLV International Research Program** (competitive, 4-person cross-university team)

---

<p align="center">
  <i>"C-index만으로는 충분한가" — always asking what a single metric might be hiding.</i>
</p>
