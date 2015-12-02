# A Study of the TextRank Algorithm in Python

[TextRank](http://web.eecs.umich.edu/~mihalcea/papers/mihalcea.emnlp04.pdf) is
a key phrase and sentence extraction algorithm based on
[PageRank](http://ilpubs.stanford.edu:8090/422/1/1999-66.pdf). I've made an
IPython notebook to demonstrate how to implement the key phrase extraction
part of it using the [networkx](https://networkx.github.io/) and
[NLTK](http://www.nltk.org/) packages. I also use
[matplotlib](http://matplotlib.org/) to visualize the graph.


## Lightning Talk Slides

The slides of my lightning talk on the same subject can be found
[here](https://docs.google.com/presentation/d/1i6yVctis-8qWYfAgWgUR4Nw3RPAU7IJYJBICuv-wf6A/edit#slide=id.p).


## Just Reading? No Installation Required

GitHub now renders IPython notebooks, and so you don't have to install
anything to view it. Simply click on the notebook file or use
[this link](https://github.com/lukhnos/textrank-study-python/blob/master/Key%20Phrase%20Extraction%20with%20Python.ipynb).


## How to Use the Notebook on Your Machine

It's strongly recommended that you create a
[virtualenv](https://virtualenv.pypa.io/en/latest/) for experimentation, but
in short, you need to install the following packages with `pip`:

    pip install ipython[notebook] nltk networkx matplotlib

Then open the notebook:

    ipython notebook "Key Phrase Extraction with Python.ipynb"

The notebook has been tested with both Python 2.7.9 and Python 3.4.3 on OS X
10.10 and 10.11, but there shouldn't be issues if you run this on a different
operating system.
