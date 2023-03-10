Create conda environment

```bash
conda create -n env_name python=3.8 -y
```

To activate conda environment

```bash
conda activate wineq
```

Create the requirements.txt file

Install the requirements.txt file

```bash
pip install -r requirements.txt
```

Download the dataset from kaggle (wine quality)

dataset:- https://www.kaggle.com/datasets/rajyellow46/wine-quality

Initalize the git

```bash
git init
```

Initailze the dvc

```bash
dvc init
```

```bash
dvc add data_given/winquality.csv
```

```bash
git add . 
```

```bash
git commit -m "first commit"
```

Oneliner command
```bash
git add . && git commit -m "update Readme.md file"
```

```bash
git remote add origin <GITHUB REPO NAME>
git branch -M main
git push origin main
```

tox command -
```bash
tox
```

for rebuilding -
```bash
tox -r
```

pytest command
```bash
pytest -v
```

setup commands
```bash
pip install -e .
```

build your own package commands -
```bash
python setup.py sdist bdist wheel
```






