# plagiarism_detecor
This project is a Streamlit-based web app that analyzes text using NLP. It preprocesses the text, calculates perplexity using an N-gram language model, computes burstiness, and visualizes the most frequent and repeated words. Ideal for detecting AI-generated text and exploring word usage patterns. Built with Python, NLTK, and Matplotlib.

📊 Language Model Text Analysis App

This is a Streamlit-based web app that performs language model-based analysis on a given input text. It visualizes the most frequent and repeated words, calculates perplexity and burstiness, and predicts whether the text is likely generated by an AI language model.

Features

- 📌 Preprocessing: Lowercasing, stopword removal, punctuation filtering
- 📈 Most Common Words Bar Chart
- ♻️ Repeated Words Visualization
- 📉 Perplexity using N-gram Language Model (MLE)
- ⚡ Burstiness Score Calculation
- 🧠 AI Text Detection Heuristic

## 🛠️ Technologies Used

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [NLTK (Natural Language Toolkit)](https://www.nltk.org/)
- [Matplotlib](https://matplotlib.org/)

## 📦 Installation

```bash
# 1️⃣ Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# 2️⃣ Navigate to the project folder
cd your-repo-name

# 3️⃣ Create a virtual environment
python -m venv venv

# 4️⃣ Activate the virtual environment
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

# 5️⃣ Install dependencies
pip install -r requirements.txt

# 6️⃣ Run the Streamlit app
streamlit run app.py

