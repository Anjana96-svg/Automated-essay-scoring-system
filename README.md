# Automated-essay-scoring-system

The Autonomous Essay Scoring System is an AI-powered application designed to automatically evaluate and score essays based on factors like grammar, coherence, structure, and content relevance. It leverages Natural Language Processing (NLP) and Deep Learning to provide both quantitative scores and qualitative feedback in real time.

Key Features

Automated Scoring: Predicts essay scores using an LSTM (Long Short-Term Memory) model trained on essay datasets.

Text Representation: Utilizes GloVe word embeddings for semantic understanding of sentences.

Feedback Generation: Uses TF-IDF and keyword matching to generate personalized content feedback.

Performance Metrics: Achieved an MSE of 0.37 and a Q-score of 0.89 for score prediction accuracy.

User Interface: Integrated with a Gradio-based web interface for easy essay upload, scoring, and insights visualization.

🧩 Tech Stack

Languages: Python

Libraries: TensorFlow / Keras, NumPy, Pandas, NLTK, Scikit-learn

NLP Tools: GloVe Embeddings, TF-IDF, Tokenization, Lemmatization

Interface: Gradio

Metrics: Mean Squared Error (MSE), Quadratic Weighted Kappa (Q-score)

🚀 How It Works

Input: User uploads or types an essay in the Gradio interface.

Preprocessing: Text is cleaned, tokenized, and converted to GloVe vectors.

Model Prediction: The trained LSTM model predicts a numerical score.

Feedback Generation: TF-IDF and keyword analysis generate improvement tips.

Output: Displays the predicted score and feedback instantly.

<img width="940" height="324" alt="image" src="https://github.com/user-attachments/assets/9aa3d4a3-d641-4636-9ec7-dad664d9edc7" />
