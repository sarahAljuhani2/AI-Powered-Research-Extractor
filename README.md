#  AI-Powered Research Paper Extractor

This project is a lightweight web application that allows users to **upload a research paper (PDF)** and automatically extract key information using **OpenAI GPT-4**.

<p align="center">
  <img src="https://img.shields.io/badge/FastAPI-✔️-005f73?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OpenAI-GPT--4-005f73?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge" />
</p>

---

## 💡 Features

- 📄 Upload any research paper (PDF)
- 🔍 Automatically extract:
  - Title
  - Abstract
  - Authors
  - Author Emails
  - Summary of Conclusion
- 🖥 Clean and interactive web interface
-  Powered by GPT-4 via OpenAI API

---

##  How It Works

1. User uploads a PDF through the interface.
2. Text is extracted using `PyPDF2`.
3. GPT-4 processes the text and returns the requested fields.
4. Results are shown in a neat HTML table.

---

## 🔧 Technologies Used

- **FastAPI** for building the backend API.
- **PyPDF2** for reading PDF content.
- **OpenAI GPT-4** for information extraction.
- **Bootstrap** for styling the UI.
- **Python 3.9+**

---

##  Model Usage

This project uses **GPT-4** via the OpenAI API to extract structured insights from unstructured academic content.

You must set your OpenAI key in an `.env` file like this:

```bash
OPENAI_API_KEY=sk-xxxxxxx
