
# A Notebook is a Hypothesis

---

## An interactive computing performance from [deathbeds](https://github.com/deathbeds/importnb)

---

1. ### [The impacts of physical and computational notebooks on science.](notebooks.ipynb)
2. ### [The lifecycle of hypothesis testing & interactive computing in Jupyter notebooks.](interactive.ipynb)
3. ### [Preserving computational essays for reuse.](testing.ipynb)

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
