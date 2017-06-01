# Machine Learning A-Z
Practical examples from [Machine Learning A-Z](https://www.udemy.com/machinelearning) rewriten using Jupyter Notebooks.

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

Alternatively you could install python using Homebrew `brew install python3` and install all libraries `pip3 install jupyter numpy pandas matplotlib sklearn statsmodels`. 

## Run examples

Get source code and run `Jupyter Notebook`

```bash
# Clone repo to get a working copy
git clone git@github.com:satyrius/machine-learning-az.git
# Change directory
cd machine-learning-az
# Run Notebook
jupyter-notebook
```

## FAQ

### Q: Why this course?

A: This is the best ML course I ever seen. Authors did a great job, they make complex things simple by giving a no-bulshit explanation and giving a lot of real-life practical examples.

### Q: Why Jupyter Notebooks?
A: Because I personnaly don't like Anaconda fat pack and Spider IDE `( ╯°□°)╯ ┻━━┻`.
