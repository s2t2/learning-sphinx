




# Learning Sphinx / Restructured Text


Setup environment and install Sphinx:

```sh
conda create -n docs-env python=3.10

conda activate docs-env

pip install -r requirements.txt
```


Getting Started:

```sh
cd docs/

# first time only:
sphinx-quickstart
```



Build:

```sh
make html
make latex
```



## References:

  + [How to Document using Sphinx: Part 1 — Setting up](https://www.youtube.com/watch?v=DSIuLnoKLd8)
