To create virtual env 
''' bash

conda create -n wineq python=3.7 -y

'''

conda activate wineq
create requirements.txt file
pip install -r requirements.txt

git init
dvc init
dvc add data_given/winequality.csv

git add .
git commit -m "first commit"

git remote add origin https://github.com/VivekMuraleedharanGit/MLOps.git
git branch -M main
git push origin main
