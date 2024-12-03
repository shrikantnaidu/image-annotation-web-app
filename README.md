# Image Annotation App

A Streamlit web application that uses OpenAI's CLIP (Contrastive Language-Image Pre-Training) model to understand and analyze images through a fun "2 Lies and 1 Truth" game format.

## Overview

This application allows users to:
- Upload images
- Provide three descriptions (two false and one true)
- Let the CLIP model determine which description is most likely true
- View confidence scores for the predictions

## Prerequisites

- Python 3.7+
- PyTorch
- CLIP
- Streamlit
- PIL (Python Imaging Library)
- CUDA-capable GPU (optional, for faster inference)

## Technical Details

- Uses OpenAI's CLIP model (ViT-B/32 architecture)
- Runs on CPU or CUDA-enabled GPU
- Image preprocessing using CLIP's built-in preprocessing
- Probability calculation using softmax normalization

## Installation & Running

1. Install the required dependencies:

```bash
pip install -r requirements.txt
```

2. Run the Streamlit app:

```bash
streamlit run app.py
```

