# releve-cli — Atelier Logiciel Nantais

`releve-cli` est un outil en ligne de commande, développé et documenté en équipe. Il lit un
fichier de relevés au format CSV (des mesures horodatées) et produit un rapport de synthèse :
nombre de mesures, moyenne, maximum, minimum, et signalement des doublons.

## Installation et démarrage

Prérequis : Terminal bash (WSL, Linux).

1. Cloner le projet

   ```
   git clone https://github.com/WayeNot/releve-cli-guichard-guibert-baffreau-le-roux-beaune.git
   ```

2. Installer les dépendances

    ```
    pip install -r requirements.txt
    ```

3. Lancer l'outil
    
    ```
    ./start.sh
    ```

Appeler l'outil :

    ```
    releve --help
    ```

## Usage

### Calculer une moyenne a partir d'un fichier :

    ```
    releve -m filename.txt
    ```

### Calculer maximum :

    ```
    releve -max filename.txt
    ```

## Architecture

[Deux à trois phrases : les grands blocs du système et comment ils
communiquent. Cette section renvoie vers le schéma détaillé, produit en
séance 3 — elle ne le duplique pas.]

Schéma détaillé : `docs/architecture.md` (produit en séance 3, pas encore présent).

## Organisation du dépôt

| Chemin | Contenu |
|---|---|
| `README.md` | Cette page : présentation, installation, usage, architecture. |
| `docs/reglages.md` | Référence des réglages disponibles. |
| `docs/demarrage.md` | Guide détaillé de démarrage. |
| `docs/architecture.md` | Schéma d'architecture détaillé (à venir, séance 3). |
| `CHANGELOG.md` | Journal des versions du projet (chapitre 3 : retirez cette ligne si vous ne le créez pas). |
| `config.example.txt` | Modèle de configuration, sans valeur réelle. |

## Contribution

- Une branche par sujet, nommée `docs/…`, `feat/…` ou `fix/…`.
- Un message d'enregistrement préfixé par `feat`, `fix`, `docs` ou `chore`.
- Toute modification passe par une demande de fusion relue par un autre membre.
- Aucune valeur réelle de configuration n'est enregistrée dans le dépôt.

## Contact

[Nom du binôme] — pour toute question, ouvrez une issue sur ce dépôt.
