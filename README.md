
# Google Review NLP Analyzer

This project automatically collects, translates, analyzes, and summarizes multilingual Google Maps reviews using NLP techniques.

## 🔍 Project Goal

To assist users in understanding the overall sentiment and key opinions expressed in Google reviews across multiple languages.

## 🚀 Workflow

1. 🔎 Search for a place using the Google Maps API.
2. 🌐 Collect reviews in multiple languages.
3. 🌍 Translate all reviews to English using the Google Translate API.
4. 🤖 Run sentiment classification using a BERT-based model.
5. 🧠 Summarize reviews by sentiment class (Bart-based summarizer).
6. 📊 Output final summaries for positive and negative sentiments.

## 📂 Folder Structure

```
├── review_clean.ipynb        # Cleaned notebook for GitHub
├── review_cleaned.txt        # Translated and filtered reviews
├── README.md                 # This file
```

## ⚙️ Requirements

- Python 3.8+
- `transformers`
- `requests`
- `pandas`
- `matplotlib` (optional for charts)

Install via:
```bash
pip install transformers requests pandas matplotlib
```

## 📎 Example Output

```
✅ Summary of Positive Reviews:
"The staff were friendly and the food was excellent..."

❌ Summary of Negative Reviews:
"Wait times were long and portions were too small..."
```

## 🔐 Security Warning

Please **do not expose your Google API Key** in any public repo. Replace it with `"YOUR_API_KEY_HERE"` before uploading.


## 📈 Future Work

- Add visualization (e.g., pie chart or bar chart for sentiment distribution)
- Deploy as a Streamlit web app for easier access
