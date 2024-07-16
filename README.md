# Model Comparison README

## Main Points

**Text Preprocessing:**

- Tokenization
- Stopword Removal
- TF-IDF Vectorization

**Models Compared:**

1. **Multinomial Naive Bayes:**

   - Precision: 0.78 (class 0), 0.84 (class 1)
   - Recall: 0.91 (class 0), 0.65 (class 1)
   - F1-Score: 0.84 (class 0), 0.73 (class 1)
   - Accuracy: 0.80
   - Macro Avg F1-Score: 0.79
   - Weighted Avg F1-Score: 0.79

2. **Linear SVC:**

   - Precision: 0.81 (class 0), 0.76 (class 1)
   - Recall: 0.83 (class 0), 0.74 (class 1)
   - F1-Score: 0.82 (class 0), 0.75 (class 1)
   - Accuracy: 0.79
   - Macro Avg F1-Score: 0.78
   - Weighted Avg F1-Score: 0.79

3. **BERT Model:**
   - Precision: 0.85 (class 0), 0.81 (class 1)
   - Recall: 0.86 (class 0), 0.79 (class 1)
   - F1-Score: 0.86 (class 0), 0.80 (class 1)
   - Accuracy: 0.83
   - Macro Avg F1-Score: 0.83
   - Weighted Avg F1-Score: 0.83

**Conclusion:**

- The BERT model achieved the highest performance across all metrics.
- Linear SVC and Multinomial Naive Bayes also performed well, with Linear SVC showing slightly better metrics than Naive Bayes.
