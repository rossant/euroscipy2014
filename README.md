EuroSciPy 2014 IPython Advanced Tutorial
========================================

Introducing the interactive features of the IPython Notebook 2.0.


## Requirements

Simpler option is to install [Anaconda](https://store.continuum.io/cshop/anaconda/).

* Python 2.7 or Python 3.3+
* IPython 2.0+
* NumPy
* matplotlib
* scikit-learn (part 2)
* mpld3 (part 3, `pip install mpld3`)
* networkX (part 3, `pip install networkx`)
* a recent browser:
    * Chrome >= 13
    * Safari >= 5
    * Firefox >= 6


## Installation

```
git clone https://github.com/rossant/euroscipy2014.git
cd euroscipy2014
ipython notebook --profile=euroscipy2014
```


## Contents

In this tutorial, we will illustrate different features and APIs for creating interactive widgets and visualizations in the IPython notebook.

> Some of the code examples come from the [IPython Cookbook](http://ipython-books.github.io), Packt Publishing, featuring high-performance interactive computing methods for data science and mathematical modeling.


1. [**Calling your Python functions with graphical controls**](http://nbviewer.ipython.org/github/rossant/euroscipy2014/blob/master/01_interact.ipynb).
    * Using the `@interact` decorator.
    * Controlling matplotlib figures with widgets.
2. [**Interactive data visualization in the notebook**](http://nbviewer.ipython.org/github/rossant/euroscipy2014/blob/master/02_gui.ipynb).
    * Making matplotlib figures interactive in the notebook.
    * A crash course on d3.js.
    * Showing a networkX graph with d3.js.
3. [**Creating a GUI in the notebook**](http://nbviewer.ipython.org/github/rossant/euroscipy2014/blob/master/03_dataviz.ipynb).
    * Creating widgets.
    * Positioning widgets.
    * Styling widgets.
4. [**Creating a custom notebook widget with backbone.js**](http://nbviewer.ipython.org/github/rossant/euroscipy2014/blob/master/04_custom.ipynb).


## Further reading

* [Documentation of the IPython widgets](http://nbviewer.ipython.org/github/ipython/ipython/blob/master/examples/Interactive%20Widgets/Index.ipynb)
* [IPython in depth](http://nbviewer.ipython.org/github/ipython/ipython-in-depth/tree/master/examples/Interactive%20Widgets/)
* [IPython Cookbook](http://ipython-books.github.io)

