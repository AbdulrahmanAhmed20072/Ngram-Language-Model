# N-gram Language Model

This repository contains an implementation of N-gram language models for text processing, probability estimation, and text prediction. The project showcases various NLP techniques to build, evaluate, and use language models.

## Features

- **Text Preprocessing**: Tokenizes text into sentences and words, and replaces out-of-vocabulary words with `<UNK>`.
- **N-gram Counts**: Calculates uni-gram, bi-gram, tri-gram, and higher-order N-gram counts.
- **Probability Estimation**: Uses Laplace smoothing for estimating probabilities.
- **Perplexity Calculation**: Evaluates the model's performance using perplexity metrics.
- **Word Suggestions**: Generates word predictions based on previous context using N-grams.

## Files

1. **`Ngram_LanguageModel.py`**: Python script implementing the project.
2. **Dataset**: `en_US.twitter.txt` (example data used for training and testing).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AbdulrahmanAhmed20072/Ngram-Language-Model.git
   ```
2. Install the required Python packages:
   ```bash
   pip install numpy pandas nltk
   ```

## Usage

1. Preprocess text data:
   - Split into sentences and tokens.
   - Replace unknown words with `<UNK>`.
2. Train the N-gram model:
   - Compute N-gram counts.
   - Estimate probabilities with smoothing.
3. Evaluate using perplexity.
4. Generate word predictions or text suggestions.

Run the script:
```bash
python Ngram_LanguageModel.py
```

## Outputs

- Vocabulary and tokenized data.
- N-gram counts and probabilities.
- Perplexity metrics for test sentences.
- Word and text predictions based on N-grams.

## Example

Input Text:
```
I like a
```

Suggested Word:
```
cat (Probability: 0.345)
```
