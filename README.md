**Project Overview**

This project involves implementing a custom Naive Bayes classifier from scratch to predict the domain (Archaea, Bacteria, Eukaryota, or Virus) of research papers based on their abstracts taken from the MEDLINE database. The objective is to achieve high predictive accuracy on a test set without class labels by enhancing the standard Naive Bayes algorithm.

**Implementation Details**

Text Representation: Explores various text representation techniques such as binary occurrence and term frequency to effectively handle textual data.

Standard Naive Bayes: Implements the foundational Naive Bayes algorithm as per the guidelines in Mitchell's "Machine Learning" textbook, focusing on conditional independence and likelihood computation.

Enhanced Model: Incorporates advanced text processing features like n-grams, feature selection based on correlation, and term weighting to improve the classifier's accuracy.

**Key Modifications**

Text Preprocessing: Includes techniques for concatenating biologically significant terms (e.g., 'homo-sapiens'), reducing redundancy, and emphasizing rare but informative terms.
Probabilistic Calculations: Utilizes log probabilities to avoid underflow issues associated with small probability values.

**Evaluation Strategy**

Validation Technique: Describes the use of cross-validation or a training/validation split to ensure robust model evaluation.

Performance Metrics: Discusses the accuracy improvements over the standard model and compares results using tables and descriptive analysis.
