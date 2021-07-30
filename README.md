To create virtual env 

```bash
conda create -n wineq python=3.7 -y
```
To activate the virtual evn
```bash
conda activate wineq
```

create requirements.txt file 

Install the requirements 
```bash
pip install -r requirements.txt
```

```bash
git init
```
```bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```
to add the new changes to remote
```bash 
git add .
```
commit the changes 
```bash

git commit -m "first commit"
```
TO add repository 
```bash
git remote add origin https://github.com/VivekMuraleedharanGit/MLOps.git
git branch -M main
git push origin main
```


tox command
```bash
tox
```
for rebuilding 
```bash
tox-r
```
pytest command
```bash
pytest -v
```

setup commands - local package installation
```bash
pip install -e .
``` 

build our own package - tar file
```bash 
python setup.py sdist bdist wheel
```
