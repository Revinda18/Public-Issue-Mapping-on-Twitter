# Public Issue Mapping on Twitter using LDA

This project was developed as a final assignment for the **Natural Language Processing (NLP)** course. It focuses on extracting and visualizing key public issues from Twitter data using **Latent Dirichlet Allocation (LDA)** topic modeling.

## Objective
To map and understand dominant public concerns discussed on Twitter by applying topic modeling techniques.

## Dataset
- Source: Twitter API / pre-scraped dataset
- Language: Bahasa Indonesia
- Format: CSV (`dataset_kemenkeu_indo.csv`)
- Contains: Tweet text, timestamp, user metadata (if applicable)
  
## Tools & Libraries
- Python (Google Colab)
- `pandas`, `numpy`  
- `nltk`, `re` (for preprocessing)  
- `gensim` (LDA modeling)  
- `pyLDAvis` (topic visualization)  
- `matplotlib`, `wordcloud`
  
## Text Preprocessing
- Case folding  
- Tokenization  
- Stopword removal  
- Punctuation & symbol cleaning  
- Filtering short/non-informative tokens

## Topic Modeling (LDA)
- Model: Gensim’s LDA  
- Number of topics: *e.g.,* 5  
- Evaluation: Perplexity & Coherence Score  
- Visualized with WordCloud and pyLDAvis

## Results
- Identified main public topics from the dataset  
- Topics represented with top keywords per cluster  
- Clear topic distribution and keyword mapping
  
## Files
- `TugasBesar_NLP.ipynb` – Main code (Colab notebook)  
- `DATASET/dataset_kemenkeu_indo.csv` – Dataset  
- `README.md` – Project documentation

## Acknowledgments
This project was created by a group of NLP course students as part of a university assignment.  
Open to feedback, collaboration, or suggestions.

