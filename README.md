# Llama 3 Medical Diagnosis

## Introduction

In the ever-evolving field of healthcare, accurate and timely medical diagnosis is paramount. With advancements in artificial intelligence (AI) and natural language processing (NLP), there is an opportunity to leverage these technologies to enhance diagnostic processes, providing support to medical professionals and improving patient outcomes. This project, "Llama 3 Medical Diagnosis," aims to harness the power of AI to build a robust medical diagnostic tool.

## Key Features

- **Efficient Model Training**: Utilizes the `unsloth` library for efficient handling and customization of the language model, with Low-Rank Adaptation (LoRA) adapters to expedite the training process.
- **Data Preparation**: Employs the open-source `Processed_Medicalbot_Dataset` from Hugging Face, with preprocessing to align with model requirements.
- **Model Fine-Tuning**: Configured and fine-tuned using `SFTTrainer` and `TrainingArguments` from the `trl` and `transformers` libraries.
- **Fast Inference**: Enabled faster inference using `FastLanguageModel.for_inference` to provide timely medical recommendations.

## Installation

To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/llama-3-medical-diagnosis.git
cd llama-3-medical-diagnosis
pip install -r requirements.txt
```
## Dataset

The dataset used in this project is the `Processed_Medicalbot_Dataset` from Hugging Face. You can access it [here](https://huggingface.co/datasets/oudaher/Processed_Medicalbot_Dataset?row=0).

## Conclusion

The "Llama 3 Medical Diagnosis" project demonstrates the application of advanced AI and NLP technologies to enhance medical diagnostic processes. By leveraging efficient model handling, fine-tuning, and fast inference capabilities, this project provides a robust foundation for an AI-driven medical diagnostic tool. The model shows significant potential to assist healthcare professionals by generating relevant medical recommendations based on user input, ultimately contributing to improved patient care and outcomes.
