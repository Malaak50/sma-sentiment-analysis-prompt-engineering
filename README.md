
# Sentiment Analysis with Prompt Engineering

## 📖 Project Overview

This project explores how Prompt Engineering techniques can improve the performance of Large Language Models (LLMs) for sentiment analysis tasks.

The objective is to analyze and classify text sentiments (Positive, Negative, or Neutral) by designing, testing, and optimizing prompts. The project evaluates the impact of different prompting strategies on the quality and consistency of model responses.

## 🎯 Objectives

- Understand the fundamentals of sentiment analysis.
- Experiment with Prompt Engineering techniques.
- Compare different prompt designs and their effectiveness.
- Analyze model outputs and identify strengths and limitations.
- Document the impact of prompt modifications on classification results.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- OpenAI / LLM APIs
- Pandas
- Matplotlib
- Prompt Engineering Techniques

## 📂 Project Structure

```text
sma-sentiment-analysis-prompt-engineering/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── exploratory_analysis.ipynb
│   └── sentiment_analysis.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── prompting.py
│   └── evaluation.py
│
├── results/
│   ├── figures/
│   └── reports/
│
├── requirements.txt
└── README.md
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Malaak50/sma-sentiment-analysis-prompt-engineering.git
cd sma-sentiment-analysis-prompt-engineering
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the environment:

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

Run the sentiment analysis workflow:

```bash
python src/main.py
```

Or explore the notebooks:

```bash
jupyter notebook
```

## 🧠 Prompt Engineering Approaches

The project investigates multiple prompting strategies:

- Zero-shot Prompting
- Few-shot Prompting
- Role Prompting
- Chain-of-Thought Prompting
- Structured Output Prompting

Each approach is evaluated to determine its influence on sentiment classification accuracy and response consistency.

## 📊 Expected Results

- Improved sentiment classification through optimized prompts.
- Comparative analysis of prompting strategies.
- Identification of best practices for prompt design.
- Better understanding of LLM behavior in text classification tasks.

## 🎓 Skills Demonstrated

- Natural Language Processing (NLP)
- Prompt Engineering
- Data Analysis
- Python Programming
- Experimental Evaluation
- Documentation and Reproducibility


