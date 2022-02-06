# TXI Jupyter Lab

A JupyterLab instance that contains some learning resources for Python and related topics.

## Running locally

### With Docker

```
docker compose up
```

This will present you with a pair of URLs to get access to the Jupyter Lab. I've found that only the `127.0.0.1` version works for me.

### With VS Code

1. Ensure that you have the version of Python installed from the [.python-version](./.python-version) file
2. Open the desired notebook file in VS Code
3. When you first try to run a code block you will be prompted to install some things that VS Code needs to run the notebook

## What's in this lab?

Inside the work folder you will find:

* [Just Enough Python notebook](./work/just_enough_python.ipynb) - a notebook that came with the [Programming Machine Learning](https://pragprog.com/titles/pplearn/programming-machine-learning/) book from Pragramatic Programmers, which is a great way to learn about Python's language features.
* [Pandas Numpy notebook](./work/PandasNumpy.ipynb) - the notebook that Derek went through during the Engineering Meet-up on 7th Jan 2022.

## What next?

Take a look at the [Pythonistas](https://www.notion.so/tablexi/Pythonistas-4258142c9da441babdb3f7894ff5f4ce) page in Notion for more information including resources that can be used to learn Python and related topics.
