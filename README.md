# Grammar Correction Model

This repository contains code to train and fine-tune a grammar correction model using T5 and the Grammar-Correction Dataset.  
It can be used to correct grammatical errors from sentences and can later be deployed in apps, APIs, or services.

---

##  Project Description

This project:
- Uses the **T5-small transformer model** to train a grammar correction model
- Trains on the **agentlans/grammar-correction dataset** from Hugging Face
- Outputs checkpoints that can be saved, evaluated, and deployed
- Is written in Python using Hugging Face Transformers & Datasets

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/grammar-correction-model.git
cd grammar-correction-model 
