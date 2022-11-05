To run the experiments we used for the LSTM-based models:
0. The .ipynb files are optimized to be run on Google Colab.
1. Download the MAMS-ATSA data and sentiment_dict.json from https://github.com/siat-nlp/MAMS-for-ABSA under data/ folder.
2. Download the glove.42B.300d.txt from https://nlp.stanford.edu/projects/glove/.
3. Place the three (MAMS-ATSA folder, sentiment\_dict.json, and glove.42B.300d.txt) downloaded data under the same folder as the .ipynb files.
4. If this is the first time running the notebook, uncomment this line:
# process_data()
under the Pipeline section.
5. Run all.
