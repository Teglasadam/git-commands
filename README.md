TERMINAL ALAP:
ls - adott helyen elérhető fájlok
cd - change directory (belépni / kilépni az adott mappából)
cd .. - Visszalépés 1el
clear - letisztítja a terminált
mkdir - mappa létrehozása
touch - fájl létrehozása
code . - megnyitja kódszerkesztővel a jelenlegi mappát

GIT parancsok:
Felhasználói adatok beállítása:
git config --global user.name "NÉV"
git config --global user.email "EMAIL CÍM"

Lekérdezés:
git config user.name
git config user.email

git init - Egy üres GIT könyvtárat ad hozzá a projekthez
git status - Az adott projektet nézi meg hogy minden fájl rögzítésre került-e, illetve tájékoztat az utoljára módosított fájlokról.

Fájlok hozzáadása:
git add név - Egy adott fájlt ad hozzá a staging -rea hoz.
git add *.html - Minden megemlített fájltípus hozzáadása .
git add . - Minden fájlt hozzáad a Staging Area-hoz.

Fájlok kivétele:
git rm --cached név - adott fájl törlése.


