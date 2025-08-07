# Wekeza LLM v6 — LoRA Fine-Tuning with Multimodal CoT Reasoning

This project fine-tunes a small causal language model (`distilgpt2-wekeza-finetuned_v5_cot_lora`) using LoRA on a dataset of Kenyan financial questions with **Chain-of-Thought (CoT)** rationales tagged by reasoning mode: `math`, `logical`, and `ethical`.

## 🔧 Model Version
- Base Model: `distilgpt2-wekeza-finetuned_v5_cot_lora`
- Fine-tuned Model: `wekeza_v6_lora_multimodal`
- LoRA modules: `q_proj`, `v_proj`
- Dataset: `kenyan_finance_selfinstruct_v6_instructzero.jsonl` → `wekeza_multimodal.json`

## 🧠 Key Features
- Multimodal CoT generation (math, logic, ethics)
- Instruction-style format (Alpaca-style)
- PEFT: Lightweight LoRA fine-tuning
- Built for local Kenyan financial reasoning

## 🗃️ Files
- `wekeza_v6_lora_multimodal_cot_finetuning.ipynb`: LoRA fine-tuning notebook

## 📈 Goal
Improve Wekeza LLM’s reasoning ability across multiple domains in Kenyan finance by training on diverse, structured, and interpretable CoT outputs.

---
