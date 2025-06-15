#  Multi-Modal Matchmaker

A smart dating assistant powered by multi-modal Retrieval-Augmented Generation (RAG). This project uses profile bios (text) and uploaded images to suggest compatible matches by comparing both **text and image embeddings** using **CLIP**, **Sentence-BERT**, and **FAISS**.

---

## Features

- Enter a short **bio** describing yourself
- Upload a **profile image**
- Retrieves and recommends **top matching profiles** using multi-modal similarity search
- Built with Gradio for easy interaction and deployment

---

## 🛠️ Tech Stack

| Component       | Technology                  |
|----------------|-----------------------------|
| UI              | Gradio                      |
| Text Embedding  | Sentence-BERT (`all-MiniLM-L6-v2`) |
| Image Embedding | OpenAI CLIP (`ViT-B/32`)    |
| Search Engine   | FAISS (vector similarity)   |
| Frameworks      | PyTorch, Hugging Face, PIL |

---

##  Running the App Locally

### Install Dependencies

```bash
pip install -r requirements.txt
