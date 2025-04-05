# Bias Analysis in LLM-Based Multi-Agent Systems

This project investigates patterns of bias and behavioral divergence in large language model (LLM)-based multi-agent environments. The work is part of a research initiative exploring fairness, explainability, and coordination in agent-based AI systems.

## 🔍 Overview

- **Goal**: Identify and visualize systematic biases in agent responses across varying scenarios.
- **Tech Stack**: Python, R, Jupyter Notebooks, Streamlit
- **Tools**: Matplotlib, Seaborn, Plotly, pandas, NumPy

## 📁 Project Structure

```
llm-bias-multiagent-analysis/ │ ├── data/ # Sample input data and synthetic test cases ├── notebooks/ # Exploratory Jupyter notebooks │ ├── 01_data_cleaning.ipynb │ ├── 02_bias_metrics.ipynb │ └── 03_visualizations.ipynb ├── scripts/ # Python scripts for data prep and analysis │ └── process_agents.py ├── app/ # Streamlit dashboard app │ └── streamlit_dashboard.py ├── figures/ # Saved visual outputs ├── requirements.txt └── README.md

```

## 📊 Key Features

- 📦 **Data Preparation**: Cleaned and structured agent interaction logs across multiple experiments.
- 📈 **Visualization**: Created comparative plots showing divergence in agent behavior using:
  - `Matplotlib`
  - `Seaborn`
  - `Plotly`
- 🧠 **Bias Metrics**: Statistical modeling using Python and R to evaluate:
  - Response divergence
  - Topic sensitivity
  - Socio-linguistic bias
- 🧪 **Dashboard**: Interactive dashboard using Streamlit to explore trends and key visualizations.

## 🚀 Getting Started

### Installation

Clone the repo:

```bash
cd llm-bias-multiagent-analysis
pip install -r requirements.txt
