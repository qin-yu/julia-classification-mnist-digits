# ML from Scratch 2: MNIST Handwritten Digits Classification by Kernel Perceptron (#Multiprocessing)
by **Qin Yu**, Dec 2018  
(all code tested on 24-core machine)

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/qin-yu/ml-julia-boston-housing/blob/master/LICENSE)
[![Julia v1.0.2](https://img.shields.io/badge/Julia-v1.0.2-brightgreen.svg)](https://julialang.org/blog/2018/08/one-point-zero)

All Machine Learning Examples:
- ML from Scratch 1: [Linear Regression & Kernel-Ridge Regression (KRR) on Boston Housing Dataset](https://github.com/qin-yu/julia-regression-boston-housing) [![Julia v1.0.1](https://img.shields.io/badge/Julia-v1.0.1-brightgreen.svg)](https://julialang.org/blog/2018/08/one-point-zero)
- ML from Scratch 2: [Classification (Kernel Perceptron) on MNIST Handwritten Digits (#Multiprocessing)](https://github.com/qin-yu/julia-classification-mnist-digits) [![Julia v1.0.2](https://img.shields.io/badge/Julia-v1.0.2-brightgreen.svg)](https://julialang.org/blog/2018/08/one-point-zero)

## Contents
- [Manifesto](#manifesto)
- [Overview of Examples](#overview-of-examples)
- [Algorithms and Tricks](#algorithms-and-tricks)
- [About The MNIST Database of Handwritten Digits (external link)](http://yann.lecun.com/exdb/mnist/)

## Manifesto
Julia 1.0 was released during JuliaCon in August 2018, two months before I started to look into machine learning. Last time when I was working on regression, I had fun playing with it, felt its power, and decided to use it again for classifying MNIST handwritten digits. This example includes the use of multiprocessing in Julia, so it would be great if run my code on a machine with more than 20 cores. A 12-core desktop like mine will do: just come with some other ways of splitting the tasks, and we have an alternative parallelism.

## Overview of Examples
- Basics:
    - 2-class Kernel Perceptron
    - Multi-class Kernel Perceptron (one-vs-rest)
        - Choice of Epochs & Parameters
    - Multi-class Kernel Perceptron (one-vs-one)
- Formal Examples:
    - Multi-class Kernel Perceptron (one-vs-rest) with 5-fold Cross-validation
        - Confusion Matrix
        - Digits that are Hardest to Predict
    - Multi-class Kernel Perceptron (one-vs-one) with 5-fold Cross-validation

## Algorithms and Tricks
