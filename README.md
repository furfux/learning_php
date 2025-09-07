# My App (Python)

Projet Python initialisé avec structure moderne, outils qualité et CI.

## Installation

1. Créer un virtualenv et activer
```bash
python -m venv .venv
source .venv/bin/activate
```
2. Installer en mode editable avec dépendances dev
```bash
pip install -e .[dev]
```

## Commandes utiles

```bash
ruff check .
black .
mypy .
pytest -q
```

## Exemple d'utilisation

```python
from my_app import hello
print(hello("Monde"))
```

