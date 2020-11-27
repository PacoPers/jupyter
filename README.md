# Jupyter and JupyterLab

- [Credit and license](https://coderefinery.github.io/jupyter/license/)

## Local development

The following Gemfile will permit you to run jekyll locally

```
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
gem 'github-linguist'
gem 'rouge', '~>1.11.1'
```

Write it as Gemfile under the repository root.

```
$ export GEM_HOME=$HOME/.gem
$ export PATH=$PATH:$HOME/.gem/bin
$ bundler install
$ bundle exec jekyll serve
```

# Link to jupyter:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PacoPers/jupyter/HEAD)

Link Qlunc Jupyter notbook:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PacoPers/jupyter/master?filepath=jupyter_tests%2Ffirst.ipynb)
