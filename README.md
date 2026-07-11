# End-to-End Text Analytics with Python

## Case Study: Pride and Prejudice by Jane Austen

This project performs an end-to-end Natural Language Processing (NLP) analysis of *Pride and Prejudice* by Jane Austen using the HTML version from Project Gutenberg.

The project demonstrates the complete text analytics workflow, from collecting web data to cleaning, preprocessing, exploratory data analysis, and visualization.

---

## Objectives

- Download a novel from Project Gutenberg
- Parse HTML using BeautifulSoup
- Clean and preprocess textual data
- Perform Natural Language Processing (NLP)
- Explore vocabulary, character prominence, and writing style
- Visualize key findings

---

## Dataset

**Source**

Project Gutenberg

Book:
*Pride and Prejudice* by Jane Austen

Format:
HTML

---

## Tools & Libraries

- Python
- Requests
- BeautifulSoup (bs4)
- NLTK
- Matplotlib

---

## Project Workflow

1. Download HTML webpage using Requests
2. Save raw HTML locally
3. Parse HTML using BeautifulSoup
4. Remove Project Gutenberg metadata
5. Remove front and back matter
6. Save cleaned text
7. Preprocess text
   - Lowercase conversion
   - Tokenization
   - Punctuation removal
   - Stopword removal
8. Perform Exploratory Data Analysis
9. Create visualizations
10. Summarize insights

---

## Key Findings

- The processed novel contains approximately **55,900 words** after preprocessing.
- Approximately **6,800 unique words** were identified.
- Lexical diversity is **0.122**, indicating a reasonably varied vocabulary despite repeated references to key characters.
- Elizabeth is the most frequently mentioned character, followed by Darcy.
- Dialogue-related words such as *could*, *would*, and *said* remain highly frequent after preprocessing.
- Character names and family-related terms dominate the vocabulary, reflecting the novel's emphasis on interpersonal relationships.

---

## Repository Structure

```
gutenberg_text_analysis/

├── data/
│   ├── raw/
│   │   └── pride_and_prejudice.html
│   └── processed/
│       └── pride_and_prejudice_clean.txt
│
├── images/
│   ├── top20_words.png
│   ├── top20_words_no_characters.png
│   ├── character_mentions.png
│   └── word_length_distribution.png
│
├── notebooks/
│   └── gutenberg_analysis.ipynb
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Sample Visualizations

- Top 20 Most Frequent Words
- Top Words Excluding Character Names
- Character Mentions
- Word Length Distribution

---

## Future Improvements

- Compare multiple Jane Austen novels
- Perform chapter-level analysis
- Build an interactive Streamlit dashboard
- Apply sentiment analysis
- Explore topic modelling and named entity recognition

---

## Author

Created by **Namya Nichani** as part of a personal Data Analytics portfolio.