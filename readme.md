# Experiments for the intent benchmark datasets

This repository contains the code to analyze intent benchmark datasets in terms of their lexical
structure, projections using UMAP to view the produced embeddings in the semantic space,
as well as implementations for DBI to utilize the cosine distance.

## Quick Start

```
# Create a new virtual environment
python -m venv new_env
source new_env/bin/activate  # On Windows: new_env\Scripts\activate

# Upgrade pip
pip install --upgrade pip

# Installing
pip install -r requirements.txt
```

Subsequently the spaCy language model, stop-words, as well as the specific sentence-transformer will be downloaded for their utilization in later sections.
