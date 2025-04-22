🧠 AI News Summarizer using Hugging Face
This project implements an AI-powered summarizer that condenses lengthy news articles into concise, meaningful summaries. It leverages the facebook/bart-large-cnn model from Hugging Face Transformers and uses ROUGE scores to evaluate summarization quality.

🔧 Key Features:
Summarizes real-world news articles using state-of-the-art NLP models.

Uses the CNN/DailyMail dataset for input and reference summaries.

Evaluates summaries using ROUGE-1, ROUGE-2, and ROUGE-L.

Built entirely on Google Colab using free-tier resources.

No OpenAI API required — uses Hugging Face models locally.

🛠 Tech Stack:
Hugging Face transformers & datasets

rouge-score for evaluation

Python + Google Colab

🚀 How It Works:
Load and preprocess a subset of the CNN/DailyMail dataset.

Use BART to generate summaries from article texts.

Compare generated summaries against reference highlights using ROUGE.

Display average evaluation scores for model performance insights.

📈 Sample Output:
Average ROUGE Scores (on 10 articles):

ROUGE-1: ~0.41

ROUGE-2: ~0.19

ROUGE-L: ~0.37
