
# Autocomplete and Autocorrect System Using Python

## 📌 Overview
This project implements an autocomplete and autocorrect system using a children's stories text corpus. It uses n-gram models to predict the next word and edit distance to suggest corrections for misspelled words.

## 🎯 Objectives
- Load and preprocess a text corpus.
- Tokenize words and analyze word frequencies.
- Implement bigram- and trigram-based autocomplete.
- Generate the top three next-word predictions.
- Implement spelling correction using edit distance.
- Evaluate autocorrect performance using classification metrics.
- Visualize frequent words and evaluation results.
- Identify limitations and possible improvements.

## 📂 Dataset
**Input file:** `cleaned_merged_fairy_tales_without_eos.txt`

The text corpus contains fairy tales and children's stories, including works by Oscar Wilde.

## 🛠️ Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- NLTK
- PySpellChecker
- Regular Expressions

## ⚙️ Workflow
1. Load and inspect the text corpus.
2. Preprocess the text and tokenize words.
3. Calculate the most frequent words.
4. Build bigram and trigram language models.
5. Generate the top three next-word predictions for test prefixes.
6. Implement autocorrect using edit distance and spelling suggestions.
7. Test deliberately misspelled words.
8. Calculate accuracy, precision, recall, and F1-score.
9. Generate charts and a confusion matrix.
10. Analyze errors and limitations.

## 🧠 Key Techniques
- Text preprocessing
- Tokenization
- Word-frequency analysis
- Bigram and trigram models
- Edit distance
- Spelling correction
- Model evaluation

## 📊 Outputs
- Top 20 frequent words chart
- Autocomplete predictions
- Autocorrect test results
- Accuracy, precision, recall, and F1-score
- Confusion matrix
- Evaluation visualizations

## ▶️ How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
2. Upload `cleaned_merged_fairy_tales_without_eos.txt`.
3. Install the required libraries.
4. Ensure the file path is correct.
5. Run the notebook cells in order.
6. Review the predictions, metrics, and visualizations.

## 📚 Learning Outcomes
- Understanding basic Natural Language Processing (NLP).
- Building frequency-based autocomplete models.
- Applying edit distance to spelling correction.
- Evaluating text-processing systems.
- Working with text corpora.

## ⚠️ Limitations
- Predictions depend on patterns in the training corpus.
- Unseen words may reduce prediction accuracy.
- Synthetic spelling errors may not reflect real-world mistakes.
- Frequency-based models do not fully understand context or meaning.
## 🏷️ Tags
`Python` `NLP` `Autocomplete` `Autocorrect` `TextProcessing` `DataAnalytics`
