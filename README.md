
# UNHCR SRF Portfolio Copilot (IATI + LLM + ABM)

This project provides an exploration of the impact of Different Resource Allocation Scenarios per Outcome Area with Causal Inference, Agent-Based Modeling & Data Envelopment Analysis


## Installation

```bash
uv venv --python 3.12
source .venv/bin/activate
uv pip install -r requirements.txt
```

(You also need **Quarto** installed and on your PATH.)

## Configure secrets

Copy the template and add your Azure keys:

```bash
cp .env.example .env
# edit .env and set AZURE_OPENAI_* variables
```

The Quarto loads environment variables from `.env` via **python‑dotenv**.

## Run 

```bash
quarto render index.qmd  
```

