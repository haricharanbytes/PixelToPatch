# PixelToPatch

## Overview
**PixelToPatch** is a project that explores image classification using **Vision Transformers (ViTs)**. The repository provides resources such as Jupyter notebooks, datasets, and documentation to help you understand and implement Vision Transformers for image classification tasks.

## What are Vision Transformers (ViTs)?
Vision Transformers (ViTs) are a deep learning architecture that applies transformer models—originally developed for natural language processing (NLP)—to image data. ViTs have shown competitive performance compared to traditional convolutional neural networks (CNNs) in many image classification tasks.

### Key Concepts:
- **Patch Embedding**: In ViTs, images are split into fixed-size patches, which are then flattened and linearly embedded into vectors before being processed by transformer layers.
- **Self-attention Mechanism**: The core idea behind transformers, including ViTs, is the self-attention mechanism, which helps the model focus on different parts of an image depending on the context.
- **Positional Encoding**: Since transformers do not inherently account for spatial relationships (unlike CNNs), positional encodings are added to patch embeddings to retain spatial information.
  
For more detailed information, refer to the **[ViT Concepts](docs/ViT_concepts.md)** document.

## Requirements
To run the notebooks and scripts in this repository, you’ll need the following Python libraries:
- `torch`
- `torchvision`
- `numpy`
- `matplotlib`
- `pandas`
- `tqdm`
- `PIL`

You can install the required dependencies with:
```bash
pip install -r requirements.txt
