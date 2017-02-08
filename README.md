# Pineapple
==============================

skeleton code for team pineapple

Add your code here (src directory). The dataset is going to have something to do with "social impact."
Jared mentioned some NLP possibilities, maybe time-series.

Here are some starter ideas:

**Statistical Inference/EDA:**
 - Quick visualization and EDA scripts.
 - Kernel Density Estimation
 - nonparametric permutation test
 - general hypothesis tests

**NLP:**
 - Text processing (remove stop words, NER, remove punctuation, stem/lemmatize, unicode)
 - Featurizing: bag of words, tfidf, word2vec, doc2vec
 - Comparing similarity: consine similarity, earth-movers distance, minkowski distance
 - Topic Modeling: LDA (fancy graphlab viz)
 - sentiment analysis

**Time Series:**
 - AR/MA linear regression
 - Forecasting: ETS, Holt-Winters Filtering
 - HMMs
 - MCMS: identify pivotal moments (tau) in time-series and get distribution parameters (Poisson, Gaussian)

**Dimensionality Reduction:**
- PCA
- TSNE
- Autoencoders

**ML Classification:**
 - XGboost
 - KFold cross-validation with error metrics
 - ROC curve, AUC
 - Confusion matrices
 - Unsupervised Clustering: Kmeans, Gaussian Mixture Models.

**Regression:**
 - linear model diagnostics
 - options for l1, l2 regularization. Glmnet/elasticnet

**Setup for Flask/Shiny app**






Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
