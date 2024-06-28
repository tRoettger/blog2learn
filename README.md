# Blog um HTML zu lernen

## Ziel

Wir wollen eine Versionverwaltung.  
Das bedeutet wir können alte Stände unserer Entwicklung wiederherstellen.  

Dafür nutzen wir Git.

Mit den Befehlen:
```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tRoettger/blog2learn.git
git push -u origin main
```
legen wir ein lokales Repository an.
Diese wird dann mit `git remote` und `git push` auf das Github Repository gespiegelt.