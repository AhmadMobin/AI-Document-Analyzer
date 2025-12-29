# AI Document Analyzer

Turn a folder of documents into a concise briefing pack using Python and AI.

## Overview
This project reads local text files (`.txt`) and text-based PDFs (`.pdf`), generates high-level summaries for each document using a large language model, and synthesizes those summaries into a single structured briefing pack saved as a Markdown file.

The project was built to practice core Python programming concepts alongside practical AI-assisted text analysis.

## Features
- Reads local `.txt` files
- Extracts text from text-based `.pdf` files
- Summarizes each document using an LLM
- Synthesizes multiple summaries into a single briefing pack
- Saves the final output as a Markdown file

## Project Structure
```text
.
├── notebook.ipynb        # Main Jupyter notebook
├── docs/                 # Input documents (.txt, .pdf)
├── outputs/              # Generated briefing packs (not committed)
├── README.md
├── .gitignore
└── .env                  # API key (not committed)

## Requirements

* Python 3.9+

* Jupyter Notebook

* OpenAI API key

## Python packages

* openai

* python-dotenv

* pypdf
