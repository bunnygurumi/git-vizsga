git clone git@github.com:szabopeter92/git-vizsga.git - a teljes projectet lehúzza a visual studionkba, mindegy ki, mikor töltötte fel és történt-e benne változás. Az ott lévő aktuális fájlokat letölti az érintett projectből. 
cd git-vizsga/ - beleléptem a klónozott mappába
git remote set-url origin git@github.com:bunnygurumi/git-vizsga.git - saját repository-t állítom originnak
git checkout -b console - létrehoztam egy mellékágat és átléptem az új ágba
git add . - hozzáadtam az új fájlokat a staging area-hoz .gitignore és README.md és a módosítt javascript és css fájlokat.
git status - lekértem, hogy sikerült-e a hozzáadás
git commit -m "initial commit" - commitáltam a módosított fájlokat, initial commit message-el
git push -u origin console - feltöltöm a távoli repoba