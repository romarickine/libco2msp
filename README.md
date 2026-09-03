# Lib&CO2 MSP — Paquet de déploiement GitHub Pages

Ce dossier contient tout ce qu'il faut pour publier l'outil.

## Contenu

- **`index.html`** — l'outil complet (site autonome, aucune dépendance externe). Doit impérativement s'appeler `index.html` pour que GitHub Pages le serve automatiquement à la racine du site.
- **`LibCO2-MSP-Notice-methodologique.docx`** — la notice méthodologique, reliée depuis le pied de page de l'outil par un lien relatif (`./LibCO2-MSP-Notice-methodologique.docx`). Doit rester dans le **même dossier** qu'`index.html`, sous ce nom exact, sinon le lien ne fonctionnera pas.

## Marche à suivre

1. Crée un nouveau dépôt GitHub (ou réutilise un dépôt existant dédié à cet outil).
2. Dépose les deux fichiers de ce dossier **à la racine** du dépôt — pas dans un sous-dossier — en conservant leurs noms exacts. **GitHub Desktop est recommandé plutôt que l'upload web**, qui a déjà posé des soucis de structure de fichiers sur le projet Lib&CO2 CAB.
3. Dans les paramètres du dépôt (Settings → Pages), active GitHub Pages sur la branche principale (`main`), dossier racine (`/`).
4. Le site sera accessible à une adresse du type `https://<ton-compte>.github.io/<nom-du-depot>/`.

## À chaque mise à jour de l'outil

Remplace `index.html` (et le `.docx` si la méthodologie évolue) par la nouvelle version, en conservant les mêmes noms de fichiers — aucune autre manipulation nécessaire.
