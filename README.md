# Generative Deep Learning
### Teaching Machines to paint, write, compose and play

The official code repository for examples in the O'Reilly book 'Generative Deep Learning'

https://learning.oreilly.com/library/view/generative-deep-learning/9781492041931/

https://www.amazon.com/Generative-Deep-Learning-Teaching-Machines/dp/1492041947/ref=sr_1_1

## Tensorflow 2.0

This branch uses Keras within Tensorflow 2.0.

## Structure

This repository is structured as follows:

The notebooks for each chapter are in the root of the repository, prefixed with the chapter number.

The `data` folder is where to download relevant data sources (chapter 3 onwards)
The `run` folder stores output from the generative models (chapter 3 onwards)
The `utils` folder stores useful functions that are sourced by the main notebooks

## Book Contents
Part 1: Introduction to Generative Deep Learning
* Chapter 1: Generative Modeling
* Chapter 2: Deep Learning
* Chapter 3: Variational Autoencoders
* Chapter 4: Generative Adversarial Networks

Part 2: Teaching Machines to Paint, Write, Compose and Play
* Chapter 5: Paint
* Chapter 6: Write
* Chapter 7: Compose
* Chapter 8: Play
* Chapter 9: The Future of Generative Modeling
* Chapter 10: Conclusion


## Getting started

To get started, first install the required libraries inside a virtual environment:

`pip install -r requirements.txt`
 



## CP notes:
### Installing on OS X
first install Miniconda:
https://docs.conda.io/en/latest/miniconda.html

Next setup a new environment:
 `conda create -n generative python=3.6 ipykernel`

Activate the environment:
 `conda activate generative`

Install required modules
 `pip install -r requirements.txt`

Install jupyter with the 'generative' virtualenv
 `python -m ipykernel install --user --name generative`


Install core pytorch utils
 `pip install torch torchvision pytorch-lightning


Start a jupyter notebook
 `jupyter notebook`