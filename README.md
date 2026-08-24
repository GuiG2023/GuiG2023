# Hi there, I'm Guiran Liu 👋

<p align="center">
  <a href="https://www.linkedin.com/in/guiran-liu-232ab228a/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://scholar.google.com/citations?user=RQWgrIsAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white" /></a>
</p>

---

## 🚀 About Me

<table>
  <tr>
    <td width="65%" valign="top">
      <p>I work on <b>LLM inference systems</b> — making them faster and cheaper, and shipping them as services people actually use.</p>
      <p><b>Research</b> — LLM inference optimization at SFSU CIDER Lab: quantization, KV-cache compression, and learned routing for edge–cloud inference. Trained a router reaching 86% accuracy that cut inference cost 60% with a controlled 12% accuracy trade-off. 10 peer-reviewed papers — see <a href="https://scholar.google.com/citations?user=RQWgrIsAAAAJ&hl=en">Google Scholar</a>.</p>
      <p><b>Engineering</b> — Backend for deployed applications: FastAPI, MySQL, SQLAlchemy, AWS EC2, NGINX. Backend Lead on GatorMart, a campus marketplace running in production with 15/15 P1 features shipped.</p>
      <p><b>Open to</b> — ML Systems / Inference Engineering and Backend roles.</p>
    </td>
    <td width="35%" valign="top" align="center">
      <img src="./assets/panda.jpg" width="180px" style="border-radius: 12px; border: 2px solid #5c2d91;" />
      <br />
      <sub><i>Code hard, stay sharp. 🚀</i></sub>
    </td>
  </tr>
</table>

---

## 🛠️ GatorMart — Campus Marketplace + AI Agent Layer

**Backend Lead** (7-person team) | SFSU-exclusive marketplace: email verification, listings, search, in-app messaging — extended with a multi-agent moderation and scheduling layer.

[Repository →](https://github.com/GuiG2023/campus-marketplace) | [Demo Video →](https://www.youtube.com/watch?v=awfDpspFIRQ)

- Parallel multi-agent moderation on **Google ADK 2.0** — concurrent vision and text-compliance agents merging at a join node, with a governor agent writing status to MySQL via typed SQLAlchemy tools
- **MCP server** (FastMCP, stdio JSON-RPC) exposing calendar and campus-location tools to a scheduling agent; graceful degradation on LLM failure or quota exhaustion
- Validated with standalone and integration test harnesses against a live database

**Tech**: FastAPI, MySQL, SQLAlchemy, AWS EC2, NGINX, Google ADK 2.0, MCP, Gemini

---

## 🔥 WildfireRFM — Edge AI Risk Prediction

**ML Engineer** | Edge-first wildfire risk assessment using quantized lightweight LLMs for on-device inference, fusing vision, weather, and geospatial data into structured reports.

[Demo Video →](https://www.youtube.com/watch?v=A1nFOhFK2E4) | [🏆 First Prize — KumoAI Hackathon](https://cs.sfsu.edu/news/cider-lab-wins-first-prize-kumo-ai-hackathon)

**Tech**: KumoRFM, quantized LLMs, Pandas, OpenWeatherMap API | ~12s per-inference latency across multi-camera edge clusters

---

## 💻 Skills

**ML Systems**: LLM inference optimization, quantization, KV-cache compression, model routing, benchmarking & evaluation  
**AI Engineering**: Multi-agent orchestration (Google ADK), MCP protocol, Gemini API, structured output  
**Backend**: Python, FastAPI, SQLAlchemy, MySQL, PostgreSQL, REST API design, JWT  
**Infrastructure**: Linux, AWS EC2, NGINX, Docker, Git, GitHub Actions  
**Also**: PyTorch, Hugging Face, Java, C/C++, React
