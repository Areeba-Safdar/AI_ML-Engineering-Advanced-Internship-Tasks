# 📰 News Topic Classifier Using BERT

## Objective
Build a news topic classifier by fine-tuning the *bert-base-uncased* model on the *AG News* dataset to classify news headlines into four categories: World, Sports, Business, and Sci/Tech.

## Dataset
- *Dataset:* AG News
- *Source:* Hugging Face Datasets

## Technologies Used
- Python
- Google Colab
- Hugging Face Transformers
- PyTorch
- Scikit-learn
- Gradio

## Methodology
- Loaded and explored the AG News dataset.
- Tokenized the text using the BERT tokenizer.
- Fine-tuned the bert-base-uncased model.
- Evaluated the model using Accuracy and F1-score.
- Built a Gradio interface for real-time predictions.

## Results
- *Accuracy:* 92.24%
- *F1-Score:* 92.24%

## Project Files
- News_Topic_Classifier_BERT.ipynb – Complete implementation
- requirements.txt – Required Python libraries

## Future Improvements
- Train on the full dataset.
- Compare with other transformer models such as RoBERTa and DistilBERT.
- Deploy on Hugging Face Spaces.

## Author
*Areeba Safdar*  
BS Computer Science | AI/ML Intern
