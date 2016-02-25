# Mathematical Modelling I<br/>_Tools for mathematical modelling_

This course will have three themes, described below. Exercised from each theme will weight 1/3 in the total final grade.

## Dates

31/Mar: Drafts for exercises Theme 1<br/>
15/Apr: Exercises Theme 1<br/>
15/May: Drafts for exercises Theme 2<br/>
31/May: Exercises Theme 2<br/>
30/Jun: Drafts for exercises Theme 3<br/>
15/Jun: Exercises Theme 3<br/>

_failure to deliver drafts will incur in a 50% penalty in the theme grade_

## 1. Visualization
**1.1 Introduction to Jupyter Notebooks**
<small>[Learn Python](http://www.learnpython.org/) - [Wakari Notebooks Gallery](https://www.wakari.io/gallery) - [Numpy Quickstart](https://docs.scipy.org/doc/numpy-dev/user/quickstart.html) - [Pandas Cookbook](https://github.com/jvns/pandas-cookbook)</small>

**1.2 Libraries: Matplotlib, Bokeh, Plotly**
<small>[Matplotlib Gallery](http://matplotlib.org/gallery.html) - [Bokeh notebooks Gallery](https://github.com/bokeh/bokeh-notebooks) - [Plotly notebooks Gallery](https://plot.ly/python/)</small>

**1.3 Interactivity**: <small>[Bokeh Widgets](http://bokeh.pydata.org/en/0.10.0/docs/user_guide/interaction.html)</small>

**1.4 Big Data Visualization**
<small>[Big Data plotting problems](https://anaconda.org/jbednar/plotting_problems/notebook) - [Plotting NYC taxi data](https://anaconda.org/jbednar/nyc_taxi/notebook) - [Datashader](https://github.com/bokeh/datashader)</small>

**EXERCISE 1.A**: _Tell a story_ through data visualization in **one** notebook. The story must use:

- Pandas and Numpy for data loading and cleaning (see [Pandas Cookbook - Chapter 7](http://nbviewer.jupyter.org/github/jvns/pandas-cookbook/blob/master/cookbook/Chapter%207%20-%20Cleaning%20up%20messy%20data.ipynb))
- Matplotlib and Plotly for creating several views on the same data (contours and scatters), sub-sampling data, show data interpolations
- Bokeh for Interactive multi-selection in subplots and interactive widgets

**EXERCISE 1.B**: Use datashader to build a meaningful visualization of at least 1 million data points

**EXERCISE 1.C**: Select time series data and build a data streaming example, using Bokeh or Plot.ly

**SOME DATASOURCES**: https://data.cityofboston.gov/ https://data.nasa.gov/ https://data.cityofchicago.org/ http://transtats.bts.gov/ http://catalog.data.gov/ http://www.kaggle.com

## 2. Computing for mathematical modelling
**2.1 Solving ODEs** [SciPy](http://www.scipy.org)

**2.2 Symbolic Computing** [SymPy] (http://www.sympy.org/) - [SAGE](http://www.sagemath.org)

**2.3 Animating mathematical models** [Matplotlib animations](http://matplotlib.org/1.5.1/examples/animation/index.html)

**EXERCISE 2.A**: Choose a problem solvable with ODEs:
  - Define, solve and visualize a mathematical model

**EXERCISE 2.B**: Use matplotlib animations to:
  - Create two animations illustrating key aspects of your model.

**EXERCISE 2.C**: Disseminate your work:
   - Create a presentation from your notebook in 2.A)
   - Use Git and nbviewer for publishing and sharing notebooks online.



## 3. Scaling computing
**3.1 Vectorizing functions** [NumPy ufuncs](http://docs.scipy.org/doc/numpy-1.10.0/reference/ufuncs.html)

**3.2 IPython parallelization** [IPython parallel](https://ipython.org/ipython-doc/3/parallel/)

**3.3 Python fast like C** [Numba](http://numba.pydata.org/) [Cython](http://cython.org/)

**3.4 Theano: Fast symbolic computing** [Theano](http://deeplearning.net/software/theano/)

**EXERCISE 3.A**: Parallelize an algorithm through vectorization (Numpy or Numba)
  - measure its scalability with increasing cores and data

**EXERCISE 3.B**: Parallelize an algorithm with iPython parallel
  - measure its scalability with increasing cores and data
  
**EXERCISE 3.C**: Use Theano to solve an optimization problem through gradient descent
  - measure its performance in CPU + GPU