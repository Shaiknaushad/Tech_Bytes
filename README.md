
# LLM Query Retrieval App

🔍 **LLM-Powered Intelligent Query–Retrieval System**

## Overview

This Streamlit app enables users to upload legal documents (PDF or DOCX), ask natural language questions, and receive:

- **Relevant Clauses:** AI-powered search for the most pertinent sections.
- **Simplified Explanations:** Easy-to-understand summaries of matched clauses.
- **Automated Decision:** Final approval/denial with estimated amount and justification.
- **Highlighted PDF:** Downloadable document with matched clauses visually marked.
- **Output JSON:** Downloadable structured results for further use.

---

## Features

- **Document Upload:** Supports PDF and DOCX (1–5 pages recommended).
- **Natural Language Query:** Ask questions in plain English.
- **Clause Search:** Finds and ranks relevant clauses using vector search.
- **LLM Explanations:** Explains legal text in simple terms.
- **Decision Engine:** Infers approval/denial and estimates amounts.
- **PDF Highlighting:** Marks matched clauses in the original document.
- **Downloadable Results:** Output JSON and highlighted PDF.

---

## Getting Started

### Prerequisites

- Python 3.8+
- [Streamlit](https://streamlit.io/)
- Other dependencies (see `requirements.txt`)

### Installation

```bash
pip install -r requirements.txt
```

### Run the App

```bash
streamlit run app.py
```

---

## Usage

1. **Upload Document:** Click "Upload Document" and select a PDF or DOCX.
2. **Enter Query:** Type your question (e.g., "Is accident on day 1 eligible for claim?").
3. **Run Query:** Click "Run Query" to process.
4. **View Results:** See matched clauses, explanations, decision, and download options.

---

## Example Queries

- *Will my knee surgery be covered after 3 months?*
- *Is accident on day 1 eligible for claim?*

---

## File Structure

```
llm_query_app/
├── app.py
├── requirements.txt
├── utils/
│   ├── document_loader.py
│   ├── vector_search.py
│   ├── llm_explainer.py
│   ├── decision_engine.py
│   └── pdf_highlighter.py
└── .gitignore
```

---

## Credits