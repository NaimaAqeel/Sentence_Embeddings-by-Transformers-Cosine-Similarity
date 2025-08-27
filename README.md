# Sentence Embeddings with Transformers

This project demonstrates how to compute **sentence embeddings** and measure **semantic similarity** between sentences using the [Sentence Transformers](https://www.sbert.net/) library.

---

## Project Overview

- The original notebook `Sentence_Embeddings_by_Transformers_Cosine_Similarity.ipynb` contains the full implementation but may not render properly on GitHub. Users can download it to view and run locally.
- The cleaned notebook `Sentence_Embeddings_by_Transformers_Cosine_Similarity_clean.ipynb` has been cleaned of outputs and execution counts. It contains the full code for:
  - Installing required libraries
  - Building a sentence embedding pipeline using the `all-MiniLM-L6-v2` model
  - Encoding sentences into embeddings
  - Calculating **cosine similarity** between sentences

This setup allows anyone to run the notebook smoothly and see the results.

---

## What I Learned

During this project, I learned how to:

- Work with **pre-trained transformer models** for sentence embeddings.
- Encode sentences into **dense vector representations** using the `SentenceTransformers` library.
- Measure **semantic similarity** between sentences using **cosine similarity**.
- Clean and manage Jupyter notebooks programmatically.
- Work efficiently in **Google Colab** and download notebooks to a local machine.

---

## Libraries Used

- `sentence-transformers` – to create sentence embeddings and compute similarity.  
- `transformers` – to handle transformer model utilities and suppress warnings.  
- `nbformat` – to read, clean, and save Jupyter notebooks.  
- `requests` – to download notebooks from GitHub.  
- `google.colab` – to download files from Colab to local PC.

---

## References

- [Sentence Transformers Documentation](https://www.sbert.net/)  
- [Hugging Face Model: all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)

---

