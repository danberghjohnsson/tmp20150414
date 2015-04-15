# opstudkonf2015-git
Demo-repo för git-föreläsning på Omegapoint Academys Studentkonferens 2015

_Förberedelse_
se till att ha lämpliga certifikat mha ssh-agent ssh-add
Två kloner av
git@github.com:Omegapoint/opstudkonf2015-git.git
Blå resp grön


_Lokal ändring_

* blå klon
* cp kalmarevisan.txt kalmarevisan_kopia.txt
* open kalmarevisan_kopia
* ed s/borste/kvast/
* git status
* git diff
* git add
* git status
* git diff
* git diff --cached
* git commit

_Lokal historik_
ed s/käft/trut
git add
git diff
git commit
git log
ls .git
find .git

_Parallell utveckling_
grön klon
ed s/Dalrö/Kalmare
git add
git diff
git commit

_Gemensamt repo_
blå klon
git remote -v

grön klon
git remote -v
open https://github.com/Omegapoint/opstudkonf2015-git

blå klon
git push
https://github.com/Omegapoint/opstudkonf2015-git

grön klon
git push -> fail
git pull
cat kalmarevisan.txt
git log
git push

blå klon
git log
git pull
git log
cat kalmarevisan.txt

_Konflikt_
(behöver fixas)
blå klon
s/biblioteket/puben
git add
git commit

grön klon
s/biblioteket/restaurangen
git add
git commit

blå klon
git push

grön klon
git push -> fail
git pull -> confict

fix : krogen



_Starta lokalt_
git init

_Starta på Github_
create
git clone
