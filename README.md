# Xtensor-polyglot

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/QuantStack/xtensor-polyglot/master?filepath=polyglot.ipynb)

An interactive demonstration of the xtensor language bindings.

## Usage

To launch the demo, simply click on the binder badge in the header or on the link below.

[![Binder](https://mybinder.org/static/logo.svg)](https://mybinder.org/v2/gh/QuantStack/xtensor-polyglot/master?filepath=polyglot.ipynb)

## Background

[xtensor](https://github.com/QuantStack/xtensor/) is a C++ library meant for numerical analysis with multi-dimensional array expressions. The xtensor framework includes several components which can be used to operate on the data structures of the main languages of data sciences, [xtensor-python](https://github.com/QuantStack/xtensor-python/) for Python and NumPy, [xtensor-julia](https://github.com/QuantStack/xtensor-julia/) for Julia, and [xtensor-r](https://github.com/QuantStack/xtensor-r/) for the R programming language.

In the example notebook, we write a simple numerical function in pure C++, which is first tested in the [xeus-cling](https://github.com/QuantStack/xeus-cling) Jupyter kernel. We then expose the function to Python, R, and Julia using the xtensor language bindings.

The example notebook is powered by the [allthekernels](https://github.com/minrk/allthekernels) project, a multiplexer Jupyter kernel which can be used to switch between all the kernels installed in a Jupyter environment.

## License

We use a shared copyright model that enables all contributors to maintain the
copyright on their contributions.

This software is licensed under the BSD-3-Clause license. See the
[LICENSE](LICENSE) file for details.
