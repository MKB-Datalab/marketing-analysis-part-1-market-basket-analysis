# :chart_with_upwards_trend: Marketing Analytics : Market Basket Analysis

![](https://github.com/dpbac/marketing_basket_analysis/blob/master/images/dave-goudreau-0uH7NLMaMtQ-unsplash_modified.jpg)
Photo by <a href="https://unsplash.com/@davegoudreau?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Dave Goudreau</a> on <a href="https://unsplash.com/s/photos/shopping-cart?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

This repository opens a series of tutorials introducing techniques that will help you making better data-driven marketing decisions.
We start by introducing **Market Basket Analysis (MBA)**; a powerful tool used for product promotion and recommendation.
We will discuss several techniques and show you their implementation such that you can employ them yourself.

Here we make use of Python tools. The main one is `mlxtend` package which is very useful for performing important tasks for Market Basket Analysis such as:

1. Pre-process data
2. Generate item sets and rules
3. Filter according to metrics

After completing this tutorial, you'll know:
What Market Basket Analysis is
- How to prepare your data to apply MBA
- Some metrics used in MBA
- How to perform MBA using the Apriori algorithm
- How to apply some simple visualizations used in MBA

The notebook [Introduction to Market Basket Analysis](https://github.com/dpbac/marketing_basket_analysis/blob/master/notebooks/Introduction%20to%20Market%20Basket%20Analysis.ipynb) provides an introduction to MBA through use cases.

## :file_folder: Data

In this tutorial we use two datasets.

1. An small fictional bakery dataset consisting of 298 transactions containing 7 unique items.

2. A transactional dataset which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered online retail. This one is available at the [UCI Machine Learning repository](http://archive.ics.uci.edu/ml/datasets/online+retail). Here we used a subset of the dataset containing only transactions of customers in The Netherlands.

Both datasets can be found [here](https://github.com/dpbac/marketing_basket_analysis/tree/master/data/raw).

If you are curious to know we obtained the dataset containing only products purchased in The Netherlands was obtained check this [notebook](https://github.com/dpbac/marketing_basket_analysis/blob/master/notebooks/UCI%20dataset.ipynb).


## :wrench: Tools

[mlxtend Python package](http://rasbt.github.io/mlxtend/) which contains useful tools for performing important tasks inherent to MBA.

In particular the following functions were used:

- Transaction encoder (from mlxtend.preprocessing import TransactionEncoder)

- Apriori algorithm (from mlxtend.frequent_patterns import apriori)

- Association rule (from mlxtend.frequent_patterns import association_rules)

    
## :computer: Install requirements
* Install requirements using `pip install -r time_series_requirements.txt`.
  * Make sure you use Python 3.
  * You may want to use a virtual environment for this.

-------------------------------------
[:arrow_backward: **Back to repository main page**](https://github.com/dpbac/test_mkb_knowledge_repo)
