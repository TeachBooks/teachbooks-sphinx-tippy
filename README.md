# TeachBooks Sphinx extension: Rich hover over tips

Rich tool tips in your TeachBook!

## Introduction

Sphinx-tippy allows you to create rich hover over tips as demonstrated here: https://sphinx-tippy.readthedocs.io/en/latest/. This TeachBooks Tippy extension makes it plug-and-play within a TeachBook.

The differences with Sphinx-tippy are:

- Default inclusion of useful CSS-file.
- Default activation of sphinx.ext.mathjax.
- Default loading method of _defer_ changed to _None_ for supporting JavaScript.
- Default support for [TeachBooks Sphinx Grasple](https://github.com/TeachBooks/Sphinx-Grasple-public) such that images are shown (as iframes are not loaded).
- Limit the showing of tool tips to the `<main>` anchor of the Sphinx book.
- Limit the maximum height of a tool tip.
- Force tool tips to remain with visible document body.
- No arrow that points from the tool tip to the link.

## What does it do?

You can see how the this works in the [example book](https://teachbooks.io/TeachBooks-sphinx-tippy-Example).

## Installation
To install TeachBooks-Sphinx-Tippy, follow these steps:

**Step 1: Install the Package**

Install the `teachbooks-sphinx-tippy` package using `pip`:
```
pip install teachbooks-sphinx-tippy
```

**Step 2: Add to `requirements.txt`**

Make sure that the package is included in your project's `requirements.txt` to track the dependency:
```
teachbooks-sphinx-tippy
```

**Step 3: Enable in `_config.yml`**

In your `_config.yml` file, add the extension to the list of Sphinx extra extensions (**important**: underscore, not dash this time):
```
sphinx: 
    extra_extensions:
        - teachbooks_sphinx_tippy
```

## Usage

By following the steps above, the extension will be added automatically.

## Contribute
This tool's repository is stored on [GitHub](https://github.com/TeachBooks/teachbooks-sphinx-tippy). The `README.md` of the branch `Manual` is also part of the [TeachBooks manual](https://teachbooks.io/manual/intro.html) as a submodule. If you'd like to contribute, you can create a fork and open a pull request on the [GitHub repository](https://github.com/TeachBooks/teachbooks-sphinx-tippy). To update the `README.md` shown in the TeachBooks manual, create a fork and open a merge request for the [GitHub repository of the manual](https://github.com/TeachBooks/manual). If you intent to clone the manual including its submodules, clone using: `git clone --recurse-submodulesgit@github.com:TeachBooks/manual.git`.
