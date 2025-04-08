# 🦺 HSE Expert Chatbot — Fine-Tuning DeepSeek R1 with LoRA & Unsloth

This project fine-tunes the [`DeepSeek R1`](https://huggingface.co/unsloth/DeepSeek-R1-Distill-Llama-8B) language model to act as an expert in **Health, Safety, and Environment (HSE)** topics.

The resulting model functions as a chatbot capable of answering expert-level questions on:
- Occupational safety
- Hazard identification
- Workplace health
- Regulatory compliance

It uses **parameter-efficient fine-tuning** with **LoRA** via the [Unsloth](https://github.com/unslothai/unsloth) framework, leveraging real-world datasets and custom instruction-tuned prompts to improve performance in safety-critical domains.

---

## 📌 Project Details

- **Base Model**: [`deepseek-ai/DeepSeek-V2`](https://huggingface.co/unsloth/DeepSeek-R1-Distill-Llama-8B)
- **Fine-tuning Method**: LoRA (Low-Rank Adaptation)
- **Library**: [Unsloth](https://github.com/unslothai/unsloth)
- **Dataset**: [`FreedomIntelligence/medical-o1-reasoning-SFT`](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT)
- **Purpose**: Build an instruction-following chatbot for HSE topics

---

## 📂 Files

```bash
.
├── DeepSeekFineTune.ipynb   # Main notebook for fine-tuning using LoRA and Unsloth
├── README.md                # Project documentation
