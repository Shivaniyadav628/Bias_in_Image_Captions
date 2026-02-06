
# Bias Detection and Mitigation in Image Captioning

## Overview
This project analyzes gender bias in a multimodal image captioning model and applies a mitigation strategy to reduce unfair gender inference.

## Model Used
- BLIP (Bootstrapped Language-Image Pretraining)
- Vision–Language Transformer
- Hugging Face Transformers, PyTorch

## Methodology
1. Generated captions for images containing people
2. Detected gender bias using lexical indicators
3. Quantified bias percentage
4. Applied gender-neutral mitigation
5. Compared bias before and after mitigation

## Results
| Stage | Bias Percentage |
|------|----------------|
| Before Mitigation | 100% |
| After Mitigation | 0% |

## Conclusion
Simple post-processing techniques can significantly reduce explicit gender bias in image captioning systems. Future work includes studying implicit bias.

## Tech Stack
Python, PyTorch, Transformers, Vision–Language Models
