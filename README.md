# GPT-2 Hindi Fine-Tuning on OSCAR Dataset

---
## Key Highlights
- **Dataset**: OSCAR Hindi Dataset (from Common Crawl) was used for training.
- **Model**: Fine-tuned the **GPT-2 Small** model using Hugging Face's `transformers` library.
- **Tokenization**:
  - Text was tokenized using the **IndicNLP tokenizer** for Hindi.
  - The IndicNLP tokens were mapped to the GPT-2 tokenizer to ensure compatibility with the model's architecture.
- **Training**:
  - The model was trained for **3 epochs**.
  - Training was conducted on **Google Colab** with GPU acceleration.
- **Results**:
  - Outputs improved significantly across epochs in terms of fluency, grammar, and coherence.
  - Generated text shows strong alignment with Hindi syntax and semantics.

![Generated Text Comparison](https://github.com/sursorot/GPT2-Oscar-Hindi-Epoch-3/blob/da43c2010ee62eddc5d83a3b889c64373bec96bc/Indic_GPT2_Model%20Comparison%20Table.png)

---

## Repository Contents
- **Code**:
  - Scripts and notebooks for data preprocessing, tokenization, and model training.
- **Dataset**:
  - Instructions for downloading and processing the OSCAR Hindi dataset.
- **Model Checkpoints and Tokenized Data**:
  - Trained model checkpoints for `indic_gpt2_epoch3` and a subset of the Mapped Tokenized Oscar Data for `indic_gpt2_tokenized.arrow`.
- **Results**:
  - Comparative analysis of outputs from different epochs.
- **Documentation**:
  - Step-by-step instructions for replicating the training process.
---
## Features
- Custom tokenization for Hindi text using IndicNLP.
- Fine-tuning of a pre-trained GPT-2 model to adapt to Hindi.
- Preprocessed dataset and reusable scripts for further training or adaptation.
- Generated sample outputs for evaluation and exploration.
---
## Goals
This project demonstrates the power of adapting large language models like GPT-2 to regional languages. It serves as a foundational step for researchers and developers aiming to build language-specific NLP models for tasks like:
- Text generation
- Dialogue systems
- Creative writing in Hindi
---
Feel free to explore the repository and contribute!
You can reach me @ latinquarter24@gmail.com
