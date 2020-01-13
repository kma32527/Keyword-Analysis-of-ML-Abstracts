# Recommender System for Academic Literature
This is an ongoing experiment in using text mining on academic literature. The eventual goal is to develop a tool for efficiently exploring academic literature and idetifying interdisciplinary research connections. I believe this has potential to identify subtle trends free of acaademic bias that would otherwise go unnoticed.

Academia is particularly well-suited to text analysis since

1) Texts tend to be formatted and spell-checked

2) Academic papers tend to follow a predictable structure

3) Terminology is mostly standardized (within disciplines)

4) There are many, many more research papers than any individual or group can parse through


# Current plan
- Find a way to assess the quality of the results, since doing so manually requires a high degree of domain specialization.

- Assess the generalizability to arbitrary research disciplines

- Test abstractive feature extraction methods

# Files

- plos_preprocess.py

  - Package to extract and clean PLOS .xml articles.

- keyword_model.py

  - Package to extract bag of words from text data.

- autoencoder.py

  - Script to test the use of an autoencoder for improving feature extraction

  - Can be interpreted as "studying the material through core concepts and keywords"

- arxiv_tests.py

  - Model tests on arxiv ML abstracts

- ploss_tests.py

  - Model tests on PLOSS articles from the category of computational biology
