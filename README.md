# GovCon Shred & Capture App

This is a Streamlit-based application that analyzes and shreds federal government contracting (GovCon) solicitations from various stages: Sources Sought, RFI, Presolicitation, Pre-RFP, and RFP.

## Features

- SAM.gov API integration
- File and text-based solicitation parsing
- LLM-based section analysis (Sections C, L, M)
- Opportunity scoring & PWIN calculator
- SWOT analysis and Shipley color review workflow
- Export to Word and CSV formats

## SAM.gov API
To enable API integration, set your SAM API key as an environment variable or Streamlit secret.

## Setup

```bash
pip install -r requirements.txt
streamlit run app.py
```

