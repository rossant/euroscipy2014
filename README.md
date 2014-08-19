EuroSciPy 2014 IPython Advanced Tutorial
========================================

Introducing the interactive features of the IPython Notebook 2.0.


## Requirements

* Python 2.7 or Python 3.3+
* IPython 2.0+
* NumPy
* matplotlib
* for part 2:
    * mpld3 (`pip install mpld3`)
    * networkX (`pip install networkx`)
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


1. Calling your Python functions with graphical controls.
    * Using the `@interact` decorator.
2. Interactive data visualization in the notebook.
    * Making matplotlib figures interactive in the notebook with mpld3.
    * Creating an interactive visualization of a networkX graph with d3.js.
3. Creating a GUI in the notebook.
    * Creating widgets.
    * Positioning widgets.
    * Styling widgets.
4. Creating a custom notebook widget with backbone.js.


## Further reading

* [Documentation of the IPython widgets](http://nbviewer.ipython.org/github/ipython/ipython/blob/master/examples/Interactive%20Widgets/Index.ipynb)
* [IPython in depth](http://nbviewer.ipython.org/github/ipython/ipython-in-depth/tree/master/examples/Interactive%20Widgets/)
* [IPython Cookbook](http://ipython-books.github.io)



