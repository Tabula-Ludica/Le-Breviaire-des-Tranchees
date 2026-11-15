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
6. [L'Arrière](regles/commun/06-arriere.md) *(prototype)*
7. [Le Bestiaire](regles/commun/07-bestiaire.md) *(prototype)*
- [L'Univers](regles/commun/univers.md) *(en préparation)*

### ✝ Les Fidèles

8. [La Création d'un Fidèle](regles/fideles/08-creation.md)
9. [La Corruption](regles/fideles/09-corruption.md) *(prototype)*
10. [Les Rites](regles/fideles/10-rites.md) *(prototype)*
- [Le Monde des Fidèles](regles/fideles/monde.md) *(en préparation)*

### ⛧ Les Damnés

8. [La Création d'un Damné](regles/damnes/08-creation.md) *(prototype)*
9. [La Faveur](regles/damnes/09-faveur.md) *(prototype)*
10. [Les Rites noirs](regles/damnes/10-rites-noirs.md) *(prototype)*
- [Le Monde des Damnés](regles/damnes/monde.md) *(en préparation)*

### Écrire un texte commun aux deux camps

Dans `regles/commun/`, un mot entre doubles accolades s'adapte au camp : `{{le Chapelet}}` s'affiche « le Chapelet » chez les Fidèles et « le Calice » chez les Damnés. Les correspondances sont dans le `LEXIQUE`, en haut du script de `index.html`. Pour un passage entier réservé à un camp :

```html
<div data-camp="damnes">

Texte en Markdown, visible seulement chez les Damnés.

</div>
```

> Projet fan-made, non affilié à Factory Fortress Inc. Trench Crusade et son univers appartiennent à leurs auteurs.
