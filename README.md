# Austria IMF Report Analysis

This project analyses Austria’s 2025 Article IV Consultation report using
a Python notebook in Google Colab. It extracts economic information,
generates summaries and creates a four-panel dashboard.

## What the Notebook Does

- Extracts and cleans PDF text while retaining page references.
- Creates overlapping text chunks and section summaries.
- Counts seven financial stability themes.
- Extracts strengths, vulnerabilities and numerical indicators.
- Prepares historical and projected economic series.
- Uses local sentence-transformer embeddings and FAISS for retrieval.
- Evaluates answers and compares single-query with multi-query retrieval.
- Saves results as JSON, CSV and dashboard files.

## How to Run

1. Open the notebook in Google Colab.
2. Download the full IMF report using the link below and rename it
   austria.pdf.
3. Place austria.pdf in the Colab Files panel.
4. Add your Gemini API key to Colab Secrets as flash_key and enable
   notebook access.
5. Run the notebook cells in order.

The notebook installs its required packages. Internet access and a Gemini
API key with access to the configured model are required. API usage may
incur charges depending on your account.

## Source Report

*Austria: 2025 Article IV Consultation—Press Release; and Staff Report*

International Monetary Fund, Country Report No. 25/159.
