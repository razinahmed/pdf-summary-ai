# PDF Summary AI

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![AI](https://img.shields.io/badge/AI-Powered-purple)
![License](https://img.shields.io/badge/License-MIT-green)

An AI-powered PDF summarization tool that extracts key information from PDF documents and generates concise, structured summaries. Uses large language models to understand document context and produce actionable insights.

---

## Features

- **Document Summarization** -- Generates concise summaries from lengthy PDF files
- **Key Point Extraction** -- Identifies and highlights the most important information
- **Multi-Page Support** -- Handles documents of any length with chunked processing
- **Section-Aware** -- Respects document structure for more accurate summarization
- **Custom Length** -- Control summary length from brief abstracts to detailed overviews
- **Batch Processing** -- Summarize entire directories of PDFs in one operation

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python 3.9+ | Core runtime |
| OpenAI / LLM API | Text summarization |
| PyPDF / pdfplumber | PDF text extraction |
| Makefile | Build and test automation |

---

## Quick Start

```bash
# Clone the repository
git clone https://github.com/razinahmed/pdf-summary-ai.git
cd pdf-summary-ai

# Install dependencies
pip install -r requirements.txt

# Summarize a PDF
python core/ai_worker.py --input document.pdf --length short
```

---

## Project Structure

```
pdf-summary-ai/
├── core/
│   └── ai_worker.py       # Main AI processing engine
├── Makefile                # Build and test commands
├── LICENSE                 # MIT License
├── SECURITY.md             # Security policy
└── README.md
```

---

## Usage

```bash
# Build the project
make build

# Run tests
make test
```

---

## Contributing

1. Fork the repository
2. Create a feature branch -- `git checkout -b feature/your-feature`
3. Commit your changes -- `git commit -m "feat: add new feature"`
4. Push and open a Pull Request

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Built by [Razin Ahmed](https://github.com/razinahmed)**
