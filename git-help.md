# git-help.md

### $ git >> git-help.md

```bash
ús: git [--version] [--help] [-C <path>] [-c <name>=<value>]
      [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
      [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
      [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
      <command> [<args>]

Aquestes són ordres del Git habitualment usades en diverses situacions:

començar una àrea de treball (vegeu també: git help tutorial)
  clone        Clona un dipòsit a un directori nou
  init         Crea un dipòsit de Git buit o reinicialitza un existent

treballar en el canvi actual (vegeu també: git help everyday)
  add          Afegeix els continguts dels fitxers a l'índex
  mv           Mou o canvia de nom a un fitxer, directori o enllaç simbòlic
  restore      Restaura els fitxers de l'arbre de treball
  rm           Elimina fitxers de l'arbre de treball i de l'índex
  sparse-checkout  Initialize and modify the sparse-checkout

examinar la història i l'estat (vegeu també: git help revisions)
  bisect       Troba per cerca binària el canvi que hagi introduït un defecte
  diff         Mostra els canvis entre comissions, la comissió i l'arbre de treball, etc
  grep         Imprimeix les línies coincidents amb un patró
  log          Mostra els registres de comissió
  show         Mostra diversos tipus d'objectes
  status       Mostra l'estat de l'arbre de treball

fer créixer, marcar i ajustar la vostra història comuna
  branch       Llista, crea o suprimeix branques
  commit       Registra els canvis al dipòsit
  merge        Uneix dues o més històries de desenvolupament
  rebase       Torna a aplicar les comissions sobre un altre punt de basament
  reset        Restableix la HEAD actual a l'estat especificat
  switch       Commuta branques
  tag          Crea, llista, suprimeix o verifica un objecte d'etiqueta signat amb GPG

col·laborar (vegeu també: git help workflow)
  fetch        Baixa objectes i referències d'un altre dipòsit
  pull         Obtén i integra amb un altre dipòsit o una branca local
  push         Actualitza les referències remotes juntament amb els objectes associats

«git help -a» i «git help -g» llisten subordres disponibles i
algunes guies de concepte. Vegeu «git help <ordre>» o
«git help <concepte>» per a llegir sobre una subordre o concepte específic.
```

Vegeu «git help git» per a una visió general del sistema.

---


## SSH | git@github.com:miquelinux/Docs.git
## HTTPS | https://github.com/miquelinux/Docs.git


# Quick setup — if you’ve done this kind of thing before

* SSH | git@github.com:miquelinux/Docs.git
* HTTPS | https://github.com/miquelinux/Docs.git

Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.


# …or create a new repository on the command line

```bash
echo "# Docs" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/miquelinux/Docs.git
git push -u origin main
```

# …or push an existing repository from the command line

```bash
git remote add origin https://github.com/miquelinux/Docs.git
git branch -M main
git push -u origin main
```

# …or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


# Anotacions

```bash
git init
git config --list
git config user.name "MiqueLinux"
git config user.email "<miquelinux@gmail.com>"
git config credential.helper cache
git config --list
git remote add origin https://github.com/miquelinux/Docs.git
git branch -M main
git add README.md
git status
git commit -m "README.md"
git status -s
git log --oneline
git branch -M main
git push -u origin main
git add git-help.md
git commit -m "git-help.md"
git status -s
git log --oneline
git branch -M main
git push -u origin main
git diff
git add .
git commit -m "Modificacions"
git push -u origin main
git log --oneline
git show
```

23 de desembre de 2020

