# 🧠 Fine-Tuning DeepSeek R1 (8B) for Medical Reasoning (Chain-of-Thought)

## 📖 Project Overview

This project focuses on fine-tuning a domain-specific medical reasoning model using **DeepSeek R1 Distill LLaMA 8B**.  
The main objective was to transform a general-purpose language model into a system capable of **structured clinical reasoning** and **step-by-step medical explanations**.

---

## 🚀 What This Project Does

- Enhances **medical question answering** with clinical reasoning
- Generates structured **Chain-of-Thought (CoT)** explanations using `<think>` tags
- Provides more **interpretable and logically consistent** responses
- Improves AI support for **medical education and research**

---

## 🛠️ Technical Stack

- PyTorch
- Hugging Face Transformers
- PEFT (LoRA)
- QLoRA (4-bit quantization)
- Unsloth (for optimized fine-tuning)
- Weights & Biases (wandb)
- Google Colab (Tesla T4 GPU)

---

## ⚙️ Key Optimizations

- Gradient Accumulation for larger effective batch size  
- Gradient Checkpointing to reduce GPU memory usage  
- Sequence length tuning for limited GPU environments  
- Efficient fine-tuning using QLoRA + LoRA (PEFT)

---

## 🧪 Sample Capability

**Medical Query Example:**

> “A 61-year-old woman with urine leakage during coughing and sneezing but not at night. What would cystometry show?”

**Model Output:**
- Step-by-step clinical reasoning
- Structured Chain-of-Thought explanation
- Relevant medical conclusion

---

## ⚠️ Limitations

- Not intended for real-world medical diagnosis  
- For **research and educational purposes only**

---

## 🎯 Objective

This project explores how AI can support **healthcare and education** through:
- Interpretable reasoning models
- Efficient fine-tuning techniques
- Domain-specific adaptation of LLMs

---

## 🤝 Open To

- Feedback
- Collaboration
- Research discussions

---

## 📬 Contact

📧 Email: your.email@example.com  
📱 Phone: +92-XXXXXXXXXX  
💼 GitHub: https://github.com/yourusername
