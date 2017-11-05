# Parsing Science Toolkit

A repo with custom PyMC3 models, transformers, and visualizers.

## Set up
```sh
git clone https://github.com/parsing-science/ps-toolkit.git
cd ps-toolkit
```

## Import the repo
To use the package, add it to the requirements.txt of your repo and pip install

SSH: git+ssh://git@github.com/parsing-science/ps-toolkit.git#egg=PS_Toolkit

To install a specific version:

SSH: git+ssh://git@github.com/parsing-science/ps-toolkit.git@[tag]#egg=PS_Toolkit

where [tag] is a specific version tag, e.g. `v1.0.0`.

## To run unittests
```sh
cd ps-toolkit
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
python -m unittest discover -cv
```
