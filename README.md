# DSA4213 Assignment 3 — Parameter-Efficient Fine-Tuning with LoRA

**Author:** Fong Kang Wei  
**Files:**  
- `FongKangWei_Assignment_3_Report.pdf` – Written report with methodology, results, and analysis  
- `dsa4213_assignment3.ipynb` – Jupyter notebook with full experimental workflow  
- `requirements.txt` – Environment dependencies  
- `README.md` – Project overview and setup instructions

---

## 📘 Project Overview

This project compares **Full Fine-Tuning** and **Low-Rank Adaptation (LoRA)** on the IMDb movie reviews dataset for **binary sentiment classification** using the `DistilBERT-base-uncased` model.  
The goal is to evaluate trade-offs between **performance** and **computational efficiency** (training time, memory, and accuracy).

Key findings:
- LoRA achieved slightly higher accuracy and F1 than full fine-tuning.  
- LoRA used less memory and was more efficient per epoch.  
- Both models struggled with linguistically complex or truncated reviews.

---

## ⚙️ Environment Setup

To recreate the environment, run:

```bash
pip install -r requirements.txt

---

## 📄 License

This repository and its contents were submitted as part of  
**NUS DSA4213: Natural Language Processing for Data Science** in AY 25/26 Semester 1.  
