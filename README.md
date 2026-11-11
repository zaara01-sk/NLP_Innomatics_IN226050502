# Applied Natural Language Processing (NLP) Engine & Transformers

A comprehensive suite of production-grade and experimental NLP workflows covering classic lexical processing to modern Transformer and BERT architectures. Developed as part of applied AI engineering coursework at Innomatics Research Labs.

---

## Repository Modules & Implementations

### 1. TASK_4_BERT_IN226050502.ipynb — BERT Fine-Tuning & Representation
* Implements bidirectional contextual embeddings using Hugging Face's BERT (ert-base-uncased).
* Tokenization pipelines with WordPiece, attention masks, and classification heads.
* Evaluated against standard benchmarks using Precision, Recall, and F1 metrics.

### 2. TASK_3_Chatbot_Transformers_IN226050502.ipynb — Generative & Conversational Transformers
* Explores sequence-to-sequence architectures and generative attention-based response generation.
* Context caching and prompt conditioning for multi-turn dialogue stability.

### 3. TASK_2_Sentiment_Analysis.ipynb — Deep Sentiment Analysis Pipeline
* End-to-end sentiment classification on unstructured textual corpora.
* Comparative benchmark between classical feature extraction (TF-IDF / N-grams) and dense neural embeddings.

### 4. TASK_5_POS_Chunking_IN226050502.ipynb — Syntax Extraction & Chunking
* Part-of-speech (POS) tagging and shallow parsing (Chunking) using rule-based grammar and probabilistic taggers.
* Information extraction pipelines for entity boundary detection.

### 5. 
lp_preprocessing_engine.ipynb — Core Preprocessing & Text Normalization
* High-throughput regex cleaning, Unicode normalization, stop-word removal, and Lemmatization pipelines.

---

## Tech Stack
* **Frameworks:** PyTorch, Hugging Face Transformers, NLTK, spaCy, Scikit-Learn
* **Models:** BERT, DistilBERT, Seq2Seq Models
* **Data Processing:** Pandas, NumPy, Regular Expressions
