<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=170&color=0:0d1117,40:1f6feb,100:8957e5&text=Noel%20Mart%C3%ADnez&fontColor=e6edf3&fontSize=48&fontAlignY=36&desc=Backend%20Software%20Engineer%20%C2%B7%20Java%20y%20Spring%20%C2%B7%20LLMs%20en%20producci%C3%B3n&descAlignY=58&descSize=15&animation=fadeIn" width="100%" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3000&pause=1000&color=A371F7&center=true&vCenter=true&width=620&lines=Backends+en+Java+y+Spring+Boot+que+no+te+despiertan+a+las+3am;LLMs+con+n%C3%BAmeros+delante%3A+F1%2C+latencia%2C+coste+por+llamada;Desplegado+en+banca+y+en+producto+europeo+regulado" alt="typing" />

</div>

---

Construyo **sistemas backend donde la IA tiene que aguantar en producción de verdad**: pipelines documentales para banca, herramientas europeas de privacidad, entornos regulados donde "el modelo suele acertar" no vale como respuesta.

La mayor parte de mi trabajo es la parte poco vistosa que rodea al modelo: microservicios, esquemas, evaluación, coste por inferencia. El modelo es una caja del diagrama; las otras doce son la razón de que llegue a producción.

```
Alicante, España  ·  Java + Spring Boot + IA aplicada  ·  Español (nativo) / Inglés (B1, mejorando a diario)
```

---

## Trabajo destacado

<table>
<tr>
<td width="50%" valign="top">
<br/>

&nbsp;&nbsp;**PrivacyShield**<br/>
&nbsp;&nbsp;<sub>SaaS europeo de anonimización con IA</sub>

Fine-tuning de modelos NER (PyTorch, Hugging Face) hasta **F1 90%**, y después capa de LLMs con Spring AI y Azure AI Foundry hasta **F1 99%** sobre más de 20 tipos de entidades.

Lideré el backend: microservicios Java, Spring Boot, Kafka y MySQL, versionados para Kubernetes.

<br/>
</td>
<td width="50%" valign="top">
<br/>

&nbsp;&nbsp;**SimplyData**<br/>
&nbsp;&nbsp;<sub>Intelligent Document Processing para banca</sub>

Microservicios Java junto a LLMs open-source (Qwen, Gemma) servidos con vLLM para extracción de información, en una plataforma en producción del sector bancario.

<br/>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<br/>

&nbsp;&nbsp;**RPA documental**<br/>
&nbsp;&nbsp;<sub>Automatización de trámites</sub>

Microservicios Java y MySQL que transmitían XML a bots RPA en Node.js (Selenium, Puppeteer) que rellenaban los trámites web automáticamente.

&nbsp;&nbsp;**~400 documentos al mes** y **~100 horas manuales ahorradas**.

<br/>
</td>
<td width="50%" valign="top">
<br/>

&nbsp;&nbsp;**HUNTERS**<br/>
&nbsp;&nbsp;<sub>Intranet corporativa</sub>

Microservicios en Java, Spring Boot y Spring Cloud sobre PostgreSQL y Oracle, con diseño de esquemas y optimización de consultas.

Modelado de procesos de negocio con Camunda (BPM), cobertura de tests hasta el **85%** (JUnit, Mockito), despliegue Docker sobre Kubernetes con Jenkins, Harbor y Argo CD.

<br/>
</td>
</tr>
</table>

---

## Proyectos propios

<table>
<tr>
<td width="50%" valign="top">
<br/>

&nbsp;&nbsp;**[ImgTwin](https://github.com/noelmartinnez/ImgTwin)**

Detección y limpieza de imágenes duplicadas o similares.

Extrae embeddings con MobileNet (TensorFlow), reduce dimensionalidad con PCA e indexa en FAISS para búsqueda de vecinos cercanos.

Incluye interfaz para revisar y borrar coincidencias, y corre en CPU sin necesidad de GPU.

&nbsp;&nbsp;<img src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776ab" /> <img src="https://img.shields.io/badge/TensorFlow-0d1117?style=flat-square&logo=tensorflow&logoColor=ff6f00" /> <img src="https://img.shields.io/badge/FAISS-0d1117?style=flat-square&logo=meta&logoColor=0081fb" /> <img src="https://img.shields.io/badge/MIT-0d1117?style=flat-square&logo=opensourceinitiative&logoColor=a371f7" />

<br/>
</td>
<td width="50%" valign="top">
<br/>

&nbsp;&nbsp;**[AutoBnB](https://github.com/noelmartinnez/AutoBnB)**

TFG calificado con 9/10.

Plataforma de alquiler de vehículos estilo Airbnb.

Aplicación full-stack en Java, Spring Boot e Hibernate sobre PostgreSQL: publicación de vehículos, búsqueda, reserva por franjas horarias y precios dinámicos.

&nbsp;&nbsp;<img src="https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=f89820" /> <img src="https://img.shields.io/badge/Spring_Boot-0d1117?style=flat-square&logo=springboot&logoColor=6db33f" /> <img src="https://img.shields.io/badge/Hibernate-0d1117?style=flat-square&logo=hibernate&logoColor=bcae79" /> <img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169e1" />

<br/>
</td>
</tr>
</table>

---

## Competencias Técnicas

```mermaid
flowchart TB
    CLIENT(["Cliente"]) --> EDGE

    subgraph EDGE["Edge"]
        direction LR
        A1["APIs REST"] --- A2["Spring Security"]
    end

    EDGE --> SVC

    subgraph SVC["Servicios"]
        direction LR
        B1["Spring Boot<br/>Spring Cloud"] --- B2["Camunda BPM"] --- B3["Bots RPA<br/>Node.js, Selenium, Puppeteer"]
    end

    SVC --> IA
    SVC --> DATOS

    subgraph IA["IA y LLMs"]
        direction LR
        C3["Fine-tuning NER<br/>PyTorch, Hugging Face"] --> C1["Spring AI<br/>Azure AI Foundry"] --> C2["vLLM<br/>Qwen, Gemma"]
    end

    subgraph DATOS["Datos y mensajeria"]
        direction LR
        D1["Kafka"] --> D2["MySQL, PostgreSQL, Oracle"]
    end

    SVC -.->|"build, test y despliegue"| PLAT

    subgraph PLAT["Plataforma"]
        direction LR
        E1["Docker<br/>Kubernetes"] --- E2["Jenkins<br/>Argo CD, Harbor"] --- E3["JUnit<br/>Mockito"]
    end

    style EDGE fill:#0d1117,stroke:#58a6ff,color:#e6edf3
    style SVC fill:#0d1117,stroke:#58a6ff,color:#e6edf3
    style IA fill:#0d1117,stroke:#a371f7,color:#e6edf3
    style DATOS fill:#0d1117,stroke:#8957e5,color:#e6edf3
    style PLAT fill:#0d1117,stroke:#8957e5,color:#e6edf3
```

<div align="center">

| | |
|---|---|
| **Lenguajes** | ![Java](https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=f89820) ![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776ab) ![Node.js](https://img.shields.io/badge/JavaScript_(Node.js)-0d1117?style=flat-square&logo=nodedotjs&logoColor=339933) ![SQL](https://img.shields.io/badge/SQL-0d1117?style=flat-square) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-0d1117?style=flat-square&logo=springboot&logoColor=6db33f) ![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-0d1117?style=flat-square&logo=spring&logoColor=6db33f) ![Spring Security](https://img.shields.io/badge/Spring_Security-0d1117?style=flat-square&logo=springsecurity&logoColor=6db33f) ![Hibernate](https://img.shields.io/badge/Hibernate-0d1117?style=flat-square&logo=hibernate&logoColor=bcae79) ![Camunda](https://img.shields.io/badge/Camunda_(BPM)-0d1117?style=flat-square&logo=camunda&logoColor=fc5d0d) ![APIs REST](https://img.shields.io/badge/APIs_REST-0d1117?style=flat-square) ![Microservicios](https://img.shields.io/badge/Microservicios-0d1117?style=flat-square) |
| **Datos y Mensajería** | ![Kafka](https://img.shields.io/badge/Kafka-0d1117?style=flat-square&logo=apachekafka&logoColor=e6edf3) ![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=4479a1) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169e1) ![Oracle](https://img.shields.io/badge/Oracle-0d1117?style=flat-square&logo=oracle&logoColor=f80000) |
| **IA y LLMs** | ![Spring AI](https://img.shields.io/badge/Spring_AI-0d1117?style=flat-square&logo=spring&logoColor=6db33f) ![Azure AI Foundry](https://img.shields.io/badge/Azure_AI_Foundry-0d1117?style=flat-square&logo=microsoftazure&logoColor=0078d4) ![vLLM](https://img.shields.io/badge/vLLM-0d1117?style=flat-square&logo=lightning&logoColor=ffd21e) ![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-0d1117?style=flat-square) ![NER](https://img.shields.io/badge/NER-0d1117?style=flat-square) ![PyTorch](https://img.shields.io/badge/PyTorch-0d1117?style=flat-square&logo=pytorch&logoColor=ee4c2c) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-0d1117?style=flat-square&logo=huggingface&logoColor=ffd21e) |
| **DevOps, Testing y RPA** | ![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ed) ![Kubernetes](https://img.shields.io/badge/Kubernetes-0d1117?style=flat-square&logo=kubernetes&logoColor=326ce5) ![Jenkins](https://img.shields.io/badge/Jenkins-0d1117?style=flat-square&logo=jenkins&logoColor=d24939) ![Harbor](https://img.shields.io/badge/Harbor-0d1117?style=flat-square&logo=harbor&logoColor=60b932) ![Argo CD](https://img.shields.io/badge/Argo_CD-0d1117?style=flat-square&logo=argo&logoColor=ef7b4d) ![JUnit](https://img.shields.io/badge/JUnit-0d1117?style=flat-square&logo=junit5&logoColor=25a162) ![Mockito](https://img.shields.io/badge/Mockito-0d1117?style=flat-square) ![Selenium](https://img.shields.io/badge/Selenium-0d1117?style=flat-square&logo=selenium&logoColor=43b02a) ![Puppeteer](https://img.shields.io/badge/Puppeteer-0d1117?style=flat-square&logo=puppeteer&logoColor=40b5a4) |

</div>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/noelmartinnez/noelmartinnez/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/noelmartinnez/noelmartinnez/output/github-snake.svg" width="95%" alt="contribution snake" />
</picture>

</div>

---

## Contacto

<div align="center">

<a href="https://noelmartinez.es"><img src="https://img.shields.io/badge/noelmartinez.es-0d1117?style=for-the-badge&logo=googlechrome&logoColor=a371f7&labelColor=0d1117" /></a>
&nbsp;
<a href="https://linkedin.com/in/noelmartinezpomares"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&labelColor=0d1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iJTIzYTM3MWY3Ij48cGF0aCBkPSJNMjAuNDQ3IDIwLjQ1MmgtMy41NTR2LTUuNTY5YzAtMS4zMjgtLjAyNy0zLjAzNy0xLjg1Mi0zLjAzNy0xLjg1MyAwLTIuMTM2IDEuNDQ1LTIuMTM2IDIuOTM5djUuNjY3SDkuMzUxVjloMy40MTR2MS41NjFoLjA0NmMuNDc3LS45IDEuNjM3LTEuODUgMy4zNy0xLjg1IDMuNjAxIDAgNC4yNjcgMi4zNyA0LjI2NyA1LjQ1NXY2LjI4NnpNNS4zMzcgNy40MzNjLTEuMTQ0IDAtMi4wNjMtLjkyNi0yLjA2My0yLjA2NSAwLTEuMTM4LjkyLTIuMDYzIDIuMDYzLTIuMDYzIDEuMTQgMCAyLjA2NC45MjUgMi4wNjQgMi4wNjMgMCAxLjEzOS0uOTI1IDIuMDY1LTIuMDY0IDIuMDY1em0xLjc4MiAxMy4wMTlIMy41NTVWOWgzLjU2NHYxMS40NTJ6TTIyLjIyNSAwSDEuNzcxQy43OTIgMCAwIC43NzQgMCAxLjcyOXYyMC41NDJDMCAyMy4yMjcuNzkyIDI0IDEuNzcxIDI0aDIwLjQ1MUMyMy4yIDI0IDI0IDIzLjIyNyAyNCAyMi4yNzFWMS43MjlDMjQgLjc3NCAyMy4yIDAgMjIuMjI1IDB6Ii8%2BPC9zdmc%2B" /></a>
&nbsp;
<a href="mailto:noelmartinezpomares@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=a371f7&labelColor=0d1117" /></a>

<br/><br/>

<sub>Universidad de Alicante · Grado en Ingeniería Informática, especialidad en Ingeniería del Software</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&height=90&section=footer&color=0:8957e5,60:1f6feb,100:0d1117" width="100%" />

</div>
