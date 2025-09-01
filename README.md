Haw you can upload folders between PC and github, by CMD or Terminal?


Clone un dépot avec un dossier: 
```
cd <chemin> #CMD
git init
git add .
git status
git commit -m "1st commit"
git branch -M main
git remote add origin <Depot github>
git remote -v
git push -u origin main
git push -u origin main --force
```
or 
```
cd <chemain> #CMD
git status
git add .
git commit -m "1st commit"
git push -u origin main
git push -u origin main --force
```
