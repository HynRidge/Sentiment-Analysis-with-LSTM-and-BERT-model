To run the experiments we used for the LSTM-based models:
0. The .ipynb files are optimized to be run on Google Colab.
1. Download the MAMS-ATSA data from https://github.com/siat-nlp/MAMS-for-ABSA under data/ folder, or the MAMS-ATSA folder in this repo.
2. Download the glove.42B.300d.txt from https://nlp.stanford.edu/projects/glove/.
3. Place the two file (MAMS-ATSA folder and glove.42B.300d.txt) and .ipynb files downloaded data under a folder named CS4248 in your Google Drive (the path should be drive/MyDrive/CS4248/). Otherwise, you need to change the path under the config dictionary.
4. If this is the first time running the notebook, uncomment this line: <br>
\# process_data() <br>
under the Pipeline section.
5. Run all.

To run BERT.ipynb:
0. The .ipynb files are optimized to be run on Google Colab.
1. Download the MAMS-ATSA data from https://github.com/siat-nlp/MAMS-for-ABSA under data/ folder, or the MAMS-ATSA folder in this repo.
2. Place the MAMS-ATSA folder and BERT.ipynb downloaded data under a folder named CS4248 in your Google Drive (the path should be drive/MyDrive/CS4248/). Otherwise, you need to change the path under the config dictionary.
3. Run all.
