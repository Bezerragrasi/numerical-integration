# Numerical Integration

In this book is available an overview about several Numerical Integration Methods.

## Booking Development

### Working locally

To work locally, first clone this GitHub repository:

```bash
git clone https://github.com/Bezerragrasi/numerical-integration.git
cd  numerical-integration
```

#### Building locally

*Note: this step is not mandatory. The book is automatically built by the `.github/workflows/buildbook.yml` action.*

Create the conda environment

```bash
conda env create --file environment.yml
conda activate jupyter-book-numint
```

*Note: depending on your operating system, you may need to replace `conda activate` with `source activate` in the above command.*

Finally, you can open the contents of this book using jupyter lab (included in the environment) - or any IDE of your choice.


To build your book locally:

```bash
jupyter-book build book/
```

