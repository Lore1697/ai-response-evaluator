# AI Response Quality & Risk Evaluator

An interactive Python-based tool for evaluating AI-generated responses across multiple domains.

## Overview

This project simulates real-world AI evaluation workflows used in training and improving language models.

It analyzes responses and detects potential issues such as:

- Overconfidence
- Missing follow-up questions
- Medical risk and unsafe advice
- Unsupported certainty in public information
- Budget mismatches in hardware recommendations
- Fitness safety and equipment issues
- Language mismatch (Italian/English)

The system assigns a risk score, identifies issues, and generates explainable outputs with improvement suggestions.

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

## Demo

### Example evaluation

![App Screenshot](screenshot.png)
