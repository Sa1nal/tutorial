Github segédlet
VSC terminál - git bash(ha nincs ilyen, akkor Git SCM telepítése)
mkdir tutorial - make directory tutorial nevű mappa
cd tutorial - change directory
echo "Github segédlet" >> readme.md - readme.md fájl létrehazása és a szöveg beszúrása
git init - mappa inicializálása
git config --global --list - globális beállítások listázása
git revote -v - távoli repo-k címének lekérdezése
git remote add https://github.com/Sa1nal/tutorial.git - fávoli repo hazzáadása origin néven
git remote remove origin - origin nevű távoli repo eltávolítása
git add readme.md - váltaztatások metése(staging)
git commit -m "first commit" - commit hazzáadása
git branch -m main - az ág átnevezáse main-re
