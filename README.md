# 🛡️ Multilingual Misogyny Detection in Swedish (Low-Resource NLP)

This project explores how multilingual and monolingual Transformer models perform on **Swedish misogyny detection**, a task made challenging by limited annotated data. It compares **zero-shot**, **cross-lingual fine-tuning**, and **few-shot inoculation** strategies using models like **mBERT**, **XLM-R**, and **KB-BERT**.

> 📘 Part of my MSc work in Computational Linguistics @ UCL.

---

## 🎯 Objectives

- Evaluate the effectiveness of **multilingual vs. monolingual** Transformer models on low-resource hate speech detection  
- Compare **transfer learning techniques**:
  - **Zero-Shot Inference**
  - **Cross-Lingual Fine-Tuning** (using EN, DE, DA)
  - **Few-Shot (Inoculation)** with minimal Swedish data  
- Provide practical insights for building NLP systems in **data-scarce language contexts**

---

## 🧠 Key Technologies

| Category     | Tools/Models Used                                                   |
|--------------|---------------------------------------------------------------------|
| Frameworks   | Python, PyTorch, TensorFlow, Hugging Face Transformers & Datasets   |
| Models       | `mBERT`, `XLM-R`, `KB-BERT`, other Swedish variants                 |
| Environment  | Google Colab (GPU)                                                  |

---

## 📂 Project Structure

```
.
├── data/               # Contains raw data files of various formats 
├── tokenized data/     # Stores tokenized data used by transformer models
├── processed data/     # Stores pre-processed data ready for tokenization
├── models/             # Stores models saved at best F1 performance during training
├── results/            # Stores evaluation results
├── LICENSE             # MIT License file
└── README.md           # This file
```


---

## 🧪 Current Status

This is an **active research project**, and the repository currently functions as both a codebase and documentation hub.  
Training and evaluation are done primarily in **Google Colab** for GPU access:

▶️ **[Open Colab Notebook](https://colab.research.google.com/drive/1MatYWBgW2FLe-u_thPLUvdP9uqgOKxWi?usp=sharing)**

---

## 🔍 Planned Improvements

- Complete full comparative analysis across all planned models  
- Add deeper evaluation (e.g., **error analysis**, confusion matrices, demographic biases)  
- Refactor code into **modular scripts** post-experiment phase  
- Finalise MSc report/paper write-up  

---

## 💬 Why This Matters

Building robust hate speech detection systems in **low-resource languages** is essential for global digital safety and fairness. This project aims to identify scalable, ethical solutions using **cross-lingual transfer** and **transformer-based models** to support responsible AI.

---

### 👩‍💻 Author
**Tatiana Limonova**  
MSc Language Sciences (Technology of Language and Speech) – UCL  
[GitHub Profile](https://github.com/kanincityy) • [LinkedIn](https://linkedin.com/in/tatianalimonova)  
