# Overview
**Created:** June 16 - 19, 2026  
**Updated:** July 13 - 14, 2026 (created streaamlit app)  
Dataset from [AsadMahmood (Kaggle)](https://www.kaggle.com/datasets/asad1m9a9h6mood/news-articles)

# About the Program
This repository contains extractive article summarizers using NLP techniques like `Frequency-based scoring`, `TF-IDF (Term Frequency - Inverse Document Frequency)`, and `Text Ranking (TF-IDF + Cosine Similarities)`. Extrative means that the program will get the top n "important" sentences and output it as your summary. This repository has two parts, an ipynb file that explains each method and a python file that implements the summarizer on the web server Streamlit.

# How to Install the Notebook
1. Install [Python](https://www.python.org/downloads/)
2. Download the files and store it in any folder on your desktop (make sure all the files are in the same folder)
3. In command prompt (cmd) run `pip install -r requirements.txt` to install the libraries necessary
4. Open [Jupyter Notebook](https://jupyter.org/install) or any related environments (make sure you are using a ipynb format not py)
5. Run the program

# Deployed Version
This [link](https://article-summarizer-akane.streamlit.app/) will lead you to the website version wherein you enter your own article. You can customize it by selecting the amount of sentences you want each method to output.

PS: The code was aided with Anthropic's Claude
