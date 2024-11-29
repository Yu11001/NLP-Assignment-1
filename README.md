# Text Processing for Assignment 1

## Intro

This Python script performs several text processing tasks on a given input file (`alice29.txt`). The operations include:

- Cleaning the text
- Tokenizing it into sentences and words
- Counting word frequencies
- Extracting the top 10 most common words

The processed results are saved into respective output files.

---

## Features

1. **Text Cleaning:**

   - Converts all text to lowercase.
   - Removes punctuation and extra whitespace.
   - Save the cleaned file to `cleaned.txt`

2. **Sentence Tokenization:**

   - Splits the text into sentences using `nltk.sent_tokenize`.

3. **Word Tokenization:**

   - Splits sentences into individual words using `nltk.word_tokenize`.
   - Saves all words (one per line) in `words.txt`.

4. **Word Frequency Analysis:**
   - Counts the frequency of each word in the text.
   - Extracts the top 10 most frequently used words.
   - Saves these words along with their frequencies in `top10words.txt`.

---

## Input and Output Files

### Input

- **`./data/alice29.txt`:** The original text file to be processed.

### Output

1. **`./data/sentences.txt`:** a clean version of text.
2. **`./data/words.txt`:** lists of tokenized sentences and words.
3. **`./data/top10words.txt`:** the top 10 most frequent words and their counts

---

## Required Libraries

- **`nltk`**- Natural Language Toolkit
- **`re`**- Regular Expressions
- **`collections`**- Counter

---

### **Installation:**

```python
    pip install nltk
```
