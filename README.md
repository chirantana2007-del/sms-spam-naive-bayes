
# Probabilistic SMS Spam Detection

BAMAT207 Probability and Statistics project by Chirantana N (VIT Vellore).

A Python notebook that classifies an SMS as spam or ham with Multinomial Naive Bayes and reports P(Spam | Message) and P(Ham | Message).

## Results (SMS Spam Collection, UCI)
- 5,574 messages loaded, 403 duplicates removed, 5,171 used (653 spam, 4,518 ham)
- P(Spam) = 0.1263, P(Ham) = 0.8737, E(Y) = 0.1263, Var(Y) = 0.1103
- Accuracy 0.9816 on a stratified 20% test set; spam precision 0.9516, recall 0.9008, F1 0.9255
- 6 false positives (ham flagged as spam), 13 false negatives (spam missed)

## Files
- `SMS_Spam_Detection.ipynb` - full notebook with outputs
- `SMSSpamCollection` - dataset
- `class_distribution.png`, `confusion_matrix.png` - charts
- `spam_nb_model.pkl`, `count_vectorizer.pkl` - trained model and vectorizer

## Run
Open the notebook in Colab or Jupyter, keep `SMSSpamCollection` in the same folder and run all cells.
Libraries: pandas, numpy, matplotlib, scikit-learn, joblib.
