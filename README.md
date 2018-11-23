# Modelling tutorial (WS2018)

Python based practical tutorial at Humboldt University Berlin, Institute for Biology
- We will use `python3` with a few core packages like `numpy`, `scipy`, `pandas` and `matplotlib`.
- Recommended to bring own laptop to follow along

For questions please contact
konigmatt@googlemail.com

## Content
[01 Boolean networks & Cellular automata](01_boolean_cellular/01_boolean_cellular.ipynb)

## Setup virtual environment
The notebooks can be executed in a virtual environment.
```bash
mkvirtualenv modelling --python=python3
(modelling) pip install -r requirements.txt
(modelling) pip install ipykernel jupyterlab
ipython kernel install --user --name=modelling
(modelling) jupyter lab
```
