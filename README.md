#LLINTERN
**POS Tagging and Text Summarization Using HMM and NLP**
**Overview**
        This project implements a Part-of-Speech (POS) tagger using the Hidden Markov Model (HMM) and performs text             summarization. The POS tagging is achieved using the Brown Corpus and NLTK's HiddenMarkovModelTrainer, while text           summarization utilizes SpaCy and Hugging Face's Transformers library.

**Table of Contents**
> POS Tagging with HMM
> Text Summarization
> Installation
> Usage
> License
> Contact

**POS Tagging with HMM:**

**Libraries and Dataset**: Utilizes NLTK for data handling and HMM training.
**Training and Testing Split**: Splits the Brown Corpus into training and testing sets.
**HMM Training**: Trains a Hidden Markov Model for POS tagging.
**Model Evaluation**: Evaluates the trained model's accuracy.

**Text Summarization:**

**Preprocessing**: Uses SpaCy for text tokenization and preprocessing.
**Word Frequency Calculation**: Determines word frequencies for scoring sentences.
**Sentence Scoring and Extraction**: Scores and extracts key sentences for summarization.
**Transformers**: Uses Hugging Face's t5-base model for advanced summarization.

**Installation**
**Clone the repository:**
**sh**
git clone https://github.com/Gayathri-Patibandla/LLINTERN.git
cd LLINTERN

**Usage**
**POS Tagging**: Run the script pos_tagging.py to train and evaluate the HMM POS tagger.
**Text Summarization**: Run the script text_summarization.py to summarize text using SpaCy and Transformers.

**License**
This project is licensed under the MIT License.
