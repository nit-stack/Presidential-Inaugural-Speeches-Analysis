# Presidential Inaugural Speeches Analysis

## Project Overview

This project involves analyzing the inaugural speeches of three Presidents of the United States using the NLTK (Natural Language Toolkit) in Python. The speeches analyzed are:

1. President Franklin D. Roosevelt's speech in 1941
2. President John F. Kennedy's speech in 1961
3. President Richard Nixon's speech in 1973

The analysis includes calculating the number of characters, words, and sentences in each speech, removing stopwords, identifying the most common words, and creating word clouds for visualization.

## Table of Contents
- Project Overview
- Installation
- Results
  - Speech Statistics
  - Common Words
  - Word Clouds

## Installation

To run this project, we need the following libraries:

- NLTK
- Matplotlib
- WordCloud

## Results

### Speech Statistics

The following statistics were computed for each speech:

- **1941 – Roosevelt**
  - Sentence count: 69 sentences
  - Word count: 1318 words
  - Character count: 7497 characters

- **1961 – Kennedy**
  - Sentence count: 56 sentences
  - Word count: 1343 words
  - Character count: 7543 characters

- **1973 – Nixon**
  - Sentence count: 71 sentences
  - Word count: 1786 words
  - Character count: 9906 characters

### Common Words

After removing stopwords, the three most common words in each speech are:

- **Roosevelt:**
  - It: 13 occurrences
  - Nation: 11 occurrences
  - We: 10 occurrences

- **Kennedy:**
  - Us: 10 occurrences
  - And, let, pledge, sides, ask: 7 occurrences each
  - To: 6 occurrences

- **Nixon:**
  - Us: 26 occurrences
  - Peace: 19 occurrences
  - Let: 13 occurrences

### Word Clouds

The word clouds for each speech visualize the frequency of words after stopwords are removed.

- **Roosevelt Word Cloud**
  ![Roosevelt Word Cloud](images/roosevelt_wordcloud.png)

- **Kennedy Word Cloud**
  ![Kennedy Word Cloud](images/kennedy_wordcloud.png)

- **Nixon Word Cloud**
  ![Nixon Word Cloud](images/nixon_wordcloud.png)
