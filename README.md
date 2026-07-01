<h1 align="center">Nicolás Pérez Llanos</h1>

<p align="center">
  Ingeniería de Computadores · URJC Madrid<br/>
  Buscando prácticas en IA / HPC · Septiembre 2026
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nicolasperezllanos" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-nicolasperezllanos-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:perezllanosnicolas@gmail.com">
    <img src="https://img.shields.io/badge/Email-perezllanosnicolas@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

***

## Sobre mí

Estudiante de 4º de Ingeniería de Computadores en la URJC, cursando 3º y 4º de forma simultánea. Me muevo en la intersección entre la ingeniería de bajo nivel y la inteligencia artificial aplicada: desde motores de cómputo paralelo en C++ con OpenMP y MPI hasta pipelines RAG con LLMs y estrategias de retrieval avanzadas.

***

## Stack tecnológico

**IA & Machine Learning**








**HPC & Sistemas**






**DevOps & Cloud**






***

## Proyectos destacados

### [Technical Document Assistant](https://github.com/perezllanosnicolas/technical-doc-assistant)
Sistema RAG local para Q&A sobre documentación técnica (papers, especificaciones, benchmarks).
- **Pipeline**: PyMuPDF → Chunking → ChromaDB → Ensemble Retriever (BM25 + semántico) → LLaMA 3 vía Groq
- **Resultado benchmark**: Ensemble recupera +2 chunks exclusivos por query frente a búsqueda semántica pura
- **Stack**: Python · LangChain · HuggingFace Embeddings · ChromaDB · Streamlit · Docker

### [HPC KMeans C++](https://github.com/perezllanosnicolas/HPC-KMeans-CPP)
Motor de cómputo híbrido para el algoritmo K-Means con paralelización a dos niveles: memoria compartida (OpenMP) y memoria distribuida (MPI).
- Soporte para ejecución secuencial, paralela OpenMP, paralela MPI e híbrida OpenMP+MPI
- Containerizado con Docker para reproducibilidad del entorno HPC
- **Stack**: C++ · OpenMP · MPI · Makefile · Docker

### Visión Artificial — Detección y OCR de Señales de Tráfico
Dos proyectos académicos consecutivos de la asignatura de Visión Artificial:
- **[Parte I](https://github.com/perezllanosnicolas/Traffic-Sign-Detection-CV)**: Detector de señales mediante MSER + Hough, evaluado con accuracy, F1-score y matriz de confusión
- **[Parte II](https://github.com/perezllanosnicolas/Traffic-Sign-OCR-System)**: Integración de OCR + clasificadores LDA y Naive Bayes sobre el pipeline anterior
- **Stack**: Python · OpenCV · NumPy · scikit-learn

***

## Certificaciones

| Certificación | Emisor | Estado |
|---|---|---|
| Getting Started with Artificial Intelligence | IBM SkillsBuild | ✅ Obtenida |
| Data Classification and Summarization Using IBM Granite | IBM SkillsBuild | ✅ Obtenida |
| Build Your First Chatbot | IBM SkillsBuild | ✅ Obtenida |
| AWS Certified Developer – Associate (DVA-C02) | Amazon Web Services | 🔄 En preparación |
| AWS Certified Solutions Architect – Associate (SAA-C03) | Amazon Web Services | 🔄 En preparación |

***

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=perezllanosnicolas&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=false" height="150" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=perezllanosnicolas&layout=compact&theme=default&hide_border=true" height="150" alt="Top Languages"/>
</p>
