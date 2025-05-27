# 1. Tweet Emotion Recognition
Goal: Classify a tweet's emotional tone (like joy, anger, sadness, etc.)

Key components:

Data: Hugging Face datasets (like emotion or tweet_eval)

Preprocessing: Tokenization (using BERT/DistilBERT tokenizer)

Model: Transformer-based (BERT, RoBERTa, etc. with TensorFlow/Keras)

Output: Emotion class label

Evaluation: Accuracy, F1-score, Confusion matrix

✅ Already using: Hugging Face, TensorFlow



# 2. Object Localization
Goal: Detect and localize objects in an image (bounding box + class label)

Key components:

Backbone: EfficientNet (from timm)

Library: PyTorch

Data Augmentation: Albumentations

Output: (x_min, y_min, x_max, y_max) + class

Losses: Usually regression + classification (e.g., MSE + CrossEntropy)

✅ Already using: EfficientNet + Albumentations + PyTorch
