# Prodigy InfoTech Internship - Task 01: GPT-2 Text Generation

## 📌 Task Objective

Train a language model to generate coherent and contextually relevant text based on a given prompt. This project uses GPT-2, a transformer-based language model by OpenAI, and fine-tunes it on a custom dataset.

## 🚀 What I Did

- Used the HuggingFace `transformers` library to fine-tune GPT-2.
- Prepared a custom `.txt` dataset with training samples.
- Configured training using `TrainingArguments` and `Trainer`.
- Disabled `wandb` and logging integrations for clean execution in Google Colab.
- Saved and exported the trained model.
- Generated text from the trained model using a prompt.

## 🧠 Model Used

- GPT-2 (`gpt2`) from HuggingFace

## 📁 Dataset

A simple `.txt` file with custom sentences to mimic a particular writing style. (Uploaded via Colab)

## 📈 Training Configuration

- Epochs: 2
- Batch Size: 1
- Block Size: 128
- Optimizer: AdamW
- Fine-tuned in Google Colab with GPU

## 💬 Sample Generated Text

> **Prompt**: "Once upon a midnight moon,"  
> **Generated**: _"Once upon a midnight moon, the stars whispered secrets to the waves. The tide carried dreams ashore..."_

## 💡 How to Run

1. Upload your `.txt` file in Colab
2. Run the notebook to train GPT-2
3. Generate text using `pipeline()`
4. Save the trained model and download it

## 📦 Output Files

- `gpt2-finetuned` (directory with model + tokenizer)
- `gpt2-finetuned.zip` (compressed model for submission)

## 🖥️ Tech Stack

- Python
- HuggingFace Transformers
- Google Colab
- PyTorch

---

## ✅ Task Status

- ✅ Task Completed
- 🔁 Submitted as part of the **Generative AI Internship at Prodigy InfoTech**
