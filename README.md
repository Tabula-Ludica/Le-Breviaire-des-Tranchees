# Le Bréviaire des Tranchées

Système de jeu de rôle non officiel dans l'univers de **Trench Crusade** : règles, création de personnage et références, publié sur GitHub Pages.

Un projet [Tabula Ludica](https://github.com/Tabula-Ludica).

## Sommaire

Le site est en trois parties. En haut de la page, on choisit son camp : les règles communes adaptent leur vocabulaire, et seule la partie du camp choisi s'affiche.

### Règles communes

1. [Le Noyau](regles/commun/01-noyau.md)
2. [Les Caractéristiques](regles/commun/02-caracteristiques.md)
3. [Les Arcanes](regles/commun/03-arcanes.md) *(prototype)*
4. [Le Combat](regles/commun/04-combat.md) *(prototype)*
5. [La Progression](regles/commun/05-progression.md) *(prototype)*
- [L'Univers](regles/commun/univers.md) *(en préparation)*

### ✝ Les Fidèles

6. [La Création d'un Fidèle](regles/fideles/06-creation.md)
7. [La Corruption](regles/fideles/07-corruption.md) *(prototype)*
- [Le Monde des Fidèles](regles/fideles/monde.md) *(en préparation)*

### ⛧ Les Damnés

6. [La Création d'un Damné](regles/damnes/06-creation.md) *(prototype)*
7. [La Faveur](regles/damnes/07-faveur.md) *(prototype)*
- [Le Monde des Damnés](regles/damnes/monde.md) *(en préparation)*

### Écrire un texte commun aux deux camps

Dans `regles/commun/`, un mot entre doubles accolades s'adapte au camp : `{{le Chapelet}}` s'affiche « le Chapelet » chez les Fidèles et « le Calice » chez les Damnés. Les correspondances sont dans le `LEXIQUE`, en haut du script de `index.html`. Pour un passage entier réservé à un camp :

```html
<div data-camp="damnes">

Texte en Markdown, visible seulement chez les Damnés.

</div>
```

> Projet fan-made, non affilié à Factory Fortress Inc. Trench Crusade et son univers appartiennent à leurs auteurs.
