# Word Frequency Analyzer

Python notebook that computes word frequencies and type/token ratio
for Jane Austen's *Emma* (NLTK Gutenberg corpus).

## Results
- Tokens: 161,096
- Types: 7,225
- Type/token ratio: 0.045
- The most frequent words are function words (to, the, and, of).

## How to run
Open `word_frequency_analysis.ipynb` in Google Colab and run the cell.
## Stopword removal
After removing English stopwords (NLTK list), tokens drop from 161,096 to 71,590.
The most frequent words are now character names (emma, harriet, weston, knightley)
and titles (mrs, miss).
