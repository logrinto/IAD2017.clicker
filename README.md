# IAD2017.clicker-game


## Eigenes Game hinzufügen

```sh
# Repo klonen
git clone git@github.com:logrinto/IAD2017.clicker-game.git

# in Verzeichnis wechseln
cd IAD2017.clicker-game


# ACHTUNG!!!! HTML-URL!!!
# Eigenes Game hinzufügen.
# ACHTUNG!!!! HTML-URL!!!
# Beispiel git submodule add -b gh-pages https://github.com/signalwerk/cookie-clicker.git docs/-example/
# Bitte {name} in index.html prüfen
git submodule add -b gh-pages https://github.com/{username}/{reponame}.git docs/{name}/


# alle Änderungen commiten
git commit -a -m 'ADD: module'

# Änderungen pushen
git push origin master
```


## Alle Games updaten
```sh
# in Verzeichnis wechseln
cd IAD2017.clicker-game

# alle updaten
git submodule update --recursive --remote

# alle Änderungen commiten
git commit -a -m 'MOD: update modules'

# Änderungen pushen
git push origin master
```

### Links
* [Aufgabestellung](https://signalwerk.github.io/IAD.LAB.DOC/exercise-cookie-clicker/)
