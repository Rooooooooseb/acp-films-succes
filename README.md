# Blockbusters vs classiques : existe-t-il un profil type du film à succès ?

Projet universitaire (Licence Économie-Gestion, CMI Data for Social Sciences, Université Paris-Nanterre).
Analyse en composantes principales (ACP) appliquée à un corpus d'une cinquantaine de films.

## Problématique
Le cinéma oscille entre films à succès commercial et films qui marquent durablement la critique.
Comment les différencier ? Existe-t-il un profil type du film à succès, critique ou commercial ?
Peut-on le prévoir dès la sortie ?

## Données
Corpus de films emblématiques, classiques de la critique (note > 8) et blockbusters (budget de production > 100 M).
Variables : budget de production, recettes, nombre de salles, durée, date de sortie,
notes du réalisateur et des acteurs, récompenses, notes IMDb, Rotten Tomatoes et Metacritic.
Les variables ont été centrées-réduites avant l'analyse.

## Méthode
- Collecte et mise en forme des données sous Excel
- Standardisation des variables
- R (ACP) : 5 dimensions retenues (80,3 % de variance cumulée)
- Analyse des contributions, du cercle des corrélations et de la projection des films
- Comparaison de groupes : adaptation vs original, nationalité, type de production

## Résultats principaux
- **Axe 1 (34,7 % de la variance) : performance commerciale** (budget, recettes, date de sortie)
- **Axe 2 (17,6 %) : reconnaissance critique** (IMDb, Metacritic, Tomatoes, récompenses)
- Deux axes de succès bien distincts, mais certains films combinent les deux (ex. : Avatar)
  tandis que d'autres relèvent surtout de la reconnaissance critique (ex. : Casablanca)
- Les films originaux se situent plutôt dans la partie haute (meilleure reconnaissance) ;
  les adaptations sont plus dispersées, donc leur réception est plus variable
- Les films américains se placent à droite (succès commercial, films récents) ;
  les films européens au centre et en haut (reconnaissance critique)
- Le type de production (majeur, indépendant, autre) influence la trajectoire d'un film

## Conclusion
Deux axes de succès distincts, certains films combinent les deux.
La prédiction est possible, mais limitée.

## Contenu du dépôt
- [Voir la présentation](presentation.pdf)

*Note : les données brutes et le code n'ont pas été conservés ; seule la présentation est disponible.*
