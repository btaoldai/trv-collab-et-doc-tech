# Aide-mémoire — étiqueter et formuler un retour

## Les cinq étiquettes de portée

| Étiquette | Quand l'employer | Effet attendu |
|---|---|---|
| `bloquant` | Le lecteur ne peut pas continuer sans correction | Prioritaire ; doit rester rare |
| `question` | Une information manque et ne peut pas être devinée | Souvent plus utile qu'une correction |
| `suggestion` | Une amélioration réelle, que l'équipe peut écarter | Réponse attendue, acceptation facultative |
| `détail` | Forme, accent, renvoi, nom de fichier | Correction rapide, groupée en fin de revue |
| `bravo` | Ce qui fonctionne et doit être conservé | Indique ce qu'il ne faut pas casser |

## La formule en trois temps

```
<étiquette> : <le fait, sans qualificatif>.
<la conséquence pour le lecteur>.
piste, à titre d'exemple : <une formulation possible>.
```

## Exemple complet

```
bloquant : le fichier de présentation renvoie vers docs/installation.md,
qui n'existe pas dans le dépôt. Une personne qui suit le document
s'arrête ici et n'a aucun moyen de continuer.
piste, à titre d'exemple : corriger le renvoi, ou créer le fichier attendu.
```

## Ce qui ne compte pas comme retour de fond

- « C'est bon pour moi », « joli schéma », une approbation sans commentaire.
- Une correction d'accent isolée présentée comme une revue.
- Une remarque sur les auteurs plutôt que sur le document.
