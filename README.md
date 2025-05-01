# News Research Tool 📈

It is an intelligent chatbot built using Streamlit and LangChain that helps you extract key insights and answers from online news articles. Simply paste in URLs of news articles, and ask your question — It will provide answers along with their sources!

## 🔍 What it does

It uses the power of:

- 🧠 **LangChain** + **Google Gemini Pro** for high-quality question answering
- 📄 **UnstructuredURLLoader** to extract content from webpages
- 🧱 **FAISS** and **HuggingFace Embeddings** to store and retrieve relevant chunks of text
- 🗂️ Chunking and embedding techniques for context-aware Q&A
- 💬 Clean Streamlit UI for ease of use

---

## 🚀 Features

- Input up to **3 URLs** of news articles
- Automatically loads, parses, and splits the content
- Embeds and stores the document chunks using **FAISS**
- Ask questions related to the articles
- Get accurate answers with **cited sources**

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| `Streamlit` | Frontend UI |
| `LangChain` | Orchestration and QA chains |
| `Google Gemini API` | LLM for answering queries |
| `FAISS` | Vector store for document retrieval |
| `HuggingFace Embeddings` | For semantic similarity search |
| `SentenceTransformers` | Pretrained embedding models |
| `Unstructured` | For scraping and parsing HTML article content |

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/news-research-tool-chatbot.git
cd news-research-tool-chatbot
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Create a `.streamlit/secrets.toml` file and add your Google API key:

```toml
GOOGLE_API_KEY = "your-gemini-api-key"
```

4. Run the app:

```bash
streamlit run streamlit_app.py
```

---

## 📁 Project Structure

```
news-research-tool-chatbot/
│
├── streamlit_app.py         # Main app file
├── requirements.txt         # Python dependencies
└── README.md                # This file
```

---

## 📸 Screenshot

![image](https://github.com/user-attachments/assets/2297fc74-1ea5-434f-8fc4-ea47ffa87f6c)


---

## 🙋‍♂️ How to Use

1. Enter up to **3 news article URLs** in the sidebar.
2. Click **"Process URLs"** to load and index them.
3. Ask a question based on the article content.
4. RockyBot will provide a concise answer, along with cited sources. 📚

---

## 📌 Example Use Cases

- Researching multiple news articles on a trending topic
- Extracting quotes or insights from long-form content
- Fact-checking or summarizing news quickly
- Journalists and analysts who need fast insights

---

## 🤝 Contributions

Feel free to fork this repo, suggest improvements, or open pull requests!

---

---

## 💡 Future Improvements

- Support for uploading PDFs or DOCX files
- Summarization of articles
- Multi-language support
- Better error handling for invalid URLs
