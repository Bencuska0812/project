# ZÁRÓ - VERZIÓKEZELÉS
# PROJECT - HELYI  REPO
# összekappcs

- inicializálás
> git init
# Összekapcs a távoli repoval

- ellenőrzés
> git status 

- Előkészítjük a commit-re
> git add
- Ellenőrzés

> git status 

- Helyi gépen ellenőrízzük 
> git config user.name

>git config user.email

- Eltároljuk mint új verzió 
> git commit -m "first commit"

## ÖSSZEKAPCS REPO

- GITHUB repo létrehozás
- Összekapcsolási parancs:
>   git remote add origin https://github.com/Bencuska0812/project.git

- meg kell mondani a legleső alkalommal, hogy melyik ágat használjuk és feltesszük a legújabb verziónkat.
> git push -u origin master