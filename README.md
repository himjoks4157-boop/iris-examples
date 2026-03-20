# 🌸 Iris Examples

This repo contains examples of how to use Iris, a fine-tuned SLM by Joks8474.

## Quick Start

```python
from transformers import pipeline

pipe = pipeline("text-generation", model="Joks8474/Iris-0.5B-v0.1")
response = pipe("How do I reverse a list in Python?")[0]['generated_text']
print(response)
