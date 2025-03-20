# Sentiment Analysis on Imbalanced Dataset  

## Overview  
This repository contains a research project on sentiment analysis using an imbalanced Twitter dataset. The study explores various balancing techniques and machine learning models to improve classification accuracy.  

## Dataset  
- **Train-Test Split**: 80% training, 20% testing  
- **Source**: Twitter sentiment dataset  

## Techniques Implemented  
### **Baseline Model**  
- Built an initial model without applying any balancing techniques  

### **Balancing Techniques**  
- SMOTE (Synthetic Minority Over-sampling Technique)  
- ADASYN (Adaptive Synthetic Sampling)  
- SMOTE + Tomek Links  
- Random Undersampling (RUS)  

### **Modeling & Evaluation**  
- Used **XGBoost** with label encoding  
- Hyperparameter tuning for optimal performance  
- Feature importance analysis to understand key contributors  

### **Libraries Used**  
- **spaCy**: NLP preprocessing and tokenization  
- **demojize**: Emoji conversion for text normalization  

## Future Work  
- Testing additional machine learning models for better accuracy  
- Fine-tuning existing models to improve performance  
- Exploring deep learning-based approaches for sentiment analysis  

## How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/somewherelostt/Sentiment-Imbalance-Research.git
   cd Sentiment-Imbalance-Research
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt //will update that
   ```  
3. Run the Colab notebooks in sequence for end-to-end analysis  

## Contact  
For any queries or collaborations, feel free to reach out.  

---
