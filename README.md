# Desafio-Branching

# Push folder in repository

cd git_landing

git init

git add .

git commit -m "primer commit"

git branch -M master

git remote add origin https://github.com/FelipeCarrascoLopez/Desafio-Branching.git

git push -u origin master


# Create pull request with branch development


git pull

git checkout -b development

git commit -m "modificacion funcionalidad boton index"

git push --set-upstream origin development