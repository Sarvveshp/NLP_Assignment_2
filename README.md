# 🧠 AI News Summarizer using Hugging Face

This project implements an AI-powered summarizer that condenses lengthy news articles into concise, meaningful summaries. It uses the `facebook/bart-large-cnn` model from Hugging Face Transformers and evaluates the quality of summaries using ROUGE metrics.

## 🔧 Key Features

- Summarizes real-world news articles using a state-of-the-art pretrained model
- Uses the **CNN/DailyMail** dataset for benchmarking
- Evaluates summaries using **ROUGE-1**, **ROUGE-2**, and **ROUGE-L**
- Built and tested entirely on **Google Colab**
- Does **not require OpenAI API keys**

## 🛠 Tech Stack

- 🧠 Model: `facebook/bart-large-cnn`
- 📚 Dataset: CNN/DailyMail (`cnn_dailymail`)
- 📊 Evaluation: `rouge-score`
- 🧰 Tools: Hugging Face Transformers, Datasets, Python, Google Colab

## 🚀 How It Works

1. Load a subset of the CNN/DailyMail dataset
2. Generate summaries using the BART model via Hugging Face's pipeline
3. Compare generated and reference summaries using ROUGE
4. Output average scores across samples

## 📈 Sample Results

Average ROUGE Scores on 10 sample articles:

- **ROUGE-1**: ~0.41
- **ROUGE-2**: ~0.19
- **ROUGE-L**: ~0.37
