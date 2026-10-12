Zahra Mohammadinezhad

MSc student in Language Technologies and Digital Humanities at the University of Turin. My background is in linguistics, but I work mostly on the computational side — NLP pipelines, data preprocessing, model evaluation, data analysis.



What I work with

Languages & libraries: Python, SQL, TensorFlow, Keras, scikit-learn, pandas, numpy
Tools: Git, Excel, Google Colab, Jupyter
Areas: NLP, data analysis, annotation workflows, corpus building, AI model evaluation

Projects

Pen Meets AI — Handwritten character classification on EMNIST Balanced. Trained and compared three architectures (Simple CNN, Optimized CNN, EfficientNetB0) on 12 visually similar character classes. Optimized CNN reached 84% accuracy.

GeMoSC (thesis) — Built a structured dataset of movie scripts with character-level annotations and metadata, using Python to automate   collection, cleaning, and formatting. Used as a benchmark corpus for NLP and LLM research.Currently building a model to recognize speech based on generation and gender. 

Ask GeMoSC: Bilingual RAG Assistant 2026
 Python, sentence-transformers, ChromaDB, Gemini API, Gradio
 Built a retrieval-augmented chatbot that answers English and Italian questions over 110,889 scene excerpts from 674 films, with scene-level citations, metadata filters (generation, gender, year) and refusal when the corpus has no evidence.
 Designed a 33-question evaluation set (LLM-drafted and manually reviewed, including Italian and unanswerable questions) and measured Hit@k, MRR, faithfulness with an LLM judge, and refusal accuracy.
 Traced low recall to the vector database's approximate (HNSW) search; switching to exact search with multilingual cross-encoder reranking raised Hit@5 from 0.30 to 0.40 and MRR from 0.17 to 0.33, with 100% refusal accuracy.
 Added retries with model fallback for API rate limits and verified the LLM judge's decisions by hand.


Background
AI Quality Analyst at Nebuly (Turin) — annotation workflows, model output evaluation, structured reporting
Research Assistant at University of Staffordshire — clinical dataset preprocessing and feature engineering for explainable AI research
Connect

LinkedIn: https://www.linkedin.com/in/zahra-mohammadinezhad-a42395237
Turin, Italy · zahra.mohammadinezha@edu.unito.it
zahramohamadinezhad27@gmail.com
