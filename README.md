<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=170&color=0:0d1117,45:1f6feb,100:39d353&text=Noel%20Mart%C3%ADnez&fontColor=e6edf3&fontSize=48&fontAlignY=36&desc=Backend%20Software%20Engineer%20%C2%B7%20Java%20y%20Spring%20%C2%B7%20LLMs%20en%20producci%C3%B3n&descAlignY=58&descSize=15&animation=fadeIn" width="100%" />

<a href="https://github.com/noelmartinnez/noelmartinnez/blob/main/README.en.md"><img src="https://img.shields.io/badge/🇬🇧_English-21262d?style=flat-square&labelColor=0d1117" /></a>
<a href="https://github.com/noelmartinnez#readme"><img src="https://img.shields.io/badge/🇪🇸_Español-1f6feb?style=flat-square&labelColor=0d1117" /></a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3000&pause=1000&color=39D353&center=true&vCenter=true&width=620&lines=Backends+en+Java+y+Spring+Boot+que+no+te+despiertan+a+las+3am;LLMs+con+n%C3%BAmeros+delante%3A+F1%2C+latencia%2C+coste+por+llamada;Desplegado+en+banca+y+en+producto+europeo+regulado" alt="typing" />

</div>

---

Construyo **sistemas backend donde la IA tiene que aguantar en producción de verdad** — pipelines documentales para banca, herramientas europeas de privacidad, entornos regulados donde "el modelo suele acertar" no vale como respuesta.

La mayor parte de mi trabajo es la parte poco vistosa que rodea al modelo: microservicios, esquemas, evaluación, coste por inferencia. El modelo es una caja del diagrama; las otras doce son la razón de que llegue a producción.

```
Alicante, España  ·  Java + Spring Boot + IA aplicada  ·  Español (nativo) / Inglés (B1, mejorando a diario)
```

---

## 🧭 Trabajo destacado

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ PrivacyShield
**SaaS europeo de anonimización con IA** · Fundamentia

Fine-tuning de modelos NER (PyTorch, Hugging Face) hasta **F1 90%**, y después capa de LLMs con Spring AI + Azure AI Foundry hasta **F1 99%** sobre más de 20 tipos de entidades.

Lideré el backend: microservicios Java, Spring Boot, Kafka y MySQL, versionados para Kubernetes. Optimicé prompts midiendo precision, recall, latencia **y coste** — la caché redujo tiempos y gasto de inferencia.

`Java` `Spring AI` `Kafka` `PyTorch` `Azure AI Foundry`

</td>
<td width="50%" valign="top">

### 🏦 SimplyData
**Intelligent Document Processing para banca** · Fundamentia

Microservicios Java junto a LLMs open-source (**Qwen, Gemma**) servidos con **vLLM** para extracción de información, en una plataforma en producción del sector bancario.

Modelos self-hosted, porque mandar documentos de cliente a una API de terceros nunca fue una opción.

`Java` `vLLM` `Qwen` `Gemma` `Document AI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 RPA documental
**Automatización de trámites** · Fundamentia

Microservicios Java + MySQL que transmitían XML a bots RPA en Node.js (Selenium, Puppeteer) que rellenaban los trámites web automáticamente.

**~400 documentos/mes · ~100 horas manuales ahorradas.**

`Java` `Node.js` `Selenium` `Puppeteer`

</td>
<td width="50%" valign="top">

### 🏢 HUNTERS
**Intranet corporativa** · Altia Consultores

Microservicios en Java, Spring Boot y Spring Cloud sobre PostgreSQL y Oracle — diseño de esquemas y optimización de consultas incluidos.

Modelado de procesos de negocio con **Camunda (BPM)**, cobertura de tests hasta el **85%** (JUnit, Mockito), despliegue Docker → Kubernetes con Jenkins, Harbor y Argo CD.

`Spring Cloud` `Camunda` `Argo CD` `Jenkins`

</td>
</tr>
</table>

---

## 🧪 Proyectos propios

<table>
<tr>
<td width="50%" valign="top">

#### [🖼️ ImgTwin](https://github.com/noelmartinnez/ImgTwin)

Detección y limpieza de imágenes duplicadas o similares. Extrae embeddings con **MobileNet** (TensorFlow), reduce dimensionalidad con **PCA** e indexa en **FAISS** para búsqueda de vecinos cercanos. Incluye interfaz para revisar y borrar coincidencias, y corre en CPU sin necesidad de GPU.

<a href="https://github.com/noelmartinnez/ImgTwin"><img src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776ab" /> <img src="https://img.shields.io/badge/TensorFlow-0d1117?style=flat-square&logo=tensorflow&logoColor=ff6f00" /> <img src="https://img.shields.io/badge/FAISS-0d1117?style=flat-square&logo=meta&logoColor=0081fb" /> <img src="https://img.shields.io/badge/MIT-0d1117?style=flat-square&logo=opensourceinitiative&logoColor=39d353" /></a>

</td>
<td width="50%" valign="top">

#### [🚗 AutoBnB](https://github.com/noelmartinnez/AutoBnB)

Plataforma de alquiler de vehículos estilo Airbnb — **TFG calificado con 9/10**. Aplicación full-stack en **Java, Spring Boot e Hibernate** sobre PostgreSQL: publicación de vehículos, búsqueda, reserva por franjas horarias y precios dinámicos.

<a href="https://github.com/noelmartinnez/AutoBnB"><img src="https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=f89820" /> <img src="https://img.shields.io/badge/Spring_Boot-0d1117?style=flat-square&logo=springboot&logoColor=6db33f" /> <img src="https://img.shields.io/badge/Hibernate-0d1117?style=flat-square&logo=hibernate&logoColor=bcae79" /> <img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169e1" /></a>

</td>
</tr>
</table>

---

## 🧱 El stack, como sistema

No un muro de logos — así encajan más o menos las piezas con las que trabajo.

```mermaid
flowchart TB
    subgraph EDGE["🌐 Edge"]
        A["APIs REST<br/>Spring Security"]
    end
    subgraph SVC["⚙️ Servicios"]
        B["Spring Boot<br/>Spring Cloud"]
        C["Camunda<br/>BPM"]
        D["Bots RPA<br/>Node.js · Selenium"]
    end
    subgraph AI["🧠 Capa de IA"]
        E["Spring AI<br/>Azure AI Foundry"]
        F["vLLM<br/>Qwen · Gemma"]
        G["Fine-tuning NER<br/>PyTorch · HuggingFace"]
    end
    subgraph DATA["🗄️ Datos y mensajería"]
        H["Kafka"]
        I["MySQL · PostgreSQL · Oracle"]
    end
    subgraph OPS["🚀 Plataforma"]
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
    SVC -.desplegado por.-> OPS
    AI -.evaluado con.-> L

    style AI fill:#0d1117,stroke:#39d353,color:#e6edf3
    style EDGE fill:#0d1117,stroke:#1f6feb,color:#e6edf3
    style SVC fill:#0d1117,stroke:#1f6feb,color:#e6edf3
    style DATA fill:#0d1117,stroke:#8957e5,color:#e6edf3
    style OPS fill:#0d1117,stroke:#8957e5,color:#e6edf3
```

<div align="center">

| | |
|---|---|
| **Lenguajes** | ![Java](https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=f89820) ![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776ab) ![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=339933) ![SQL](https://img.shields.io/badge/SQL-0d1117?style=flat-square&logo=databricks&logoColor=58a6ff) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-0d1117?style=flat-square&logo=springboot&logoColor=6db33f) ![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-0d1117?style=flat-square&logo=spring&logoColor=6db33f) ![Hibernate](https://img.shields.io/badge/Hibernate-0d1117?style=flat-square&logo=hibernate&logoColor=bcae79) ![Camunda](https://img.shields.io/badge/Camunda_BPM-0d1117?style=flat-square&logo=camunda&logoColor=fc5d0d) |
| **IA y LLMs** | ![Spring AI](https://img.shields.io/badge/Spring_AI-0d1117?style=flat-square&logo=spring&logoColor=6db33f) ![Azure AI](https://img.shields.io/badge/Azure_AI_Foundry-0d1117?style=flat-square&logo=microsoftazure&logoColor=0078d4) ![vLLM](https://img.shields.io/badge/vLLM-0d1117?style=flat-square&logo=lightning&logoColor=ffd21e) ![PyTorch](https://img.shields.io/badge/PyTorch-0d1117?style=flat-square&logo=pytorch&logoColor=ee4c2c) ![HuggingFace](https://img.shields.io/badge/Hugging_Face-0d1117?style=flat-square&logo=huggingface&logoColor=ffd21e) |
| **Datos y mensajería** | ![Kafka](https://img.shields.io/badge/Kafka-0d1117?style=flat-square&logo=apachekafka&logoColor=e6edf3) ![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=4479a1) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169e1) ![Oracle](https://img.shields.io/badge/Oracle-0d1117?style=flat-square&logo=oracle&logoColor=f80000) |
| **Plataforma y testing** | ![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ed) ![Kubernetes](https://img.shields.io/badge/Kubernetes-0d1117?style=flat-square&logo=kubernetes&logoColor=326ce5) ![Jenkins](https://img.shields.io/badge/Jenkins-0d1117?style=flat-square&logo=jenkins&logoColor=d24939) ![Argo CD](https://img.shields.io/badge/Argo_CD-0d1117?style=flat-square&logo=argo&logoColor=ef7b4d) ![JUnit](https://img.shields.io/badge/JUnit-0d1117?style=flat-square&logo=junit5&logoColor=25a162) |

</div>

---

## 🐍 Contribuciones

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/noelmartinnez/noelmartinnez/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/noelmartinnez/noelmartinnez/output/github-snake.svg" width="95%" alt="contribution snake" />
</picture>

</div>

---

## 📬 Contacto

<div align="center">

<a href="https://noelmartinez.es"><img src="https://img.shields.io/badge/Portfolio-noelmartinez.es-0d1117?style=for-the-badge&logo=googlechrome&logoColor=39d353&labelColor=0d1117" /></a>
<a href="https://linkedin.com/in/noelmartinezpomares"><img src="https://img.shields.io/badge/LinkedIn-noelmartinezpomares-0d1117?style=for-the-badge&logo=linkedin&logoColor=1f6feb&labelColor=0d1117" /></a>
<a href="mailto:noelmartinezpomares@gmail.com"><img src="https://img.shields.io/badge/Email-escr%C3%ADbeme-0d1117?style=for-the-badge&logo=gmail&logoColor=ea4335&labelColor=0d1117" /></a>

<br/><br/>

<sub>Universidad de Alicante · Grado en Ingeniería Informática, especialidad en Ingeniería del Software</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&height=90&section=footer&color=0:39d353,55:1f6feb,100:0d1117" width="100%" />

</div>
