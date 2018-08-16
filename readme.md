
# A Notebook is a Hypothesis

---

## An interactive computing performance from [deathbeds](https://github.com/deathbeds/importnb)

---

1. ### [The impacts of physical and computational notebooks on science.](0_notebooks.ipynb)
2. ### [The lifecycle of hypothesis testing & interactive computing in Jupyter notebooks.](1_interactive.ipynb)
3. ### [Preserving computational essays for reuse.](2_testing.ipynb)

 ---

# Takeaways

* ### [Computational essays take parts from literacy and programming to tell data driven stories.](http://blog.stephenwolfram.com/2017/11/what-is-a-computational-essay/).
* ### Best practices for maturing notebooks into computational essays.
* ### Formal software testing practices to extend the __sell by date__ of a notebook.
* ### All of the artifacts of this presentation and to explore later.

---

# Links to this presentation.

[github](https://github.com/deathbeds/importnb/blob/master/readme.ipynb) | [nbviewer](http://nbviewer.jupyter.org/github/deathbeds/wtf/blob/master/readme.ipynb)

Code along with binder.

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/deathbeds/wtf/master?filepath=readme.ipynb)


---

## Resources for new notebook users.

* ### [Jupyter/IPython Notebook Quick Start Guide](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/)
* ### [Try Jupyterlab](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/18a9793b58ba86660b5ab964e1aeaf7324d667c8?urlpath=lab%2Ftree%2Fdemo%2FLorenz.ipynb)
* ### [A gallery of interesting Jupyter Notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)

## Useful packages for advanced notebooks users

* ### [importnb](https://github.com/deathbeds/importnb/tree/master/src/importnb)
* ### [doctest](https://docs.python.org/3/library/doctest.html)
* ### [pytest](https://docs.pytest.org/en/latest/customize.html)
* ### [mybinder](https://mybinder.org/)
* ### [nbviewer](http://nbviewer.jupyter.org/)
* ### [nbconvert](https://github.com/jupyter/nbconvert/tree/master/nbconvert/exporters)
* ### [jupyterlab](https://github.com/jupyterlab/jupyterlab/issues/2369)
* ### [graphviz](http://graphviz.readthedocs.io/en/stable/manual.html) _for diagrams._

## Resources for advanced users

* ### [Integrating IPython/Jupyter with your objects](http://ipython.readthedocs.io/en/stable/config/integrating.html)
* ### Learn deep learning in [fast.ai](http://www.fast.ai/) notebooks.

# Deathbeds

Deathbeds is open source coding collective experimenting with interactive computing and modern science.

* ### [Jyve](https://deathbeds.github.io/jyve/lab/)

    Jupyterlab if pure javascript.
    
* ### [importnb](https://github.com/deathbeds/importnb/tree/master/src/importnb)

    Use notebooks like real modules.

* ### [poser](https://github.com/deathbeds/poser)

    A fluent API for python.


```python
    if __name__ == '__main__':
        !jupyter nbconvert --to markdown readme.ipynb
```


```python
    if __name__ == '__main__':
        import pytest
        pytest.main([])
```

    ============================ test session starts =============================
    platform darwin -- Python 3.6.3, pytest-3.5.0, py-1.5.3, pluggy-0.6.0
    benchmark: 3.1.1 (defaults: timer=time.perf_counter disable_gc=False min_rounds=5 min_time=0.000005 max_time=1.0 calibration_precision=10 warmup=False warmup_iterations=100000)
    rootdir: /Users/tonyfast/_what_is_a_hypothesis, inifile:
    plugins: cov-2.5.1, benchmark-3.1.1, hypothesis-3.56.5, importnb-0.3.1
    
