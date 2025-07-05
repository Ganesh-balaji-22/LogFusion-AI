# LogFusion AI: Hybrid Log Classification Framework

🚀 **LogFusion AI** implements a **hybrid log classification system** that combines Regex, Machine Learning, and LLM approaches to handle varying complexities in log patterns within enterprise data pipelines.

---

## 🛠️ Classification Approaches

1️⃣ **Regular Expressions (Regex)**  
- Handles predictable and structured log patterns using rule-based logic.  
- Fast and effective for consistent error patterns.

2️⃣ **Sentence Transformer + Logistic Regression**  
- Classifies complex patterns when sufficient labeled data is available.  
- Uses embeddings from Sentence Transformers with Logistic Regression for classification.

3️⃣ **LLM (Large Language Models)**  
- Classifies complex patterns when labeled data is limited or absent.  
- Acts as a fallback to enhance coverage with zero/few-shot capabilities.

---

## 🗂️ Project Structure

```
LogFusion-AI/
├── training/               # Scripts for regex and ML model training
├── models/                 # Saved embeddings and trained ML models
├── resources/              # Test CSVs, output samples, architecture diagrams
├── server.py               # FastAPI server for classification
├── requirements.txt        # Python dependencies
└── README.md
```

---

## 🖼️ Architecture

![Hybrid Classification Architecture](resources/arch.png)

---

## 🤝 Contributing

Contributions are welcome! Please open issues or PRs to enhance LogFusion AI further.

---

## 📫 Contact

**Ganesh Balaji**  
[LinkedIn](https://www.linkedin.com/in/ganeshbalaji22/) 

