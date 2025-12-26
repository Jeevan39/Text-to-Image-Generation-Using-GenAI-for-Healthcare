# GenAI Healthcare Text-to-Image Generator

A Generative AI–based healthcare image synthesis system that converts medical text prompts into realistic images using Stable Diffusion and LoRA fine-tuned models. This project enables the generation of synthetic medical images such as MRI scans, CT scans, X-rays, and anatomical visuals for research, education, and experimentation.

---

## Project Overview

Medical imaging datasets are often limited due to privacy, cost, and availability constraints. This project leverages diffusion-based generative models to produce high-quality synthetic healthcare images from textual descriptions, helping overcome data scarcity while preserving patient privacy.

The system provides a Gradio-based web interface where users can enter prompts and choose between Stable Diffusion and LoRA-enhanced models for image generation.

---

## Features

- Text-to-image generation for healthcare scenarios  
- Supports Stable Diffusion v1.5  
- Optional LoRA fine-tuned model for domain-specific accuracy  
- Interactive Gradio Web UI  
- GPU acceleration support (CUDA)  
- No real patient data used (privacy-preserving)  

---

## Technologies Used

- Python  
- PyTorch  
- Hugging Face Diffusers  
- Stable Diffusion  
- LoRA (Low-Rank Adaptation)  
- Gradio  
- Transformers  
- Google Colab / Local GPU  

---
