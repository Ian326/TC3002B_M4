# TC3002B

## Description 📝
A research-oriented tool designed to compare and evaluate different NLP approaches for measuring text similarity.  The system implements three distinct similarity calculation methods: Bag-of-Words (BoW), Term Frequency-Inverse Document Frequency (TF-IDF), and Markov Chains, specifically applied to question similarity analysis tasks.

## Project Structure 📚
| Component              | Function                                      | Key Code Entities                               |
| ---------------------- | --------------------------------------------- | ----------------------------------------------- |
| Data Loading           | CSV file ingestion                            | df_file(), archivo = 'questions.csv'            |
| Text Preprocessing     | Cleaning and tokenization                     | clean_text(), array_words()                     |
| BoW Implementation     | Word counting and vectorization               | uniqueWords(), countWords() with 'BoW'          |
| TF-IDF Implementation  | Term frequency and inverse document frequency | countWords() with 'TF', idf(), tfByIDF()        |
| Markov Implementation  | Transition matrices and probabilities         | word_follow(), word_follow_matrix()             |
| Similarity Calculation | Cosine similarity computation                 | cosine_similarity(), cosine_similarity_matrix() |

## Processing Flow 🔄
![image](https://github.com/user-attachments/assets/85494b0d-de4d-4e87-aead-6d82c8c3b34d)

## Context ❔
This system provides:
- **Multi-method comparison:** Simultaneous implementation of BoW, TF-IDF, and Markov Chain approaches
- **Scalable processing:** Handles up to 10,000 question pairs from the input dataset
- **Comprehensive output:** Generates detailed CSV files with all intermediate calculations and final similarity scores
- **Matrix operations:** Advanced linear algebra operations for Markov chain similarity calculations using matrix flattening and trace operations
- **Flexible text processing:** Robust preprocessing pipeline with special character removal and case normalization

## Notes
This repo is under construction, but it's almost done. Don't expect weekly changes. This could be dead in 2 weeks or so

![](https://media.tenor.com/80HFRoLbNWcAAAAM/shrugging-shoulders-shrug-shoulders.gif)
