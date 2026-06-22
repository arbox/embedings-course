# Embeddings Course

A short, hands-on course on numeric representations for linguistic units (word embeddings) — from the basics of vector representations to practical alignment and similarity techniques.

## What you'll learn

- How words and other linguistic units get represented as vectors
- How to train, load, and inspect embedding models
- How to measure similarity and explore embedding spaces
- Practical applications and common pitfalls

## Prerequisites

You'll need a working Python environment capable of running Jupyter notebooks, with permission to install additional packages as needed.

- **Python**: 3.10+ recommended
- **Jupyter**: JupyterLab or Jupyter Notebook installed and working
- **Package manager**: `pip`, [`uv`](https://github.com/astral-sh/uv) (or `conda`/`mamba`), with the ability to install new packages during the course
- **Admin/install rights**: you should be able to install Python packages (and, if needed, command-line tools) on your machine without IT restrictions blocking you
- **Operating system**: any *unix-like OS (macOS, Linux) is recommended; Windows works too (e.g. via WSL)

### Quick setup check

Before the course starts, please confirm you can do the following:

```bash
python3 --version        # should be 3.10 or newer
pip install --upgrade pip
jupyter --version         # should print without error
```

If `jupyter` isn't found, install it with:

```bash
pip install jupyterlab
# or, with uv:
uv pip install jupyterlab
```

We'll install course-specific packages (e.g. `numpy`, `gensim`, `scikit-learn`, embedding libraries) together at the start of the course.

## Getting started

1. Clone this repository
2. Set up your Python environment (see Prerequisites above)
3. Launch Jupyter and open the first notebook

```bash
git clone <repo-url>
cd embeddings-course
jupyter lab
```

## License

TBD
