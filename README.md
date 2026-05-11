# Resume & JD Matcher Bot 🤖

An advanced, AI-powered career optimization tool designed to analyze the compatibility between a candidate's resume and a target job description. Leveraging **Google Gemini Pro**, this application provides deep semantic matching, automated gap analysis, and tailored, actionable feedback to align profiles with modern Applicant Tracking Systems (ATS) and hiring requirements.

---

## 🔍 Key Features

*   **Multi-Format Parsing:** Seamlessly processes resumes in both PDF and plain text formats.
*   **Semantic Alignment Analysis:** Evaluates core competencies, underlying skills, and domain-specific vocabulary rather than relying on simple keyword counts.
*   **ATS Optimization & Keyword Match:** Identifies critical missing keywords and phrases essential for passing automated screening systems.
*   **Quantitative Compatibility Scoring:** Generates an objective alignment score from $0 \text{ to } 10$ to help candidates benchmark their readiness.
*   **Constructive Feedback Loop:** Delivers targeted, actionable suggestions to dynamically improve resume impact and role fit.

---

## 🚀 Tech Stack

*   **Core Engine:** Python 3
*   **LLM Integration:** Google Generative AI (`google-generativeai` / Gemini Pro)
*   **Document Intelligence:** `PyMuPDF` (Fitz) for high-fidelity PDF text extraction
*   **Environment Management:** `python-dotenv` for secure API key configuration

---

## ✨ Project Genesis & Engineering Objectives

This repository was engineered as a core component of my professional portfolio to demonstrate the practical application of Large Language Models (LLMs) in solving real-world data-matching challenges. 

Beyond its architectural value as an AI pipeline—showcasing prompt engineering, document parsing, and structured LLM outputs—this tool was designed to solve a practical problem: optimizing my own technical resume against demanding roles in Software Engineering and Artificial Intelligence.

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone [https://github.com/yourusername/resume-jd-matcher-gemini.git](https://github.com/yourusername/resume-jd-matcher-gemini.git)
cd resume-jd-matcher-gemini