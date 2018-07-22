# Logic Tensor Networks (LTN) Tutorials

## Dependencies

The following is what we are using for development. Basically similar versions should run fine.

* python3.6
* tensorflow >=1.8
* numpy >= 1.13.3
* matplotlib >= 2.1

Installing dependencies is easy. Just use ``pip install tensorflow numpy matplotlib`` or use a virtualenv. If you want to run the notebooks you need a Jupyter installation.

## Repository structure

* ``logictensornetworks.py`` -- core system for defining constants, variables, predicates, functions and formulas.
* ``logictensornetworks_wrapper.py`` -- a simple wrapper that allows to express constants, variables, predicates, functions and formulas using strings.
* ``logictensornetworks_library.py`` -- a collection of useful functions.
* ``*.ipynb`` are jupyter notebooks


## Tutorials

* [grounding](https://nbviewer.jupyter.org/github/logictensornetworks/tutorials/blob/master/grounding.ipynb)
* [grounding and learning](https://nbviewer.jupyter.org/github/logictensornetworks/tutorials/blob/master/grounding_and_learning.ipynb)
* [regression linear](https://nbviewer.jupyter.org/github/logictensornetworks/tutorials/blob/master/regression_linear.ipynb)
* [binary classification](https://nbviewer.jupyter.org/github/logictensornetworks/tutorials/blob/master/binary_classification.ipynb)
* [multilabel classification](https://nbviewer.jupyter.org/github/logictensornetworks/tutorials/blob/master/multilabel_classification.ipynb)
* [multilabel classification axiomatized](https://nbviewer.jupyter.org/github/logictensornetworks/tutorials/blob/master/multilabel_classification_axiomatized.ipynb)
* [relations](https://nbviewer.jupyter.org/github/logictensornetworks/tutorials/blob/master/relations.ipynb)
* [smokes/friends/cancer](https://nbviewer.jupyter.org/github/logictensornetworks/tutorials/blob/master/smokes_friends_cancer.ipynb)

## Documentation

Checkout recent tutorials on Logic Tensor Networks (LTN)

* [IJCNN 2018 tutorial](https://sites.google.com/fbk.eu/ltn/tutorial-ijcnn-2018)
* [IJCAI 2018 tutorial](https://sites.google.com/fbk.eu/ltn/tutorial-ijcai-2018)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

LTN has been developed thanks to active contributions and discussions with the following people:
* Alessandro Daniele (FBK)
* Artur d’Avila Garces (City)
* Francesco Giannini (UniSiena)
* Giuseppe Marra (UniSiena)
* Ivan Donadello (FBK)
* Lucas Brukberger (UniOsnabruck)
* Luciano Serafini (FBK)
* Marco Gori (UniSiena)
* Michael Spranger (Sony CSL)
* Michelangelo Diligenti (UniSiena)
