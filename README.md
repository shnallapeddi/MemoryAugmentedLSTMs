# Memory Augmented LSTMs
## Title - “Memory on Demand: Can Augmented LSTMs Rival Transformers in Few-Shot Sentiment Analysis?”

### Summary
State-of-the-art sentiment analysis models like e.g., Transformer-based models including BERT, RoBERTa, and DeBERTa have shown good few-shot learning performance but at costly computation and with heavy pretraining. In contrast, LSTM-based models are less computationally demanding but suffer from catastrophic forgetting and hence have their knowledge retention capability for various tasks restricted. This work investigates if MA-LSTMs can serve as an efficient, but lightweight, alternative to Transformers in the context of few-shot sentiment analysis. By embedding a differentiable memory module (i.e., Neural Dictionary, Key-Value Memory), an attempt is made to extend the ability of LSTMs in storing and recalling earlier information to mitigate forgetting at low loss in efficiency. The research aims to establish whether MA-LSTMs can achieve competitive accuracy, improved memory retention, and greater computational efficiency compared to Transformer-based models when applied to few-shot learning. If successful, the method could provide a less resource-hungry alternative to current Transformer-bloated solutions.

### Live Demo
You can try out the few‑shot sentiment analyzer live on Hugging Face Spaces:
https://huggingface.co/spaces/AravindMohan/myFewshotSentimentAnalyser
