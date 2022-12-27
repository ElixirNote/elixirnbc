# ElixirNBC

[![Google Group](https://img.shields.io/badge/-Google%20Group-lightgrey.svg)](https://groups.google.com/forum/#!forum/jupyter)
[![Build Status](https://travis-ci.org/jupyter/nbconvert.svg?branch=main)](https://travis-ci.org/jupyter/nbconvert)
[![Documentation Status](https://readthedocs.org/projects/nbconvert/badge/?version=latest)](https://nbconvert.readthedocs.io/en/latest/?badge=latest)
[![Documentation Status](https://readthedocs.org/projects/nbconvert/badge/?version=stable)](https://nbconvert.readthedocs.io/en/stable/?badge=stable)
[![codecov.io](https://codecov.io/github/jupyter/nbconvert/coverage.svg?branch=main)](https://codecov.io/github/jupyter/nbconvert?branch=main)

The **nbconvert** tool, `elixir nbconvert`, converts notebooks to various other
formats via Jinja templates. The nbconvert tool allows you to convert an
`.ipynb` notebook file into various static formats including:

- HTML
- LaTeX
- PDF
- Reveal JS
- Markdown (md)
- ReStructured Text (rst)
- executable script

## Usage

From the command line, use nbconvert to convert a Jupyter notebook (_input_) to a
a different format (_output_). The basic command structure is:

    $ elixir-nbconvert --to <output format> <input notebook>

where `<output format>` is the desired output format and `<input notebook>` is the
filename of the Jupyter notebook.

Convert notebook file, `sample.ipynb`, to HTML using:

    $ elixir-nbconvert --to html sample.ipynb

This command creates an HTML output file named `mynotebook.html`.

## Dev Install

Check if pandoc is installed (`pandoc --version`); if needed, install:

```
sudo apt-get install pandoc
```

Or

```
brew install pandoc
```

Install elixirnbc for development using:

```
git clone git@github.com:ElixirNote/elixirnbc.git
cd elixirnbc
pip install -e .
```

## Documentation

- [Documentation for Elixir Nbc](https://ciusji.gitbook.io/elixirnote/guides/elixirnote-nbc)
- [Examples of Elixir Nbc](https://ciusji.gitbook.io/elixirnote/guides/elixirnote-nbc)

## Technical Support

- [Issues and Bug Reports](https://github.com/ElixirNote/elixirnbc/issues): A place to report
  bugs or regressions found for nbconvert
- [Community Technical Support and Discussion](https://github.com/orgs/ElixirNote/discussions): A place for
  installation, configuration, and troubleshooting assistannce by the Elixir community.
  As a non-profit project and maintainers who are primarily volunteers, we encourage you
  to ask questions and share your knowledge on Discourse.

