# 🧾 Multi-Document Summarization Models

This repository showcases advanced techniques for summarizing information from multiple documents. These approaches are essential when dealing with collections of related texts like news articles, research papers, or meeting transcripts.

We include attention-based transformers, graph neural networks, and hierarchical summarization theory.

---

## 🚀 Notebooks & Techniques

| Notebook | Method | Technique |
|----------|--------|-----------|
| `01_longformer_multidoc_attention.ipynb` | Longformer Encoder-Decoder | Handles long sequences for multi-doc input |
| `02_gat_sentencebert.ipynb` | GAT + Sentence-BERT | Graph-based summarization using attention |
| `03_hatsum_theory.ipynb` | HATSum (Theory) | Hierarchical Attention Transformer (conceptual understanding) |

---

## 📂 Folder Structure

```

multi-document-summarization-models/
├── Notebooks/
│   ├── 01\_longformer\_multidoc\_attention.ipynb
│   ├── 02\_gat\_sentencebert.ipynb
│   └── 03\_hatsum\_theory.ipynb
├── LICENSE
├── README.md
└── requirements.txt

````

---

## 💻 Run Locally

```bash
git clone https://github.com/Koushim/multi-document-summarization-models.git
cd multi-document-summarization-models
pip install -r requirements.txt
````

---

## 🙌 Acknowledgements

* [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/)
* [SentenceTransformers](https://www.sbert.net/)
* [GAT Paper](https://arxiv.org/abs/1710.10903)

---

## 📈 Highlights

* ✅ Handles very long or multiple document inputs
* ✅ Graph Attention Networks (GAT) for sentence-level relationships
* ✅ Pretrained transformer models for semantic embeddings
* ✅ Includes theoretical foundation of HATSum

---

## ✍️ Author

**Koushik Reddy**
🔗 [Hugging Face](https://huggingface.co/Koushim) | [LinkedIn](https://www.linkedin.com/in/koushik-reddy-k-790938257)

---

## 📌 License

This project is open source and available under the [Apache License](LICENSE).

