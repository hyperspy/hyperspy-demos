# HyperSpy demos

[![Live demos (Binder)](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/hyperspy/hyperspy-demos/master)
[![Notebook Viewer (nbviewer)](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg?sanitize=true)](http://nbviewer.ipython.org/github/hyperspy/hyperspy-demos/tree/master/)
[![Documentation Status](https://readthedocs.org/projects/hyperspy/badge/?version=stable)](http://hyperspy.readthedocs.io/en/stable/?badge=stable)

## Introduction

This repository contains [Jupyter Notebooks](http://jupyter.org/) to demo and learn
how to process multi-dimensional data with [HyperSpy](http://hyperspy.org). For
learning purposes we recommend to use them alongside the [HyperSpy User
Guide](http://hyperspy.org/hyperspy-doc/current/index.html).

The root folder contains notebooks concerning general HyperSpy features while
the subfolders contains notebooks for specific signals.

## Visualising and running the demos.

### Running and visualizing the demos online

[![Live demos (Binder)](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/hyperspy/hyperspy-demos/master)

Follow [this link](https://mybinder.org/v2/gh/hyperspy/hyperspy-demos/master)
or click the binder bash above
to run the the demos on [mybinder.org](https://mybinder.org/). 
The demos will run remotely, and one can experiment with HyperSpy in a
Jupyter notebook with no need to install or configure any software locally.

**Note:** depending on the server load, binder may take up to several minutes
to load the demos. For a quicker static visualization see below.

### Visualize the demos statically online

[![Notebook Viewer (nbviewer)](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg?sanitize=true)](http://nbviewer.ipython.org/github/hyperspy/hyperspy-demos/tree/master/)

Follow [this link](http://nbviewer.ipython.org/github/hyperspy/hyperspy-demos/tree/master/) or click on the nbviewer banner above
to display the demos with the [Jupyter Notebook viewer](http://nbviewer.ipython.org). The
[nbviewer](http://nbviewer.jupyter.org/) also permits downloading the notebooks
locally.

### Running and visualizing the demos locally

To run the demo notebooks locally, 
clone or download the [demos repository to your local
machine](https://github.com/hyperspy/hyperspy-demos), install HyperSpy and
[Jupyter Lab](http://jupyterlab.readthedocs.io/en/latest/) or [Jupyter
Notebook](https://jupyter-notebook.readthedocs.io/en/stable/) and use any of
the latter to run the notebooks.


#### (For developers) Testing the demos locally

To test the demos install
[nbval](http://github.com/computationalmodelling/nbval) and
[py.test](https://pytest.org/) and run

```bash
$ py.test
```

To help visualize differences/errors, install
[nbdime](http://github.com/jupyter/nbdime) as well, and run the test with

```bash
$ py.test --nbdime
```

## Contributing

To contribute new demos or improvements to the current ones fork the demos
repository and send us a pull request. See the [HyperSpy Developer Guide](http://hyperspy.org/hyperspy-doc/current/dev_guide.html) for more details on how to contribute to HyperSpy.

For issues and discussions fill a new
issue in [the demos github repository](https://github.com/hyperspy/hyperspy-demos)
or discuss it in [HyperSpy's gitter chat](https://gitter.im/hyperspy/hyperspy).



