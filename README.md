
<div align="center">

# Vikas Sahu

### AI Engineer · Machine Learning · Full-Stack Development

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=Building+AI-powered+applications;Computer+Vision+%7C+Generative+AI;RAG+%7C+LLMs+%7C+Intelligent+Analytics;Turning+real-world+problems+into+software" alt="Animated introduction" />

<p>
  <a href="https://github.com/Vikaas28">
    <img src="https://img.shields.io/badge/GitHub-Vikaas28-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <img src="https://img.shields.io/badge/Focus-AI%20Engineering-2563eb?style=for-the-badge" alt="AI Engineering"/>
  <img src="https://img.shields.io/badge/Building-Intelligent%20Systems-7c3aed?style=for-the-badge" alt="Intelligent Systems"/>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=Vikaas28&label=PROFILE+VIEWS&color=0e75b6&style=flat-square" alt="Profile views"/>
</p>

</div>

---

## 👨‍💻 About Me

I'm a Computer Science Engineering student and developer passionate about building **AI-powered systems and full-stack applications** that solve real-world problems.

My interests span Computer Vision, Machine Learning, Generative AI, Retrieval-Augmented Generation (RAG), and cloud-native application development.

I enjoy connecting intelligent models with practical software engineering — from data processing and model inference to APIs, dashboards, and scalable applications.

- 🧠 Exploring LLMs, RAG pipelines, and intelligent agents
- 👁️ Building Computer Vision systems for real-world environments
- 🏗️ Developing full-stack applications and AI-powered backends
- ☁️ Learning AWS, Docker, MLOps, and model deployment
- 🎯 Focused on writing useful, maintainable, production-oriented software

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🩺 Dr. Charaka

**AI-Powered Healthcare Assistant**

A healthcare platform designed to provide symptom analysis, drug-interaction checking, medical guidance, and accessible health information.

**Highlights**
- LLM-powered healthcare assistance
- Unified web-based healthcare workflows
- Structured medical information access

`Python` `Django` `LLMs` `SQLite`

</td>
<td width="50%" valign="top">

### ♻️ Smart Waste Monitoring

**Computer Vision for Civic Infrastructure**

A smart-city monitoring system designed to detect suspicious waste-disposal events using CCTV video and computer vision.

**Highlights**
- Object detection and activity analysis
- Multi-object tracking
- Incident evidence and analytics dashboard
- Municipal monitoring workflows

`YOLOv8` `MediaPipe` `ByteTrack` `OpenCV` `React` `Supabase`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛣️ Pothole Detection System

**AI for Road Infrastructure**

A deep-learning system designed to identify potholes in images and video streams, supporting automated road-defect monitoring.

**Highlights**
- Image and video inference
- Automated defect identification
- Smart-city maintenance applications

`YOLO` `Python` `OpenCV` `Deep Learning`

</td>
<td width="50%" valign="top">

### 🏋️ GymFlow Pro

**Modern Gym Management Platform**

A web application for gym operations, including memberships, attendance, authentication, and operational analytics.

**Highlights**
- Modern responsive interface
- Membership and attendance workflows
- Cloud-backed application architecture

`React` `TypeScript` `Tailwind CSS` `Supabase` `Vite`

</td>
</tr>
</table>

---

## 🧠 Flagship AI Project — NovaCart Intelligence

### Hybrid AI Business Intelligence Assistant

An AI-powered analytics assistant concept for **NovaCart, an e-commerce SaaS platform**, combining structured business data with unstructured customer feedback to answer business questions in natural language.

The system routes questions to the appropriate retrieval strategy instead of forcing every query through a single data source.

<table>
<tr>
<th>Query Mode</th>
<th>Data Source</th>
<th>What It Delivers</th>
</tr>
<tr>
<td><strong>📊 SQL-only</strong></td>
<td>DuckDB</td>
<td>Revenue, subscriptions, orders, and exact business metrics with generated SQL.</td>
</tr>
<tr>
<td><strong>🔎 Vector-only</strong></td>
<td>Qdrant</td>
<td>Customer-requested features, cancellation reasons, and recurring feedback themes.</td>
</tr>
<tr>
<td><strong>🧠 Hybrid</strong></td>
<td>DuckDB + Qdrant</td>
<td>Combines financial changes with relevant support tickets to investigate business causes.</td>
</tr>
</table>

### ⚡ How the Hybrid Pipeline Works

1. **Understand the question** — classify the request as SQL, vector search, or hybrid.
2. **Extract business filters** — identify region, quarter, and subscription plan.
3. **Query structured data** — generate and execute SQL against DuckDB.
4. **Retrieve customer context** — search Qdrant using semantic similarity and metadata filters.
5. **Synthesize the answer** — combine verified metrics with relevant customer evidence.
6. **Show the evidence** — return source ticket IDs and the SQL used for analysis.

### 💡 Example: Why Did Enterprise Revenue Drop?

**Illustrative scenario — sample figures, not verified company data.**

A business user asks:

> Why did our Enterprise revenue drop in the West region in Q3?

**Business metrics from DuckDB**

| Metric | Example result |
|---|---:|
| Q2 revenue | $420,000 |
| Q3 revenue | $348,600 |
| Revenue change | -17% |
| Churned accounts | 6 |

**Customer evidence from Qdrant**

- **SSO login outage:** tickets describe enterprise administrators being locked out.
- **Webhook latency:** customers report delayed order-sync events.
- **Cancellation evidence:** retrieved notes help investigate whether these problems contributed to churn.

**Final answer:** Revenue fell by 17% in the example scenario. The retrieved support records suggest SSO outages and webhook delays as possible contributing factors, which can be investigated against the affected accounts.

**Architecture**

`Business Question → Intent Router → DuckDB SQL + Qdrant Retrieval → Evidence Synthesis → Answer + Sources`

**Core technologies**

`Python` `DuckDB` `Qdrant` `SQL` `Embeddings` `LLMs` `RAG` `FastAPI` `React`

**Engineering focus:** hybrid retrieval, metadata filtering, grounded responses, traceable SQL, and evidence-backed business insights.

---

## 🛠️ Technical Stack

<div align="center">

### AI & Machine Learning

<img src="https://skillicons.dev/icons?i=python,tensorflow,pytorch,opencv" alt="AI and machine learning technologies"/>

### Backend & Databases

<img src="https://skillicons.dev/icons?i=django,flask,fastapi,sqlite,postgres" alt="Backend technologies"/>

### Frontend Development

<img src="https://skillicons.dev/icons?i=react,ts,js,vite,tailwind" alt="Frontend technologies"/>

### Cloud & Developer Tools

<img src="https://skillicons.dev/icons?i=aws,docker,linux,git,github,vscode" alt="Cloud and developer tools"/>

</div>

**Additional tools:** Scikit-learn, Keras, Pandas, NumPy, SciPy, NLTK, Supabase, OpenCV, YOLO, MediaPipe, ByteTrack, RAG, embeddings, vector search, and REST APIs.

---

## 🏆 Certifications & Learning

- 🏅 IBM Data Science Professional Certificate
- ☁️ AWS Cloud Practitioner Course
- ☁️ AWS Cloud Fundamentals & Cloud Computing

---

## 📈 GitHub Statistics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Vikaas28&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub statistics"/>

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vikaas28&layout=compact&theme=tokyonight&hide_border=true" alt="Most-used languages"/>

<img width="95%" src="https://github-readme-streak-stats.herokuapp.com/?user=Vikaas28&theme=tokyonight&hide_border=true" alt="GitHub contribution streak"/>

</div>

---

## 🌱 What I'm Exploring

- Generative AI and advanced RAG architectures
- Reliable AI systems with grounded answers and source attribution
- Production deployment, MLOps, and cloud infrastructure
- Computer Vision pipelines and real-time inference
- Data-driven applications that turn business questions into actionable insights

---

<div align="center">

### "Build intelligent systems. Solve meaningful problems."

**Thanks for visiting my profile! Let's build something useful.**

<a href="https://github.com/Vikaas28">
  <img src="https://img.shields.io/badge/Explore%20My%20Repositories-181717?style=for-the-badge&logo=github" alt="Explore repositories"/>
</a>

</div>
