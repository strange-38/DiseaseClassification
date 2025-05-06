# Medical Text Classification with Bio_ClinicalBERT

This project demonstrates the use of **Bio_ClinicalBERT**, a BERT-based transformer model pre-trained on clinical and biomedical texts, for **medical text classification**. The model is fine-tuned on a dataset of medical abstracts extracted from doctor's prescriptions, aiming to classify them into various **disease categories**.

## 🚀 Key Features

- ✅ **Bio_ClinicalBERT**: Leverages domain-specific BERT for superior understanding of clinical language.
- ✅ **Fine-tuning**: Uses the **AdamW** optimizer and **cross-entropy loss** for efficient training.
- ✅ **Early Stopping**: Monitors validation loss to prevent overfitting during training.
- ✅ **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score

## 🔬 Model Details

- **Model**: `emilyalsentzer/Bio_ClinicalBERT`
- **Task**: Multi-class classification
- **Dataset**: Medical abstracts from prescriptions

## 📌 References

- [Bio_ClinicalBERT on HuggingFace]https://huggingface.co/datasets/123rc/medical_text/tree/main)
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
