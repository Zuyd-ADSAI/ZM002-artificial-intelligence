# ZM002-2425-artificial-intelligence

Minor AI notebooks and resources in English

## Getting started

Open a terminal and clone this repository using [git](https://git-scm.com/)
```bash
git clone git@github.com:Zuyd-ADSAI/ZM002-2425-artificial-intelligence.git
```

Navigate into the cloned folder
```bash
cd ZM002-2425-artificial-intelligence
```

Create a virtual environment where packages will be installed. This can be done via the [Anaconda](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) package manager or via a Python virtual environment ([venv](https://docs.python.org/3/library/venv.html)).

1. Using Anaconda, activate and install packages:
```bash
conda create --name zm002ai
conda activate zm002ai
conda install --yes --file requirements.txt
```

2. Using Python Virtual Environment, activate and install packages:
```bash
python -m venv .venv
activate
pip install -r requirements.txt
```
