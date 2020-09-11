# Git (Oppgave 3)
* Sette opp git lokalt
- git init
* Sette opp nytt repo i Github
- Lagde repository på GitHub
- git remote add origin https://github.com/Ranum99/oblig3Webbapplikasjoner.git
* Lage dev branch lokalt
- git checkout -b dev
* Lage fil i dev branch lokalt (hiof.js fil med console.log("hiof"))
- git add hiof.js
* Commite disse
- git commit -m "First commit"
* Pushe endringene til repo
- git push -u origin dev
* Lage en fil i dev branch remote
- Gjorde det i GitHub
* Hente endringene lokalt
- git pull 
* Merge filene fra dev i master
- git merge dev --allow-unrelated-histories
* Samarbeide med en kollega eller en annen konto du har for å få til merge conflict
- Lagde en ny mappe til dette
- git init
- git branch -a
- git checkout -b newBranch
- git add .
- git commit -m "test"
- git branch branch-a
- git branch branch-b
- git checkout branch-a
- Endrer på filen i VSCode
- git add .
- git commit -m "endring 1"
- git checkout branch-b
- Endrer på filen i VSCode
- git add .
- git commit -m "endring 2"
- git checkout -b branchMaster
- git merge branch-a
- git merge branch-b
- ![Merge conflict](bilder/oppgave3mergeConflict.png)
* Resolve merge conflict
- Gjorde det i VSCode