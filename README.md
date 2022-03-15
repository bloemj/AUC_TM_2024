# Text Mining 2021/22
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bloemj/AUC_TMCI_2022/main)

Amsterdam University College -- Text Mining -- Winter/Spring 2022.

## Contents

You can use the [Hello World](notebooks/0_HelloWorld.ipynb) notebooks to check that everything is working.

| Week         | Topic           | Materials  |
| ------------- |-------------| -----:|
| 1      | Introduction and Python refresher | <a href='slides/AUC_1_Introduction.pdf'>slides</a> + notebooks <a href='notebooks/1_Fundamentals.ipynb'>1</a>, <a href='notebooks/1_MoreFundamentals.ipynb'>2</a>, <a href='notebooks/1_EvenMoreFundamentals.ipynb'>3</a>, <a href='notebooks/1_RegularExpressions.ipynb'>4</a>, <a href='notebooks/1_ScientificProgramming.ipynb'>5</a> |
| 2      | Introduction to NLP and NLP pipelines | <a href='slides/AUC_2_NLP_Foundations.pdf'>slides</a> + <a href='notebooks/2_NLP_pipelines.ipynb'>notebook</a> |
| 3      | Language modelling  | <a href='slides/AUC_3_language_models.pdf'>slides</a> + notebooks <a href='notebooks/3_Distributions_in_text.ipynb'>1</a>, <a href='notebooks/3_WordNet.ipynb'>2</a> |
| 4      | Vector space semantics | <a href='slides/AUC_4_vectorSpaceSemantics.pdf'>slides</a> + <a href='notebooks/4_Vector_Semantics.ipynb'>notebook</a> |
| 5      | Word embeddings | <a href='slides/AUC_5_Word_Embeddings.pdf'>slides</a> + <a href='notebooks/5_WordEmbeddings.ipynb'>notebook</a> |
| 6      | Machine learning fundamentals  | <a href=''>slides</a> + <a href='notebooks/6_ML.ipynb'>notebook</a> |
| 7      | Text classification  | <a href=''>slides</a> + <a href='notebooks/7_1_Classification.ipynb'>notebook (Scikit-learn)</a>, <a href='notebooks/7_2_PyTorch.ipynb'>notebook (PyTorch)</a> |
| 8      | RNNs and NER  | <a href=''>slides</a> + <a href='notebooks/8_1_NER.ipynb'>notebook</a> |
| 9      | Web scraping and APIs  | <a href='notebooks/9_WebScraping_APIs.ipynb'>notebook</a> |
| 10      | Recommender systems  | <a href=''>slides</a> + <a href='notebooks/10_Recommender_Systems.ipynb'>notebook</a> |
| 11      | Creating annotated corpora  | <a href=''>slides</a> |
| 12      | Sentiment analysis  | <a href=''>slides</a> + <a href='notebooks/11_Sentiment_Analysis.ipynb'>notebook</a> |
| 13      | Clustering and topic modelling  | <a href=''>slides</a> + <a href='notebooks/12_Clustering_TopicModelling.ipynb'>notebook</a> |
| 14      | XAI and Ethics  | Selected contents from [this course](https://github.com/Giovanni1085/UvA_AIforSociety_2022) |

### External materials

#### Neural networks

* [Introduction (Stanford's CS231N)](https://cs231n.github.io/neural-networks-1).
* [Optimization 1 (Stanford's CS231N)](https://cs231n.github.io/optimization-1/).
* [Yes you should understand backprop](https://medium.com/@karpathy/yes-you-should-understand-backprop-e2f06eab496b) by Andrej Karpathy.
* [Optimization 2 (Stanford's CS231N)](https://cs231n.github.io/optimization-2/).

#### Tutorials

* [SpaCy 101](https://spacy.io/usage/spacy-101).
* [scikit-learn tutorials](https://scikit-learn.org/stable/tutorial/index.html).
* [PyTorch 60m blitz](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html).
* [PyTorch text classification with torchtext](https://pytorch.org/tutorials/beginner/text_sentiment_ngrams_tutorial.html).

## Group projects

See the [projects folder](/projects) for info.

### Project outcomes


## Set-up

### Running in the cloud (Google Colab)

1. Fork the repository to your Github account: go to https://github.com/bloemj/AUC_TMCI_2022 and click Fork
2. Get updates (from time to time): In your fork on the Github website, click "Fetch upstream"
3. Launch notebooks by going to your Google Colab: https://colab.research.google.com/ and loading them using the "Open Notebook" window. Enter the GitHub URL of the fork of the course materials in your own GitHub account to be able to save your changes. Click "Open notebook in new tab" to run the notebook.
4. To save your changes, choose "Save a copy in GitHub" and accept the suggested location. Note that just using "Save" will not work, and changes will not automatically save. This will also not work if you did not perform step 1 and are loading my version of the repository directly.

### Running on your own system

1. Clone the repository locally: `git clone https://github.com/bloemj/AUC_TMCI_2022.git`
2. Get updates (from time to time): `git pull`
3. Create a conda environemnt: `conda create -n myenv python=3.7 anaconda` (where `myenv` is the envirnoment name)
4. Activate it: `conda activate myenv`
5. Install packages (see the `requirements.txt` file), e.g. `conda install pandas`
6. Launch a Jupyter notebook: `jupyter notebook`

* [More on conda enviroments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
* [Conda cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
* [Getting started with Jupyter notebooks](https://medium.com/codingthesmartway-com-blog/getting-started-with-jupyter-notebook-for-python-4e7082bd5d46)
* [On using git and GitHub for version control](https://alan-turing-institute.github.io/rsd-engineeringcourse/ch02git)

Alternatively, use [Binder](https://mybinder.org) (link above).

**A more detailed [guide to setup your environment](setup.md), with multiple options.**

## Credits

* Giovanni Colavizza, who ran the [previous-year edition](https://github.com/Giovanni1085/AUC_TMCI_2021) of this course.
* Michael Repplinger, who ran the 2018/19 edition and Gianluca Lebani, who ran the 2017/18 edition.
* Giovanni Colavizza and Matteo Romanello, Applied Data Analysis course for the Oxford Digitial Humanities Summer School [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3352830.svg)](https://doi.org/10.5281/zenodo.3352830)
* James Hetherington and Giovanni Colavizza, [Research Software Engineering with Python](https://alan-turing-institute.github.io/rsd-engineeringcourse/)

## License

Everything in this repository which is not already attributed to someone else is released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). 
