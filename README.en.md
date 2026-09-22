<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=170&color=0:0d1117,45:1f6feb,100:39d353&text=Noel%20Mart%C3%ADnez&fontColor=e6edf3&fontSize=48&fontAlignY=36&desc=Backend%20Software%20Engineer%20%C2%B7%20Java%20%26%20Spring%20%C2%B7%20LLMs%20in%20production&descAlignY=58&descSize=15&animation=fadeIn" width="100%" />

<a href="https://github.com/noelmartinnez/noelmartinnez/blob/main/README.en.md"><img src="https://img.shields.io/badge/🇬🇧_English-1f6feb?style=flat-square&labelColor=0d1117" /></a>
<a href="https://github.com/noelmartinnez#readme"><img src="https://img.shields.io/badge/🇪🇸_Español-21262d?style=flat-square&labelColor=0d1117" /></a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3000&pause=1000&color=39D353&center=true&vCenter=true&width=600&lines=Java+%2B+Spring+Boot+backends+that+don't+page+you+at+3am;LLMs+with+numbers+attached%3A+F1%2C+latency%2C+cost+per+call;Shipped+to+banks+and+regulated+EU+products" alt="typing" />

</div>

---

I build **backend systems where AI has to actually hold up in production** — banking document pipelines, EU privacy tooling, regulated environments where "the model usually gets it right" is not an acceptable answer.

Most of my work is the unglamorous part around the model: microservices, schemas, evaluation, cost per inference. The model is one box in the diagram; the other twelve boxes are why it ships.

```
Alicante, Spain  ·  Java + Spring Boot + applied AI  ·  Spanish (native) / English (B1, improving daily)
```

---

## 🧭 Selected work

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ PrivacyShield
**European AI anonymization SaaS** · Fundamentia

Fine-tuned NER models (PyTorch, Hugging Face) to **F1 90%**, then layered LLMs via Spring AI + Azure AI Foundry to reach **F1 99%** across 20+ entity types.

Led the backend: Java microservices, Spring Boot, Kafka, MySQL, versioned for Kubernetes. Tuned prompts against precision, recall, latency **and cost** — caching cut inference time and spend.

`Java` `Spring AI` `Kafka` `PyTorch` `Azure AI Foundry`

</td>
<td width="50%" valign="top">

### 🏦 SimplyData
**Intelligent Document Processing for banking** · Fundamentia

Java microservices plus open-source LLMs (**Qwen, Gemma**) served with **vLLM** for information extraction — running in a live production platform in the banking sector.

Self-hosted models, because sending client documents to a third-party API was never on the table.

`Java` `vLLM` `Qwen` `Gemma` `Document AI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 Document RPA
**Automating administrative filings** · Fundamentia

Java + MySQL microservices streaming XML to Node.js RPA bots (Selenium, Puppeteer) that filled web forms automatically.

**~400 documents/month · ~100 manual hours saved.**

`Java` `Node.js` `Selenium` `Puppeteer`

</td>
<td width="50%" valign="top">

### 🏢 HUNTERS
**Corporate intranet** · Altia Consultores

Microservices in Java, Spring Boot and Spring Cloud over PostgreSQL and Oracle — schema design and query optimization included.

Modeled business processes with **Camunda (BPM)**, pushed test coverage to **85%** (JUnit, Mockito), shipped through Docker → Kubernetes with Jenkins, Harbor and Argo CD.

`Spring Cloud` `Camunda` `Argo CD` `Jenkins`

</td>
</tr>
</table>

---

## 🧪 Personal projects

<table>
<tr>
<td width="50%" valign="top">

#### [🖼️ ImgTwin](https://github.com/noelmartinnez/ImgTwin)

Detects and cleans up duplicate or near-identical images. Extracts embeddings with **MobileNet** (TensorFlow), reduces dimensionality with **PCA** and indexes them in **FAISS** for nearest-neighbour search. Ships with a UI to review and delete matches, and runs on CPU — no GPU required.

<a href="https://github.com/noelmartinnez/ImgTwin"><img src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776ab" /> <img src="https://img.shields.io/badge/TensorFlow-0d1117?style=flat-square&logo=tensorflow&logoColor=ff6f00" /> <img src="https://img.shields.io/badge/FAISS-0d1117?style=flat-square&logo=meta&logoColor=0081fb" /> <img src="https://img.shields.io/badge/MIT-0d1117?style=flat-square&logo=opensourceinitiative&logoColor=39d353" /></a>

</td>
<td width="50%" valign="top">

#### [🚗 AutoBnB](https://github.com/noelmartinnez/AutoBnB)

Airbnb-style vehicle rental platform — **final degree project, graded 9/10**. Full-stack app in **Java, Spring Boot and Hibernate** over PostgreSQL: vehicle listings, search, time-slot booking and dynamic pricing.

<a href="https://github.com/noelmartinnez/AutoBnB"><img src="https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=f89820" /> <img src="https://img.shields.io/badge/Spring_Boot-0d1117?style=flat-square&logo=springboot&logoColor=6db33f" /> <img src="https://img.shields.io/badge/Hibernate-0d1117?style=flat-square&logo=hibernate&logoColor=bcae79" /> <img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169e1" /></a>

</td>
</tr>
</table>

---

## 🧱 The stack, as a system

Not a wall of logos — this is roughly how the pieces I work with fit together.

```mermaid
flowchart TB
    subgraph EDGE["🌐 Edge"]
        A["REST APIs<br/>Spring Security"]
    end
    subgraph SVC["⚙️ Services"]
        B["Spring Boot<br/>Spring Cloud"]
        C["Camunda<br/>BPM"]
        D["RPA workers<br/>Node.js · Selenium"]
    end
    subgraph AI["🧠 AI layer"]
        E["Spring AI<br/>Azure AI Foundry"]
        F["vLLM<br/>Qwen · Gemma"]
        G["NER fine-tuning<br/>PyTorch · HuggingFace"]
    end
    subgraph DATA["🗄️ Data & messaging"]
        H["Kafka"]
        I["MySQL · PostgreSQL · Oracle"]
    end
    subgraph OPS["🚀 Platform"]
        J["Docker · Kubernetes"]
        K["Jenkins · Argo CD · Harbor"]
        L["JUnit · Mockito"]
    end

    A --> B
    B --> C
    B --> D
    B --> E
    E --> F
    G --> E
    B --> H
    H --> I
    B --> I
    SVC -.deployed by.-> OPS
    AI -.evaluated with.-> L

    style AI fill:#0d1117,stroke:#39d353,color:#e6edf3
    style EDGE fill:#0d1117,stroke:#1f6feb,color:#e6edf3
    style SVC fill:#0d1117,stroke:#1f6feb,color:#e6edf3
    style DATA fill:#0d1117,stroke:#8957e5,color:#e6edf3
    style OPS fill:#0d1117,stroke:#8957e5,color:#e6edf3
```

<div align="center">

| | |
|---|---|
| **Languages** | ![Java](https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=f89820) ![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776ab) ![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=339933) ![SQL](https://img.shields.io/badge/SQL-0d1117?style=flat-square&logo=databricks&logoColor=58a6ff) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-0d1117?style=flat-square&logo=springboot&logoColor=6db33f) ![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-0d1117?style=flat-square&logo=spring&logoColor=6db33f) ![Hibernate](https://img.shields.io/badge/Hibernate-0d1117?style=flat-square&logo=hibernate&logoColor=bcae79) ![Camunda](https://img.shields.io/badge/Camunda_BPM-0d1117?style=flat-square&logo=camunda&logoColor=fc5d0d) |
| **AI & LLMs** | ![Spring AI](https://img.shields.io/badge/Spring_AI-0d1117?style=flat-square&logo=spring&logoColor=6db33f) ![Azure AI](https://img.shields.io/badge/Azure_AI_Foundry-0d1117?style=flat-square&logo=microsoftazure&logoColor=0078d4) ![vLLM](https://img.shields.io/badge/vLLM-0d1117?style=flat-square&logo=lightning&logoColor=ffd21e) ![PyTorch](https://img.shields.io/badge/PyTorch-0d1117?style=flat-square&logo=pytorch&logoColor=ee4c2c) ![HuggingFace](https://img.shields.io/badge/Hugging_Face-0d1117?style=flat-square&logo=huggingface&logoColor=ffd21e) |
| **Data & messaging** | ![Kafka](https://img.shields.io/badge/Kafka-0d1117?style=flat-square&logo=apachekafka&logoColor=e6edf3) ![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=4479a1) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169e1) ![Oracle](https://img.shields.io/badge/Oracle-0d1117?style=flat-square&logo=oracle&logoColor=f80000) |
| **Platform & testing** | ![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ed) ![Kubernetes](https://img.shields.io/badge/Kubernetes-0d1117?style=flat-square&logo=kubernetes&logoColor=326ce5) ![Jenkins](https://img.shields.io/badge/Jenkins-0d1117?style=flat-square&logo=jenkins&logoColor=d24939) ![Argo CD](https://img.shields.io/badge/Argo_CD-0d1117?style=flat-square&logo=argo&logoColor=ef7b4d) ![JUnit](https://img.shields.io/badge/JUnit-0d1117?style=flat-square&logo=junit5&logoColor=25a162) |

</div>

---

## 🐍 Contributions

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/noelmartinnez/noelmartinnez/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/noelmartinnez/noelmartinnez/output/github-snake.svg" width="95%" alt="contribution snake" />
</picture>

</div>

---

## 📬 Get in touch

<div align="center">

<a href="https://noelmartinez.es"><img src="https://img.shields.io/badge/Portfolio-noelmartinez.es-0d1117?style=for-the-badge&logo=googlechrome&logoColor=39d353&labelColor=0d1117" /></a>
<a href="https://linkedin.com/in/noelmartinezpomares"><img src="https://img.shields.io/badge/LinkedIn-noelmartinezpomares-0d1117?style=for-the-badge&logo=linkedin&logoColor=1f6feb&labelColor=0d1117" /></a>
<a href="mailto:noelmartinezpomares@gmail.com"><img src="https://img.shields.io/badge/Email-get_in_touch-0d1117?style=for-the-badge&logo=gmail&logoColor=ea4335&labelColor=0d1117" /></a>

<br/><br/>

<sub>Universidad de Alicante · BSc Computer Engineering, Software Engineering track</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&height=90&section=footer&color=0:39d353,55:1f6feb,100:0d1117" width="100%" />

</div>
