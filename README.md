Intelligent Systems for Detecting Hate Speech and Offensive Content — 2024

Objective: Created a multi-class classification model to detect hate speech, offensive language, and neutral content on social media.

Dataset: 24,802 labeled tweets.

Models Used: Logistic Regression, SVM, Random Forest, XGBoost, FFNN, LSTM, BERT, and hybrid models (BERT+CNN, BERT+LSTM).

Key Techniques:
1. Hybrid Architecture: Combined BERT embeddings with LSTM for improved sequential pattern detection, achieving 92% accuracy.

2. Preprocessing: Implemented advanced techniques in text cleaning, tokenization, and feature engineering.

3. Training Optimization: Utilized cosine annealing, gradient accumulation, and early stopping to stabilize training.

4. Hyperparameter Tuning: Optuna was used to fine-tune hyperparameters, enhancing validation accuracy and F1 scores.

5. Class Imbalance Management: Applied oversampling and optimized for macro F1 score (0.77).

Technologies: Leveraged GPU acceleration, mixed-precision training, and frameworks such as TensorFlow/PyTorch.

Outcome: Achieved 92% accuracy and a Macro F1 score of 0.77.

Co-authored-by: ISHA KUMAR <70069912+Isha-pixel@users.noreply.github.com>
Co-authored-by: Rishabh Chaturvedi <192364586+rishabh-iith@users.noreply.github.com>
