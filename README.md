### First run

```sh
python3.8 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip setuptools wheel ipykernel ipywidgets
ipython kernel install --user --name=.venv



python -m pip install -r requirements.txt

jupyter notebook

```


### Every followup run

``ssh
source .venv/bin/activate
jupyter notebook

```

