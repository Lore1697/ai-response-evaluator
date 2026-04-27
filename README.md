# AI Response Quality & Risk Evaluator
![Python](https://img.shields.io/badge/Python-3.13-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

An interactive tool for evaluating AI-generated responses with multi-domain risk scoring, explainability, and multilingual support.

## Demo

### Example evaluation

![App Screenshot](screenshot.png)

## What it does

This tool evaluates AI responses and detects potential risks such as:

- Overconfidence
- Unsafe medical advice
- Missing follow-up questions
- Budget inconsistencies
- Unsupported certainty in public information
- Language mismatch (Italian/English)

It assigns a risk score and provides explanations and improvement suggestions.

---

## Features

- Multi-domain evaluation (health, hardware, public information, fitness)
- Rule-based risk scoring system
- Explainable AI output (issues + reasoning)
- Multilingual support (Italian / English)
- Interactive web interface (Streamlit)
- Exportable evaluation reports (CSV)

---

## Technologies

- Python
- pandas
- Streamlit
- Rule-based NLP techniques

---

## Example Output

| Domain | Risk Score | Risk Level | Issues |
|--------|-----------|-----------|--------|
| Health | 75 | HIGH | Medical risk, Overconfidence |
| Hardware | 45 | MEDIUM | Budget mismatch |
| Public Info | 35 | MEDIUM | Unsupported certainty |

---

## Why This Project

This project demonstrates practical skills in:

- AI response evaluation
- Risk detection in language models
- NLP-based rule systems
- Building interactive tools for analysis

---

## How to Run

```bash
pip install streamlit pandas
python -m streamlit run app.py
```

## Project Structure

ai-response-evaluator/
│
├── app.py # Streamlit interface (UI)
├── evaluator.py # Core evaluation logic (rules, scoring, detection)
├── README.md
├── screenshot.png # App demo image
└── data/
└── examples.csv # Sample inputs for testing

## Future Improvements

- Add ML-based evaluation models
- Expand multilingual support
- Improve scoring system
- Add batch evaluation
