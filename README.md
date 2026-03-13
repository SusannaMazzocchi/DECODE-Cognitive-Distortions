# 🧠 DECODE: DEtection of COgnitive Distortions in Expressions

--------

## 📝 Short introduction on the project
Hi, I'm Susanna! I care deeply about this project because it merges Artificial Intelligence with our brains. 

**DECODE** is an NLP (Natural Language Processing) project designed to detect cognitive distortions in textual evidence from psychological counselling dialogues. Cognitive distortions are irrational or biased ways of thinking that usually lead to psychological distress, like anxiety or depression. 
Using the "Therapist Q&A" dataset from Kaggle, the main objective of this project is to solve a binary text classification problem: teaching the AI to understand if a specific text sample contains a cognitive distortion or if it doesn't.

--------

## 🛠️ Technologies/tools used
* **Python**.
* **Google Colab** - The environment where I wrote and ran the `DECODE.ipynb` notebook.
* **Hugging Face (Transformers)** - Used to fine-tune state-of-the-art language models (like BERT/RoBERTa).
* **PyTorch / Scikit-learn** - For model training, deep learning, and evaluation metrics.
* **Pandas & Matplotlib** - For data analysis and visualization.

--------

## ✨ Features
* **Binary Text Classification:** A fully trained pipeline that reads counselling dialogues and flags the presence of irrational thinking.
* **Fine-Tuned NLP Models:** I didn't just use basic algorithms; I worked with powerful Transformer models to truly understand the context of the psychological texts.
* **Complete Repository:** I've included the original dataset, a `trained_models` folder with the exported results, and the full project report so you can dive deep into the theory and results!

--------

## 🚀 Process
I started by analyzing the Kaggle dataset, exploring the psychologically tagged examples of questions and answers. Since text data can be very messy, I had to clean and preprocess the dialogues. 
Then, I moved to the exciting part: setting up the NLP models. I used Hugging Face's tools to fine-tune pre-trained language models so they could learn the specific "psychological language" of the dataset. I ran multiple tests and evaluated the models using classification metrics.

--------

## 🧠 What I learned
This project was a massive milestone for me. It was my first deep dive into Text Mining and Natural Language Processing (TMNLP) for my Bachelor in AI. I learned how to handle real-world, unstructured text data and how to use Hugging Face's ecosystem to fine-tune complex Transformer models. 
But more than just the technical skills, this project showed me the real-world impact AI can have. Seeing a machine learn to recognize human psychological distress was both challenging and incredibly rewarding.

--------

## 🔧 How could it be improved
If I continue working on DECODE, I would love to:
* **Go beyond Binary Classification:** Instead of just detecting *if* a distortion is present, I want to train the model to classify *which exact type* of cognitive distortion it is (e.g., Catastrophizing, Overgeneralizing, etc.).
* **Build a User Interface:** It would be amazing to create a simple web app where anyone can type a sentence they are thinking and get real-time feedback on whether their thought is distorted.
* **Larger Datasets:** Train the model on more diverse psychological transcripts to make it even more accurate and inclusive.

--------

## ▶️ How to run the project
I developed the entire code on Google Colab to make it easily accessible. 
Instead of a long list of instructions here, **please read the `requirements` file**. Inside, you will find everything you need to know to run the `DECODE.ipynb` notebook, install the right dependencies, and load the dataset and `trained_models` correctly! 

📄 *For a deeper look into the design choices, model comparisons, and mathematical metrics, please read the included full report: `[TMNLP 2024-2025] DECODE report.pdf`.*
