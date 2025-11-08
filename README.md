# 📘 RAG (Retrieval-Augmented Generation) Mini Project👇

---

## 🧠 **Project Summary**

This project presents a practical implementation of a **Retrieval-Augmented Generation (RAG)** system, illustrating how artificial intelligence can combine **information retrieval** with **contextual language generation** to produce accurate and relevant answers.

Using a small custom knowledge base, the notebook demonstrates the core logic of a RAG pipeline — from embedding sentences for semantic similarity, retrieving the most relevant context, and generating human-like answers through a question–answering model.

Through a series of structured tasks, the project progressively enhances the RAG workflow by:

* Evaluating the system on fundamental question–answer pairs.
* Adding new questions and validating model adaptability.
* Expanding the knowledge base with new information to test retrieval and generation robustness.

This project emphasizes **clarity, experimentation, and applied understanding**, making it an excellent educational example for students and practitioners who want to explore how retrieval and generation models interact in real-world AI applications.

---

### 🧩 Overview
This notebook demonstrates a simple **Retrieval-Augmented Generation (RAG)** system.  
It combines two main AI components:

1. **Retriever** – finds the most relevant sentence from a small knowledge base.  
2. **Generator (Question Answering model)** – uses the retrieved context to generate an answer.

The goal of the notebook is to practice how RAG systems retrieve and generate accurate answers using a minimal dataset.

---

### ⚙️ What’s Inside
The notebook includes:
- Loading the models (`SentenceTransformer` for retrieval, and a QA model for answer generation).
- A small **knowledge base** with 5–6 factual sentences.
- Three main **tasks**:
  - **Task 1:** Test basic question–answer pairs.
  - **Task 2:** Add a new question and rerun the evaluation.
  - **Task 3:** Expand the knowledge base (adding “The Nile” fact) and test the new question.

---

### 🚀 How to Run
1. Install the required libraries:
   ```bash
   pip install sentence-transformers transformers torch
   ```
2. Open the notebook in Jupyter or Google Colab.
3. Run the setup cells (imports, models, embeddings).
4. Execute any of the task functions:
   ```python
   run_rag_assessment()          # Task 1
   run_rag_assessment_task_2()   # Task 2
   run_rag_assessment_task_3()   # Task 3
   ```

Each task prints the question, the retrieved context, the model’s generated answer, and a simple score.

---

### 📊 Example Output
```
--- 🚀 Starting RAG System Assessment (Task 1) ---

--- Question 1: 'What is the highest mountain?'
✅ Retrieval Successful!
✍️  Generated Answer: 'Mount Everest'
✅ Generation Successful!

🏁 Final Score: 6/6
```

---

### 🧠 Key Learning Points
- Understand how **semantic search** retrieves relevant context using embeddings.
- Practice how **QA models** generate answers based on context.
- Learn the logic behind testing RAG systems with structured tasks.

---


### 🏁 Summary
This notebook is a **hands-on mini project** for understanding the RAG pipeline.  
It walks through retrieval, generation, and evaluation steps in a clear and simple structure — perfect for learning how knowledge-augmented AI systems work.
