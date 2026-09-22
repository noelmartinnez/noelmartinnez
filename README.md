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

**PrivacyShield**<br/>
<sub>SaaS europeo de anonimización con IA</sub>

Fine-tuning de modelos NER (PyTorch, Hugging Face) hasta **F1 90%**, y después capa de LLMs con Spring AI y Azure AI Foundry hasta **F1 99%** sobre más de 20 tipos de entidades.

Lideré el backend: microservicios Java, Spring Boot, Kafka y MySQL, versionados para Kubernetes. Optimicé prompts midiendo precision, recall, latencia y coste; la caché redujo tiempos y gasto de inferencia.

</td>
<td width="50%" valign="top">

**SimplyData**<br/>
<sub>Intelligent Document Processing para banca</sub>

Microservicios Java junto a LLMs open-source (Qwen, Gemma) servidos con vLLM para extracción de información, en una plataforma en producción del sector bancario.

Modelos self-hosted, porque mandar documentos de cliente a una API de terceros nunca fue una opción.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**RPA documental**<br/>
<sub>Automatización de trámites</sub>

Microservicios Java y MySQL que transmitían XML a bots RPA en Node.js (Selenium, Puppeteer) que rellenaban los trámites web automáticamente.

**~400 documentos al mes** y **~100 horas manuales ahorradas**.

</td>
<td width="50%" valign="top">

**HUNTERS**<br/>
<sub>Intranet corporativa</sub>

Microservicios en Java, Spring Boot y Spring Cloud sobre PostgreSQL y Oracle, con diseño de esquemas y optimización de consultas.

Modelado de procesos de negocio con Camunda (BPM), cobertura de tests hasta el **85%** (JUnit, Mockito), despliegue Docker sobre Kubernetes con Jenkins, Harbor y Argo CD.

</td>
</tr>
</table>

---

## Proyectos propios

<table>
<tr>
<td width="50%" valign="top">

**[ImgTwin](https://github.com/noelmartinnez/ImgTwin)**

Detección y limpieza de imágenes duplicadas o similares. Extrae embeddings con MobileNet (TensorFlow), reduce dimensionalidad con PCA e indexa en FAISS para búsqueda de vecinos cercanos. Incluye interfaz para revisar y borrar coincidencias, y corre en CPU sin necesidad de GPU.

<img src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776ab" /> <img src="https://img.shields.io/badge/TensorFlow-0d1117?style=flat-square&logo=tensorflow&logoColor=ff6f00" /> <img src="https://img.shields.io/badge/FAISS-0d1117?style=flat-square&logo=meta&logoColor=0081fb" /> <img src="https://img.shields.io/badge/MIT-0d1117?style=flat-square&logo=opensourceinitiative&logoColor=a371f7" />

</td>
<td width="50%" valign="top">

**[AutoBnB](https://github.com/noelmartinnez/AutoBnB)**

Plataforma de alquiler de vehículos estilo Airbnb, TFG calificado con 9/10. Aplicación full-stack en Java, Spring Boot e Hibernate sobre PostgreSQL: publicación de vehículos, búsqueda, reserva por franjas horarias y precios dinámicos.

<img src="https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=f89820" /> <img src="https://img.shields.io/badge/Spring_Boot-0d1117?style=flat-square&logo=springboot&logoColor=6db33f" /> <img src="https://img.shields.io/badge/Hibernate-0d1117?style=flat-square&logo=hibernate&logoColor=bcae79" /> <img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169e1" />

</td>
</tr>
</table>

---

## El stack, como sistema

```mermaid
flowchart TB
    subgraph EDGE["Edge"]
        A["APIs REST<br/>Spring Security"]
    end
    subgraph SVC["Servicios"]
        B["Spring Boot<br/>Spring Cloud"]
        C["Camunda<br/>BPM"]
        D["Bots RPA<br/>Node.js · Selenium"]
    end
    subgraph AI["Capa de IA"]
        E["Spring AI<br/>Azure AI Foundry"]
        F["vLLM<br/>Qwen · Gemma"]
        G["Fine-tuning NER<br/>PyTorch · HuggingFace"]
    end
    subgraph DATA["Datos y mensajería"]
        H["Kafka"]
        I["MySQL · PostgreSQL · Oracle"]
    end
    subgraph OPS["Plataforma"]
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

    style AI fill:#0d1117,stroke:#a371f7,color:#e6edf3
    style EDGE fill:#0d1117,stroke:#58a6ff,color:#e6edf3
    style SVC fill:#0d1117,stroke:#58a6ff,color:#e6edf3
    style DATA fill:#0d1117,stroke:#8957e5,color:#e6edf3
    style OPS fill:#0d1117,stroke:#8957e5,color:#e6edf3
```

<div align="center">

<a href="https://mermaid.live/view#pako:eNqdVFtvmzAU_isWeU26RlWbLpoqkUAuTdLSku1l7MHBB0IDdmTsVKzqf98xhA6qNtLGE-d8F382x7xYoWBgDYkVpeI53FKpyHoUcIJPrjexpPstcZ2p-zOwXBZDYP2qQPPY2LS9eU4eXX_9bSO_3Ph7mfCY-BBqmajijQ2cvfP0f4xR7YM8JGEi8pbvyCCV00gI1XQep0KzFtnYjGmmOaMlceStWriD-EgoDOnZJeEON3z2lJNAn59vBpg1BZ7o7ERWe16usaeEAZnbLXv3b1Z7Xvrbv7UELMhEYChZtOgTpB-Wy1XJfHgGXseYQpbRFnWK1EnCoac0N_Z37mOp8oq1kOG2Fs50HCM8oSGc2IJjr83XcqgSOSlIBjynTyCNB7D2ujPkLWi0a3fNEawK_2FZr-uJXMUSGp17ScP0VIh7z0cXL6WKRkK-2-6tiSfCHcjab6E3IDkoaE_HAom3wHcJf_uGtowFGTtvR0LlRsiWaGlE33mias4Kl0qUaKetXm3S692Q4yUYlcW4WTjNwq0KtywmVTFtIhVtVhWzspg3kWOB94H0zhjk-xRiygTZC3mGMJ7ZMdUccTjQVBs0FNygyzpzroq0HLooSdNh55z1-_1BN1dS7GDYoReDfjTohiIVctiBK2DRRVNnLvjHystrehVFnytN7P8SmoH8WHn99XIAl58r8UT-RWh1iZUBTlvCzG_uJbDUFjIc0yEJLEblLrBeDYdqJfyCh9hXUgN29J5RBU5CcXqzY_v1D80aiBs"><img src="https://img.shields.io/badge/Abrir_diagrama_interactivo-8957e5?style=for-the-badge&logoColor=white&labelColor=0d1117" alt="Diagrama interactivo" /></a>

<sub>Arrastra para mover, rueda del ratón para acercar y alejar</sub>

</div>

<div align="center">

| | |
|---|---|
| **Lenguajes** | ![Java](https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=f89820) ![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776ab) ![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=339933) ![SQL](https://img.shields.io/badge/SQL-0d1117?style=flat-square&logo=databricks&logoColor=a371f7) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-0d1117?style=flat-square&logo=springboot&logoColor=6db33f) ![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-0d1117?style=flat-square&logo=spring&logoColor=6db33f) ![Hibernate](https://img.shields.io/badge/Hibernate-0d1117?style=flat-square&logo=hibernate&logoColor=bcae79) ![Camunda](https://img.shields.io/badge/Camunda_BPM-0d1117?style=flat-square&logo=camunda&logoColor=fc5d0d) |
| **IA y LLMs** | ![Spring AI](https://img.shields.io/badge/Spring_AI-0d1117?style=flat-square&logo=spring&logoColor=6db33f) ![Azure AI](https://img.shields.io/badge/Azure_AI_Foundry-0d1117?style=flat-square&logo=microsoftazure&logoColor=0078d4) ![vLLM](https://img.shields.io/badge/vLLM-0d1117?style=flat-square&logo=lightning&logoColor=ffd21e) ![PyTorch](https://img.shields.io/badge/PyTorch-0d1117?style=flat-square&logo=pytorch&logoColor=ee4c2c) ![HuggingFace](https://img.shields.io/badge/Hugging_Face-0d1117?style=flat-square&logo=huggingface&logoColor=ffd21e) |
| **Datos y mensajería** | ![Kafka](https://img.shields.io/badge/Kafka-0d1117?style=flat-square&logo=apachekafka&logoColor=e6edf3) ![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=4479a1) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169e1) ![Oracle](https://img.shields.io/badge/Oracle-0d1117?style=flat-square&logo=oracle&logoColor=f80000) |
| **Plataforma y testing** | ![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ed) ![Kubernetes](https://img.shields.io/badge/Kubernetes-0d1117?style=flat-square&logo=kubernetes&logoColor=326ce5) ![Jenkins](https://img.shields.io/badge/Jenkins-0d1117?style=flat-square&logo=jenkins&logoColor=d24939) ![Argo CD](https://img.shields.io/badge/Argo_CD-0d1117?style=flat-square&logo=argo&logoColor=ef7b4d) ![JUnit](https://img.shields.io/badge/JUnit-0d1117?style=flat-square&logo=junit5&logoColor=25a162) |

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
<a href="https://linkedin.com/in/noelmartinezpomares"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=a371f7&labelColor=0d1117" /></a>
&nbsp;
<a href="mailto:noelmartinezpomares@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=a371f7&labelColor=0d1117" /></a>

<br/><br/>

<sub>Universidad de Alicante · Grado en Ingeniería Informática, especialidad en Ingeniería del Software</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&height=90&section=footer&color=0:8957e5,60:1f6feb,100:0d1117" width="100%" />

</div>
