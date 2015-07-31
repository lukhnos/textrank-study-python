# A Study of the TextRank Algorithm in Python

[TextRank](http://web.eecs.umich.edu/~mihalcea/papers/mihalcea.emnlp04.pdf) is
a key phrase and sentence extraction algorithm based on
[PageRank](http://ilpubs.stanford.edu:8090/422/1/1999-66.pdf). I've made an
IPython notebook to demonstrate how to implement it using the
[networkx](https://networkx.github.io/) and
[NLTK](http://www.nltk.org/) packages. I also use
[matplotlib](http://matplotlib.org/) to visualize the graph.

## How to Use the Notebook

It's strongly recommended that you create a
[virtualenv](https://virtualenv.pypa.io/en/latest/) for experimentation, but
in short, you need to install the following packages with `pip`:

    pip install ipython[notebook] nltk networkx matplotlib

Then open the notebook:

    ipython notebook "Key Phrase Extraction with Python.ipynb"
