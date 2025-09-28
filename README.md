# Prétraitement d'images médicales

Ce dépôt contient le notebook de l'atelier 2 : prétraitement d'images médicales (Mme ATTIA).

## Contenu

- `02_Pretraitement_d'images_medicales_Mme_ATTIA.ipynb` — Notebook principal pour le prétraitement des images.
- `LICENSE` — Licence du projet (voir ce fichier pour les détails).

## Objectif

Exemples et exercices montrant des étapes de prétraitement d'images médicales : lecture d'images, normalisation, filtrage, amélioration du contraste, etc. Le contenu est fourni dans un unique notebook Jupyter.

## Prérequis

- Python 3.8+ recommandé
- Jupyter (Notebook ou JupyterLab) ou Visual Studio Code avec l'extension Jupyter

Installer rapidement les outils (exemple) :

```powershell
python -m pip install --user jupyter notebook
```

Si vous utilisez un environnement virtuel (recommandé) :

```powershell
python -m venv .venv ; .\.venv\Scripts\Activate.ps1 ; pip install jupyter
```

## Ouvrir le notebook

1. Depuis VS Code : ouvrez le dossier du projet, puis cliquez sur le notebook `02_Pretraitement_d'images_medicales_Mme_ATTIA.ipynb`.
2. Depuis la ligne de commande :

```powershell
jupyter notebook
# puis ouvrez le fichier `02_Pretraitement_d'images_medicales_Mme_ATTIA.ipynb` dans votre navigateur
```

## Commandes Git (PowerShell)

Si vous modifiez le notebook et voulez pousser vos changements :

```powershell
Set-Location -LiteralPath 'C:\Users\wael\OneDrive - SUPCOM\Bureau\SIA\atelier imagerie medicale\atelier 2\solution'
git add "02_Pretraitement_d'images_medicales_Mme_ATTIA.ipynb"
git commit -m "Update notebook"
git push origin main
```

Si le dépôt distant nécessite un token ou des identifiants, configurez un helper de credentials ou utilisez un Personal Access Token (PAT) pour HTTPS pushes.

## Licence
Voir le fichier `LICENSE`.

## Contact
Pour toute question sur le notebook ou les instructions, répondez dans cette issue/PR ou contactez le mainteneur du dépôt.
# Pretraitement_d-images_medicales