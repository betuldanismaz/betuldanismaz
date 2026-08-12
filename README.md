<div align="center">

# 🌌 Betül Danışmaz

### `Data Scientist` • `Computer Engineering Graduate`

</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=8A2BE2&center=true&vCenter=true&width=700&lines=Real-time+ML+pipelines+on+Kafka+%26+Docker;IEEE+SIU+2026+published+%26+presented;LLM+fine-tuning+%E2%80%94+LoRA+%26+SFT+on+medical+AI" alt="Typing SVG" />
<br/>

<img src="https://img.shields.io/badge/IEEE%20SIU%202026-Published%20%26%20Presented-6A5ACD?style=for-the-badge&logo=ieee&logoColor=white" />
<img src="https://img.shields.io/badge/TÜBİTAK%202209--A-Research%20Grant-2E8B57?style=for-the-badge" />
<img src="https://img.shields.io/badge/SIU%202026-Graduate%20Projects%20Competition-8B0000?style=for-the-badge" />
<img src="https://img.shields.io/badge/TEKNOFEST-Aviation%20AI%20Competitor-FF6F00?style=for-the-badge" />

</div>

---

## About Me

I build ML systems that go beyond notebooks: **real-time streaming pipelines**, **LLM fine-tuning for medical AI**, and **geospatial intelligence tools** designed for production deployment.

My work spans cybersecurity, healthcare, disaster response, and autonomous systems — united by a single focus: building AI systems that work outside the notebook.

- 🏢 Software Engineering Intern at **Uyumsoft**, building LLM-powered ERP cost analysis with **Llama 3.3 70B**
- 📄 Paper published and presented at [IEEE SIU 2026](https://ieeexplore.ieee.org/document/11636987) on real-time network intrusion detection
- 🏆 TÜBİTAK 2209-A research grant recipient; project presented at **SIU 2026 Graduate Projects Competition**
- 📝 Manuscript under review at the [Journal of Dental Education](https://onlinelibrary.wiley.com/journal/19307837) by Wiley
- 🎓 Computer Engineering graduate, GPA 3.49/4.00, Istanbul

Open to full-time **AI engineering**, **ML engineering**, and **applied AI research** roles globally.

---

## Selected Work

### 🛡️ Real-Time Network Intrusion Detection System
**Python • Kafka • Docker • XGBoost • TensorFlow • SHAP**

> Production-grade real-time intrusion detection pipeline with streaming inference, explainability, and automated threat response.

- Deployed production-grade NIDS on a Dockerized Kafka streaming pipeline, benchmarking 5 ML/DL architectures (XGBoost, Random Forest, Decision Tree, BiLSTM, LSTM) on **2.8M+ network flows**
- Achieved **98.88% accuracy** and **0.999 ROC-AUC**; architected Scapy-to-CICFlowMeter pipeline reducing 78 raw features to a top-20 optimized set
- Engineered ultra-low latency inference at **0.008 ms** with **126K+ predictions/sec**
- Built real-time monitoring dashboard with **SHAP explainability**, dynamic model hot-reloading, and automated iptables/Windows Firewall threat response
- 📄 Paper published and presented at [IEEE SIU 2026](https://ieeexplore.ieee.org/document/11636987)

[![Repo](https://img.shields.io/badge/GitHub-Network__Anomaly__Detection-181717?style=flat-square&logo=github)](https://github.com/betuldanismaz/Network_Anomaly_Detection)

---

### 🦷 DENTAI — Oral Pathology Assessment Platform
**React • Next.js • FastAPI • PostgreSQL • Gemma 2-9B • QLoRA • SFT**

> Intelligent clinical learning system with adaptive AI feedback for oral pathology education and assessment.

- Fine-tuned **Gemma 2-9B** via **QLoRA + SFT** on domain-specific dental corpora for oral pathology classification; deployed model on **Hugging Face** with a hybrid inference pipeline combining LLM-generated diagnoses and deterministic clinical validation rules
- Engineered an adaptive difficulty model using **Item Response Theory (IRT)** for student ability estimation, paired with **LSTM/XGBoost** predictive models to forecast learning trajectories and dynamically adjust case complexity
- Curated **100+ structured clinical scenarios** across multiple pathology categories with multi-modal AI analysis of dental radiographs and clinical images; built interactive **3D dental model viewer** for anatomical visualization
- Validated platform with dental faculty in a **Phase 1 feasibility study**; presented at **SIU 2026 Graduate Projects Competition**
- Awarded **TÜBİTAK 2209-A Research Grant**; manuscript under review at the *[Journal of Dental Education](https://onlinelibrary.wiley.com/journal/19307837)* by Wiley

[![Repo](https://img.shields.io/badge/GitHub-DisHekimligiAI-181717?style=flat-square&logo=github)](https://github.com/betuldanismaz/DisHekimligiAI)

---

### ✈️ TEKNOFEST 2026 — AI in Aviation (Drone Vision System)
**Python • YOLO11 • OpenCV • PyTorch • TensorRT**

> Real-time autonomous drone perception pipeline targeting object detection, GPS-free navigation, and cross-modal recognition under strict latency budgets — deployed on NVIDIA Jetson Orin Nano 8GB.

- Built a real-time multi-module AI pipeline across 3 competition tasks — object detection, GPS-free navigation, and cross-modal recognition (RGB ↔ Thermal/Satellite) — under a strict **700ms/frame** budget on **NVIDIA Jetson Orin Nano 8GB**
- Implemented **YOLO11s (TensorRT FP16)** with centroid-based tracking and hysteresis motion classification; developed hybrid GPS-free visual odometry with adaptive ORB/RAFT switching and a **7-DOF Extended Kalman Filter** for low-drift position estimation
- Designed time-budget-aware orchestrator with graceful degradation and coarse-to-fine cross-modal matching (GeM pooling + SuperPoint/SuperGlue), achieving **~10x fewer matcher calls**
- Maintained **103 tests** via TDD with CI/CD (GitHub Actions) and a **2,250-frame stress test** validating sustained sub-700ms throughput

[![Repo](https://img.shields.io/badge/GitHub-TEKNOFEST__2026-181717?style=flat-square&logo=github)](https://github.com/betuldanismaz)

---

### 🌍 GeoSafe — Disaster Safety & Geospatial Logistics Platform
**Python • FastAPI • PostgreSQL • PostGIS • React • Docker**

> Disaster response platform for locating safe gathering areas, available supplies, and nearby logistics resources through geospatial data.

- Modeled **Point and Polygon geometries** using WGS84/SRID 4326 in PostGIS
- Built spatial query pipelines with `ST_DistanceSphere`, `ST_AsGeoJSON`, and GIST indexing
- Designed a normalized **3NF supply chain schema** for warehouse inventory and movement tracking
- Delivered a GeoJSON API with async FastAPI and GeoAlchemy2
- Visualized evacuation zones, warehouses, and logistics data on an interactive Leaflet.js dashboard

[![Repo](https://img.shields.io/badge/GitHub-GEO--SAFE-181717?style=flat-square&logo=github)](https://github.com/betuldanismaz/GEO-SAFE)

---

### 🏆 YZTA Datathon 2026 — Cognitive Performance Prediction
**Python • CatBoost • XGBoost • Scikit-learn**

> Competitive regression challenge focused on predicting cognitive performance from behavioral and demographic features.

- Built a full ML pipeline covering EDA, feature engineering, validation, and weighted ensembling
- Engineered domain-specific features and applied robust cross-validation to reduce leakage risk
- Ranked **17th / 135 teams**, Top 13%, as part of a 3-person team

[![Repo](https://img.shields.io/badge/GitHub-datathon__yzta-181717?style=flat-square&logo=github)](https://github.com/betuldanismaz/datathon_yzta)

---

## 🛠️ Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=python,cs,js,c,cpp" />
</p>

### ML / AI / Data

<p>
  <img src="https://skillicons.dev/icons?i=tensorflow,pytorch,opencv" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLO-111111?style=for-the-badge" />
</p>

### Backend & Databases

<p>
  <img src="https://skillicons.dev/icons?i=dotnet,fastapi,postgres,mongodb" />
</p>

### Cloud / DevOps / Tools

<p>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,git,linux" />
  <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Huawei%20Cloud-FF0000?style=for-the-badge&logo=huawei&logoColor=white" />
</p>

---

## 📊 GitHub Activity

<div align="center">
<img src="https://streak-stats.demolab.com?user=betuldanismaz&theme=radical&hide_border=true" />
<br/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=betuldanismaz&theme=radical" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=betuldanismaz&theme=radical" />
</div>

---

## 📬 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/betuldanismaz/)
[![HuggingFace](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/betuldanismaz)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@danismazbetul3)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/bethdanis)

</div>

<div align="center">

*Open to AI engineering, ML engineering, and applied AI research roles — Turkey and globally.*

</div>
