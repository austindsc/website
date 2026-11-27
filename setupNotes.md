
---
### Venv notes/setup ###
cd path/to/project
python3.14 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install ipykernel numpy
python -m ipykernel install --user --name my-project --display-name "Python 3.14 (my-project)"