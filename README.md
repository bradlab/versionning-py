# versionning
Ce projet est un exemple de projet Python utilisant un environnement virtuel (`venv`) et un fichier `Makefile` pour automatiser l'installation.

## 🧰 Prérequis

- Python 3.7 ou supérieur
- `make` (facultatif, mais recommandé pour exécuter les commandes facilement)

## venv: virtual environment
```bash
$ python -m venv venv
```

## Activate venv
```bash
$ venv/Scripts/activate
```

## Install dependencies
```bash
$ pip install --upgrade pip setuptools
$ pip install -r requirements.txt
```

## Use make
```bash
$ make install
```

## Launch projet
```bash
$ python main.py
```
