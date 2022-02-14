# Elara ML

A minimalist, very lightweight library for machine learning in Rust.

**Please note:** Due to Rust's inherent design, Elara ML only runs fast if you compile in release mode. Running it in debug mode will be much slower.

## Goals

- Minimalist (very few dependencies, small codebase)
- Fast and safe (w/ Rust)
- Easy to use API
- Work well within the Elara project

## Future goals

- Python API and publish library to PyPI
- Support for `intel-mkl` for acceleration

## Non-goals

- Support GPU-acceleration (it will remain CPU-only for the foreseeable future)
- Support every use case
- Compete against industry-standard ML frameworks (e.g. Theano, TensorFlow, PyTorch)
