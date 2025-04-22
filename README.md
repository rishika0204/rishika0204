Project Portfolio
Welcome to my GitHub project repository! Here, you'll find a collection of my data science, machine learning, and software development projects. Each project includes detailed implementation, relevant algorithms, and performance evaluation metrics.

Projects
1. O1A Insight – AI-Driven Immigration Evaluation
An AI-powered application designed to assess O-1A visa eligibility by evaluating CVs against USCIS evidentiary criteria using ML and NLP techniques.

Features:

Automated CV text extraction (PDF, text files).

NLP-based criteria assessment using spaCy, DistilBERT, and semantic similarity models.

Probabilistic qualification rating (High, Medium, Low) based on the strength of evidence detected.

Technology: Python, spaCy, DistilBERT, Hugging Face Transformers, PyPDF2, Uvicorn, FastAPI.

Results: Improved accuracy in O-1A visa assessment by aligning CV content with legal requirements.

2. Real-Time Adaptive Anomaly Detection System
An adaptive anomaly detection system utilizing Isolation Forest for real-time monitoring in dynamic environments.

Features:

Real-time anomaly detection, adaptive thresholding with EMA, sliding window processing, and performance metrics visualization.

Performance: Achieved 92% accuracy with an 8% false positive rate.

Technology: Python, Isolation Forest, Matplotlib, NumPy, Scikit-learn.

3. Credit Card Fraud Detection
Detects fraudulent transactions using Decision Tree, K-Means Clustering, and K-Nearest Neighbors (KNN) algorithms.

Dataset: 284,807 transactions with 492 fraudulent cases.

Results: 99.93% accuracy with Decision Tree, outperforming K-Means and KNN models.

Technology: Python, Pandas, Scikit-learn, Matplotlib.

4. MusePred Song Recommender Chatbot
A chatbot that suggests songs based on user-provided lyrics, mood, and emotional context.

Features:

Lyric-based, emotion-sensitive song recommendations, genre matching, and a conversational interface.

Technology: Python, NLTK, TensorFlow, PyTorch, IBM Tone Analyzer API, Last.fm API.

5. Multivariate Time-Series Analysis
Implemented machine learning algorithms for regression, classification, and clustering on a weather dataset.

Algorithms: Linear Regression, Random Forests, Naive Bayes, KNN, SVM, Decision Trees, K-Means, EM Clustering.

Results: Achieved 99.93% classification accuracy using Decision Trees.

Technology: Python, Scikit-learn, Matplotlib, Kaggle Weather Dataset.

6. Note-Taking CLI Application
A command-line interface (CLI) application for managing notes.

Features:

Add, remove, list, and read notes via command-line commands.

Technology: Node.js, yargs, fs module.

7. Spotify Song Recommender
A web application that recommends three songs based on a given song title and artist name.

Frontend: HTML, CSS, JavaScript.

Backend: Node.js, Express, Spotify API.

8. Federated Learning for Image Classification
A ResNet152V2-based federated learning model demonstrating collaborative training across multiple clients.

Features:

Data partitioning, federated training, and evaluation.

Technology: Python, TensorFlow, Keras, ResNet152V2.

9. Hotel Management System with IPC
A C-based hotel management system utilizing System V IPC for real-time hotel operations.

Features:

Table management, order handling, and real-time profit calculation using shared memory and semaphores.

Technology: C, System V IPC (Shared Memory, Semaphores, Pipes).

10. Retrieval-Augmented Generation (RAG)
The RAG project implements a Retrieval-Augmented Generation pipeline for enhancing responses by combining document retrieval with OpenAI's language model.

Features:

Document preprocessing (PDF extraction, chunking).

Embedding generation using OpenAI models.

FAISS-based indexing for efficient retrieval.

Query processing using OpenAI's GPT model for context-aware responses.

Technology: Python, OpenAI API, FAISS, PyPDF2, NumPy.

### 11. OCR and Ground Truth Text Alignment

This project provides methods for aligning OCR-generated texts with Ground Truth (GT) texts using deterministic and embedding-based alignment techniques.

**Features:**
- Deterministic alignment using Needleman-Wunsch algorithm based on edit distance (Levenshtein).
- Embedding-based alignment using the MiniLM multilingual model (`paraphrase-multilingual-MiniLM-L12-v2`).
- Embedding-based alignment using the indic-sentence-similarity-sbert model (`l3cube-pune/indic-sentence-similarity-sbert`) fine-tuned for Indic languages.
- FAISS indexing for efficient similarity search in embedding-based methods.
- Evaluation metrics including Levenshtein similarity, Word Error Rate (WER), and Character Error Rate (CER).

**Technology:** Python, Sentence Transformers, FAISS, jiwer, rapidfuzz, regex, PyPDF2



## Getting Started  

Each project includes detailed instructions in its respective directory for setting up the environment, running the code, and understanding the implementation. Dependencies and installation commands are provided for ease of use.  

Feel free to explore, clone, and experiment with the projects! For any questions or contributions, please reach out or submit a pull request.  

