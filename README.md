<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:2563eb&height=190&section=header&text=Sasmita%20Das&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%2FML%20%26%20Generative%20AI%20Developer&descAlignY=58&descSize=18&descColor=cbd5e1" width="100%"/>

<a href="https://github.com/D-sasmita">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2600&pause=900&color=3B82F6&center=true&vCenter=true&width=650&lines=Generative+AI+Developer;RAG+%2B+LLM+Fine-Tuning;Machine+Learning+Engineer;Python+Developer;Full-Stack+Developer" alt="Typing SVG" />
</a>

<br/>

![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=3776AB)
![Generative AI](https://img.shields.io/badge/Generative%20AI-000000?style=for-the-badge)
![LLMs](https://img.shields.io/badge/LLMs-000000?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-000000?style=for-the-badge)
![Fine--Tuning](https://img.shields.io/badge/Fine--Tuning-000000?style=for-the-badge)
![Full Stack](https://img.shields.io/badge/Full--Stack%20Dev-000000?style=for-the-badge)

</div>

<br/>

## About Me

- Final-year B.Tech Computer Engineering student, focused on AI/ML and Generative AI.
- Building practical Generative AI systems: retrieval-augmented generation, LLM fine-tuning with LoRA/PEFT, and prompt-driven applications.
- Comfortable across the ML lifecycle: data preprocessing, model training, evaluation, and deployment as an API or web app.
- Also build full-stack applications (MERN) when a project needs a complete product, not just a model.
- Currently exploring deeper RAG architectures and efficient fine-tuning techniques for smaller open-source LLMs.

<br/>

## Technical Focus

```
Python  ->  Machine Learning  ->  ML Deployment  ->  Generative AI (RAG + Fine-Tuning)  ->  Full-Stack Development
```

The heaviest current focus is on the left-to-right progression above: solid Python and ML fundamentals feeding into applied Generative AI work, with full-stack development as a complementary skill for shipping complete products.

<br/>

## Featured Projects

<table width="100%">
<tr>
<td width="100%">

### <a href="https://github.com/D-sasmita/pdf-qa-langchain">PDF Q&A with LangChain</a>
**Category: Retrieval-Augmented Generation (RAG)**

A RAG application that answers questions from uploaded PDFs, grounded strictly in document content instead of the model's own knowledge. PDFs are chunked, embedded, and indexed in FAISS; a retriever pulls the most relevant chunks for each question and passes them to an LLM for the final answer. Supports multiple documents at once, shows the source chunk and page number behind every answer, and explicitly returns "not found" when the answer isn't in the document.

`Python` `LangChain` `FAISS` `HuggingFace Embeddings` `Groq LLM` `Streamlit`

[Live Demo](https://pdf-app-langchain-ixvw2omx7spihzzmqtpp9q.streamlit.app/) &nbsp;|&nbsp; [Repository](https://github.com/D-sasmita/pdf-qa-langchain)

</td>
</tr>
<tr>
<td width="100%">

### <a href="https://github.com/D-sasmita/dialogue-summarizer-app">Dialogue Summarizer</a>
**Category: LLM Fine-Tuning / Generative AI**

A Flan-T5-base model fine-tuned with LoRA on the SAMSum dialogue dataset to summarize short chat-style conversations. Demonstrates adapting an existing open-source LLM to a specific task with parameter-efficient fine-tuning (PEFT) rather than only calling a hosted API. The LoRA adapter is attached to the base model at inference time inside a Streamlit interface.

`Python` `Hugging Face Transformers` `Flan-T5` `LoRA` `PEFT` `Streamlit`

[Live Demo](https://dialogue-summarizer-app-yhg4rto4v4ytsdqyjcfvkb.streamlit.app/) &nbsp;|&nbsp; [Model on Hugging Face](https://huggingface.co/Sasmita03/lora-samsum-summarizer) &nbsp;|&nbsp; [Repository](https://github.com/D-sasmita/dialogue-summarizer-app)

</td>
</tr>
<tr>
<td width="100%">

### <a href="https://github.com/D-sasmita/heart-lung-sound-classification">Heart & Lung Sound Classification</a>
**Category: Audio ML / Machine Learning**

An academic research project classifying heart and lung sound recordings using MFCC feature extraction and supervised machine learning. Covers dataset exploration and preprocessing on both the ICBHI lung sound dataset and the Pascal heart sound dataset, audio visualization, feature engineering, model notebooks, and an explainable AI (XAI) implementation to interpret model predictions. This is a research/academic classification project, not a diagnostic tool.

`Python` `MFCC` `Audio Preprocessing` `Feature Extraction` `Supervised ML` `Explainable AI`

[Repository](https://github.com/D-sasmita/heart-lung-sound-classification)

</td>
</tr>
<tr>
<td width="100%">

### <a href="https://github.com/D-sasmita/sms-spam-api">SMS Spam API</a>
**Category: Machine Learning Deployment**

A containerized FastAPI service that serves a trained SMS spam classifier as a REST endpoint instead of a UI. A message is converted to TF-IDF features and passed to a Multinomial Naive Bayes model, returning a spam/not-spam prediction with a confidence score. Packaged with Docker for a reproducible runtime, taking the companion classifier project from a script into a callable production-style service.

`Python` `FastAPI` `scikit-learn` `Docker` `REST API`

[Repository](https://github.com/D-sasmita/sms-spam-api)

</td>
</tr>
<tr>
<td width="100%">

### <a href="https://github.com/D-sasmita/sms-spam-detector">SMS Spam Detector</a>
**Category: Machine Learning Application**

A Streamlit app that classifies SMS messages as spam or not spam using a TF-IDF vectorizer and a Multinomial Naive Bayes model trained on the SMS Spam Collection dataset. Achieves 97.1% accuracy and 100% precision, with precision prioritized so legitimate messages are never misclassified as spam. This project and the SMS Spam API together cover both ends of ML delivery: an interactive application and a callable API.

`Python` `scikit-learn` `TF-IDF` `Naive Bayes` `Streamlit`

[Live Demo](https://sms-spam-detector-cmifw8qt3scwrfeb2xackh.streamlit.app/) &nbsp;|&nbsp; [Repository](https://github.com/D-sasmita/sms-spam-detector)

</td>
</tr>
<tr>
<td width="100%">

### <a href="https://github.com/D-sasmita/TimeX_MERN">TimeX</a>
**Category: Full-Stack Development**

A full-stack MERN e-commerce application for selling watches, with a customer storefront (product browsing, search, cart, checkout, order history) and a separate admin dashboard for managing products, orders, and store analytics. Includes JWT-based authentication, role-based admin access, Cloudinary image uploads for products, and an AI watch-finder feature that recommends products from the live MongoDB catalog based on a natural-language query.

`MongoDB` `Express.js` `React` `Node.js` `REST APIs` `JWT Authentication`

[Live Demo](https://timex-frontend-npuy.onrender.com/) &nbsp;|&nbsp; [Repository](https://github.com/D-sasmita/TimeX_MERN)

</td>
</tr>
</table>

<br/>

## Skills

**Generative AI**

![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat-square)
![HuggingFace](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![RAG](https://img.shields.io/badge/RAG-000000?style=flat-square)
![LoRA](https://img.shields.io/badge/LoRA-000000?style=flat-square)
![PEFT](https://img.shields.io/badge/PEFT-000000?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-000000?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-000000?style=flat-square)

**AI / Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Backend / ML Deployment**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-000000?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Full-Stack Development**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)

<br/>

## GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=D-sasmita&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Sasmita's GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=D-sasmita&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>

<br/>

<img src="https://streak-stats.demolab.com?user=D-sasmita&theme=tokyonight&hide_border=true" alt="GitHub streak stats"/>

</div>

<br/>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=D-sasmita&style=flat-square&color=3B82F6&label=Profile+Views" alt="Profile views"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,50:1e3a8a,100:0f172a&height=100&section=footer" width="100%"/>

</div>
