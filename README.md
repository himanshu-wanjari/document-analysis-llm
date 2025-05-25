# Document Analysis using LLMs (Large Language Models)

This project leverages transformer-based large language models to extract summaries, generate answers, and identify insights from unstructured PDF documents. Built as a context-aware document assistant using Python and LLM libraries.

## 🧠 Features

- Extracts text from scanned or digital PDFs
- Summarizes long documents intelligently
- Performs context-aware Question Answering
- Works with financial reports, contracts, legal docs, etc.

## 🛠️ Technologies

- Python
- pdfplumber for PDF text extraction
- HuggingFace Transformers (T5 model)
- NLTK for preprocessing and sentence parsing
- Streamlit (optional UI)


## 🚀 Usage

1. Upload a PDF
2. The model extracts and preprocesses the text
3. Generates a summary
4. Accepts user questions about the document and provides contextual answers

## 📈 Results

- Summarized ~5-page financial reports into 4-5 bullet points
- Answered >85% user questions correctly based on extracted context

## 🔮 Future Work

- Add multilingual support using MarianMT or mT5
- Deploy as SaaS or API-based service
- Improve OCR for scanned PDFs
