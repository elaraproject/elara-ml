# Elara ML

A minimalist, very lightweight library for machine learning in Rust.

**Please note:** Due to Rust's inherent design, Elara ML only runs fast if you compile in release mode. Running it in debug mode will be much slower.

## What is it?

Elara ML provides a simple way to create and train neural networks. It wraps low-level libraries such as `gad` and `ndarray` and implements various machine learning algorithmns, so you don't have to worry about the low-level details. It's fast and efficient by design, too.

## Goals

- Minimalist library (very few dependencies, small codebase)
- Fast and safe (w/ Rust)
- Easy to use API
- Work well within the Elara project
- Use no libraries except for `nanoserde`, `gad` (without `arrayfire`), and `ndarray`

## Features

- Model loading and saving
- Implementations of common ML optimization algorithms, activation functions, loss functions, etc.
- Modules to build complex neural networks

## Future goals

- Python API and publish library to PyPI
- Support for `intel-mkl` for CPU-acceleration
- Support for `arrayfire` optionally for GPU-acceleration

## Non-goals

- Support every use case
- Compete against industry-standard ML frameworks (e.g. Theano, TensorFlow, PyTorch)
