# Hi, I'm Christian 👋

I build AI applications and applied machine learning projects, with a focus on useful tools and questions that affect people's lives. I have a **B.S. in Data Science** from Arizona State University and bring a hands-on background in IT troubleshooting.

**Open to opportunities in applied ML, AI application development, and Python engineering.**

[Portfolio](https://www.christianolivares.us/) · [LinkedIn](https://www.linkedin.com/in/christian-olivares-rodriguez/) · [Email](mailto:christianolivares@protonmail.com)

## Featured projects

### Lumitudy — AI study platform

A deployed web application that turns uploaded PDF, DOCX, and EPUB chapters into flashcards and exams, with live multiplayer quizzes.

- **Application engineering:** document access controls, JWT authentication, WebSocket quiz rooms, and server-side exam grading.
- **AI integration:** Claude generates study material; the server validates responses and copies source passages directly from the document for flashcard quotes.
- **Verification:** automated backend and frontend regression tests, with GitHub Actions checks.

**FastAPI · React · SQLite · WebSockets · Claude API**

[Try Lumitudy](https://lumitudy.vercel.app/) · [Code and setup](https://github.com/Oli-Data/lumitudy)

### Ookla — California mobile broadband equity

Analyzed Ookla mobile speed-test data from 2020–2025 across the Central Valley, Bay Area, and Southern California. Joined geographic data with Census demographics to examine differences in broadband performance.

In the Central Valley sample for 2022–2024, median mobile download speeds were 119 Mbps in rural areas and 186 Mbps in urban areas. This is an observed difference, not a causal estimate.

**Python · GeoPandas · Census ACS · AWS S3 · Matplotlib**

[Analysis, charts, and methodology](https://github.com/Oli-Data/Ookla-Data)

### Chicago — Recorded-arrest classification

Explored a sample of **192,082 crime records** and built a four-layer PyTorch network to classify whether an arrest was recorded.

- **86% accuracy** on 38,417 held-out test records, compared with an approximately **75% majority-class baseline**.
- Arrest-class **precision: 0.78**, **recall: 0.59**, and **F1: 0.67**.
- Used weighted sampling to address class imbalance; the minority-class results show where the model still misses cases.

**PyTorch · pandas · scikit-learn · Folium**

[Notebook, evaluation, and limitations](https://github.com/Oli-Data/Data-Science-Machine-Learning-Projects/tree/main/Chicago%20Crime%20Project)

## More work

- [Fraud detection on GCP](https://github.com/Oli-Data/Data-Engineering-Infrastructure-Projects/tree/main/Google%20Cloud%20Project) — an ASU coursework project using PySpark MLlib and Dataproc to compare classifiers on 999,001 transaction records.
- [Bank marketing classification](https://github.com/Oli-Data/Data-Science-Machine-Learning-Projects/tree/main/Bank%20Marketing%20ML) — experiments comparing models for term-deposit subscription prediction.

## Tools I use

- **Languages:** Python, SQL, JavaScript, TypeScript
- **ML and data:** PyTorch, scikit-learn, PySpark, pandas, NumPy, GeoPandas
- **Applications:** FastAPI, React, Next.js, WebSockets
- **Infrastructure:** Linux, CUDA, AWS S3, Google Cloud Dataproc, Vercel, GitHub Actions
- **Visualization:** Matplotlib, Plotly, Folium, Seaborn, Tableau

## What I'm exploring

Through **CO³ Labs**, my independent research and engineering venture, I'm developing local-LLM agent experiments focused on context management and task execution. This work is in development. I'm interested in making AI systems easier to inspect, evaluate, and use.
