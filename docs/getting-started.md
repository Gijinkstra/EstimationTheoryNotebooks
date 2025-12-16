## Getting started with Python and VS Code

[*Home*](../README.md)

This is a step-by-step guide to install everything you need and start using these Python notebooks.

## 1. The super-easy way

You can run these Python notebooks on Google Colab — all you need is a Google account. Just go to [colab.research.google.com/](https://colab.research.google.com/) and upload a Python notebook, and you're ready to go.

On Google Colab several standard libraries like `numpy` and `matplotlib` are pre-installed. Other libraries like `vegas` need to be installed. You can do this by running:
```bash
!pip install vegas==6.3
```
Note the `!` at the beginning of the line. This means that this is to be executed in the terminal (it's not a Python command).


## 2. Run the notebooks locally

You can run these Python notebooks locally.
Firstly, you will need an IDE. Here are some guidelines to help you install 
and set up **VS Code**, which is a free and open-source IDE, but feel free 
to use your own favourite IDE if you are an experienced user.

### 2.1. Installation of VS Code

You can easily download and install VS Code on [Windows](https://code.visualstudio.com/docs/setup/windows),
[Linux](https://code.visualstudio.com/docs/setup/linux) (you'll get a `deb` file),
or [mac OS](https://code.visualstudio.com/docs/setup/mac). 

### 2.2. Installation of Python

On macOS and Linux you should have Python3 pre-installed.
I have run and tested all Python notebooks with Python 3.13.

You also need to install the Python extension in VS Code if it's not already installed.


### 2.3. Virtual environment

You need to install and setup a virtual environment (you only need to do this once).

