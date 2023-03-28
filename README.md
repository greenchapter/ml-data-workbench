# 🧪🐍 ML/Data workbench

That is my data science workbench which is **dedicated** build to **running tensorflow** with tensorflow-metal **on Apple Silicon**.

For more detailed informations please check https://developer.apple.com/metal/tensorflow-plugin/


## Build up a Python virtual environment
```bash
brew install python3.10
```

```bash
python3.10 -m venv .
```

```bash
source ./bin/activate
```
*(currently, it looks like that `tensorflow-macos==2.11.0` and `tensorflow-metal==0.7.0` espacially needs Python in version 3.10)*

## Prepare the Python virtual environment

```bash
python -m pip install -U pip
```

## Install Python tensorflow and data wrangling dependencies

```bash
 pip install -r requirements.txt
```

## Run Jupyter Lab

```bash
jupyter-lab notebooks
```

```bash
jupyter lab build
```

*(If your interested in running the classic Jupyter Notebook https://jupyter.org/install#jupyter-notebook)*
