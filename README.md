# supervied_learning_MLDS2021

In this work we implement different supervised learning methods to classify data from two groups of datasets:
  ## - German Credit Risk: 
  a dataset that contains 1000 entries with 20 variables prepared by Prof. Hofmann. In this dataset, each entry represents a person who takes a credit by a bank. Each person is classified as good or bad credit risks according to the set of attributes.
  ## - Relational Datasets: 
  Three datasets of reaserch papers:
    - The CiteSeer dataset consists of 3327 scientific publications classified into one of six classes. The citation network consists of 4732 links. Each publication in the dataset is described by a 0/1-valued word vector indicating the absence/presence of the corresponding word from the dictionary. The dictionary consists of 3703 unique words.
    - The Cora dataset consists of 2708 scientific publications classified into one of seven classes. The citation network consists of 5429 links. Each publication in the dataset is described by a 0/1-valued word vector indicating the absence/presence of the corresponding word from the dictionary. The dictionary consists of 1433 unique words.
    - The Pubmed dataset consists of 19717 scientific publications from PubMed database pertaining to diabetes classified into one of three classes. The citation network consists of 44338 links. Each publication in the dataset is described by a TF/IDF weighted word vector from a dictionary which consists of 500 unique words.
   
The methods implemented in this work are: 
  - Linear Discriminant Analysis (LDA).
  - Classification And Regression Trees (CART).
  - Random Forest (RF).
  - Logistric Regression (LR).
  - K Nearest Neighbours (KNN).
  - Naive Bayes Classifier.


### German Credit Risk Notebook:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/ybenabed/supervied_learning_MLDS2021/blob/main/bank_client_classification.ipynb)

### Relational Datasets Notebook:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/ybenabed/supervied_learning_MLDS2021/blob/main/papers_classification.ipynb)
