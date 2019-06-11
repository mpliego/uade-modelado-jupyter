# uade-modelado-jupyter

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mpliego/uade-modelado-jupyter/master)


# Instalación Local

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
deactivate
source .venv/bin/activate
ipython kernel install --user --name=.venv
jupyter notebook
```