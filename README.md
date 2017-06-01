# Machine Learning A-Z
Practical examples from [Machine Learning A-Z](https://www.udemy.com/machinelearning) rewriten using Jupyter Notebooks. Why? Because I personnaly don't like Anaconda fat pack and Spider IDE `( ╯°□°)╯ ┻━━┻`.

**NOTE This source code does not affilated by [SuperDataScience Team](http://superdatascience.com/) (original course authors)**

## Setup environment (macOS, pyenv)

I use `macOS` as a host system and `pyenv` to install `Python`. I recommend to use the latest `Python 3.x`. There is a trick to make `matplotlib` works properly: you have to [install `Python` as a framework for `macOS`](https://matplotlib.org/faq/osx_framework.html). I also suggest you to install all libs globally (without virtualenv) to do not repeat all this tricks again for each virtual environments.

```bash
# Install pyenv using Homebrew
brew install pyenv
# Install python 3 as a framework
PYTHON_CONFIGURE_OPTS="--enable-framework" pyenv install 3.6.1
# I always use latest python as global, but you can use it as local
pyenv global 3.6.1
# Ensure you the version, restart your shell otherwise
python --version
# Install all you need for Machine Learning course
pip install jupyter numpy pandas matplotlib sklearn statsmodels
```
