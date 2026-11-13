# Chapitre V — Le Combat

Le combat du Bréviaire est **tactique** : il se joue sur une carte quadrillée, avec des jetons, et il est pensé avant tout pour **Foundry VTT**. Toutes les **distances sont en mètres** et se mesurent avec la règle de la table virtuelle.

---

## 1. Préparer la table

### Sur Foundry VTT

| Réglage | Valeur conseillée |
|---|---|
| Grille | Carrée, **1 case = 1,5 m** |
| Unité de distance | **m** |
| Barre 1 des jetons | **Blessures** |
| Suivi de combat | Initiative par phases (voir §2) : **3**, **2** ou **1** |
| États utiles | *Paniqué*, *Hors de combat*, *Hémorragie*, *Immobilisé*, *Viseur* |

Sur une table physique, on utilise la même échelle avec une grille ou une règle.

---

## 2. L'initiative par phases

Au début d'un combat, **chaque personnage fait un jet de Nerf** (Spécialités et difficulté ne s'appliquent pas, sauf circonstances décidées par le MJ).

| Résultat | Phase | Valeur Foundry |
|---|---|---|
| Réussite | **Phase rapide** : avant les ennemis | **3** |
| — | **Phase ennemie** : tous les ennemis | **2** |
| Échec | **Phase lente** : après les ennemis | **1** |

Dans une même phase, les joueurs choisissent leur ordre entre eux.

On ne lance l'initiative **qu'une seule fois** par combat, mais la phase d'un personnage peut changer en cours de route :

- **Reprendre l'initiative :** un personnage en phase lente peut dépenser **son action** pour relancer son jet de Nerf. S'il réussit, il passe en **phase rapide** à partir du tour suivant.
- **Perdre l'initiative :** un personnage qui subit une **Blessure grave** ou qui devient **paniqué** passe automatiquement en **phase lente**.

Sur Foundry, il suffit de changer sa valeur dans le suivi de combat (3 ou 1).

**Embuscade :** un camp surpris passe tout entier en phase lente au premier tour.

---

## 3. Le tour d'un personnage

À son tour, un personnage peut faire :
- **1 déplacement et 1 action**, dans l'ordre qu'il veut ;
- **ou 2 déplacements**.

### Se déplacer

| Mouvement | Distance |
|---|---|
| **Déplacement normal** | **9 m** |
| **Ramper** | **3 m** ; compte comme un couvert léger contre les tirs venant de plus de 20 m |
| **Porter un blessé** | **4,5 m** |
| **Armure lourde** | **6 m** au lieu de 9 |

### Les actions

| Action | Effet |
|---|---|
| **Tirer** | Jet de **Tir** contre une cible en vue (§4). Puis test d'usure de **Munitions**. |
| **Frapper** | Jet de **Mêlée** en opposition contre une cible au contact (1,5 m, ou l'allonge de l'arme). |
| **Lancer** | Jet de **Lancer** : grenade, eau bénite, cocktail… (§6). |
| **Viser** | Le prochain tir est **favorisé**. Perdu si le personnage se déplace ou est touché avant. |
| **Se mettre à couvert** | Jusqu'à son prochain tour, son couvert est amélioré d'un cran (aucun → léger → lourd). |
| **Soigner** | Jet de **Médecine** sur un personnage au contact (§7). |
| **Rallier** | Jet de **Commandement** : un allié paniqué en vue se reprend (§8). |
| **Reprendre l'initiative** | En phase lente seulement : nouveau jet de **Nerf**. Réussite → phase rapide au tour suivant (§2). |
| **Autre** | Couper des barbelés, poser une charge, ouvrir une porte, saboter… au jugement du MJ. |

**Prier et pactiser** ne coûtent pas d'action : ils se décident juste avant un jet (chapitre I).

### La réaction : Plonger

**Une fois par tour de jeu**, quand un personnage est pris pour cible d'un tir, il peut **plonger** : jet d'**Esquive**.
- **Réussite :** le tir est **défavorisé**.
- **Dans tous les cas**, le personnage n'aura droit qu'à **un seul déplacement ou une seule action** à son prochain tour.

---

## 4. Tirer

Le tireur fait un jet de **Tir**. Sa difficulté dépend du **couvert** de la cible et de la **portée**.

### Le couvert

| Couvert de la cible | Exemples | Modificateur |
|---|---|---|
| **Aucun** | À découvert, en plein no man's land | 0 |
| **Léger** | Sacs de sable bas, bord de cratère, broussailles, fumée | **−2** |
| **Lourd** | Parapet, mur, béton, épave de char | **−5** |
| **Total** | Entièrement caché | Tir impossible |

### La portée

Chaque arme à distance a une **portée courte** et une **portée longue**, en mètres.

| Distance | Modificateur |
|---|---|
| Jusqu'à la **portée courte** | 0 |
| Jusqu'à la **portée longue** | **−2** |
| **Au-delà** | Tir impossible |

### Après le tir

Que le tir touche ou non, le tireur fait un **test d'usure de Munitions**. Sur une **rafale** (§6), le test est **défavorisé** : on lance deux fois le dé de Munitions et on garde le plus bas.

**Munitions épuisées :** impossible de tirer avant d'être ravitaillé (un camarade, un cadavre, une caisse…).

---

## 5. Frapper

Le corps à corps est un **jet en opposition** (chapitre I) :
- l'attaquant lance en **Mêlée** ;
- le défenseur lance en **Mêlée** pour parer, ou en **Esquive** pour se dégager.

Le camp qui **réussit avec le résultat le plus élevé** l'emporte. Si l'attaquant l'emporte, il inflige ses dégâts. Si le défenseur l'emporte avec Mêlée, il ne riposte pas, mais l'attaquant est **défavorisé** à sa prochaine attaque contre lui.

**Charger :** un personnage qui se déplace d'au moins 6 m en ligne droite puis frappe dans le même tour est **favorisé**.

---

## 6. Armes et protections

### Les dégâts

Une attaque réussie inflige le **dé de dégâts** de l'arme, **moins la Protection** de la cible. Le résultat est retiré des **Blessures** (minimum 0).

### Armes de corps à corps

| Arme | Dégâts | Particularités |
|---|---|---|
| **Couteau de tranchée** | d4 | *Discret* : favorisé contre une cible qui ne l'a pas vu venir |
| **Baïonnette** (sur fusil) | d6 | Ne nécessite pas de changer d'arme |
| **Masse cloutée** | d8 | *Brutal* : ignore 1 point de Protection |
| **Fléau** | d8 | *Sacré* : dégâts doublés contre les Démons |
| **Hallebarde** | d10 | *Allonge* : frappe jusqu'à 3 m ; *Deux mains* |
| **Poings, crosse, pelle** | d4 | — |

### Armes à distance

| Arme | Dégâts | Portée courte / longue | Particularités |
|---|---|---|---|
| **Pistolet** | d6 | 10 m / 30 m | Utilisable au contact |
| **Carabine** | d8 | 30 m / 100 m | — |
| **Fusil** | d8 | 50 m / 200 m | Accepte une baïonnette |
| **Fusil à lunette** | d10 | 100 m / 400 m | *Lunette* : en visant, ignore le malus de portée longue |
| **Mitrailleuse légère** | d10 | 50 m / 200 m | *Rafale* ; *Lourde* |

- **Rafale :** au lieu d'un tir normal, l'arme peut viser **jusqu'à 3 cibles** à 3 m ou moins les unes des autres. Un seul jet de Tir, contre le couvert le plus favorable des cibles ; chaque cible touchée subit les dégâts. Le test de Munitions est défavorisé.
- **Lourde :** sans être posée sur son trépied (une action), l'arme tire **défavorisée**.

### Armes lancées et explosifs

Les grenades et les charges se **comptent à l'unité** : elles ne passent pas par le dé de Munitions.

| Arme | Dégâts | Portée | Zone | Particularités |
|---|---|---|---|---|
| **Grenade** | d10 | 20 m | 3 m de rayon | Raté : tombe à d6 × 1,5 m du point visé |
| **Cocktail incendiaire** | d6 | 15 m | 2 m de rayon | *Enflammé* : d4 par tour jusqu'à ce qu'on s'éteigne (une action) |
| **Eau bénite** (fiole) | d6 | 10 m | Une cible | Ne blesse que les Démons, mais ignore leur Protection |
| **Charge explosive** | 2d10 | Posée | 5 m de rayon | Une action pour la poser ; Explosifs pour la régler |

Une cible prise dans une zone peut faire un jet d'**Esquive** : en cas de réussite, elle ne subit que **la moitié** des dégâts.

### Protections

| Protection | Valeur | Particularités |
|---|---|---|
| **Casque** (dotation de tous) | 1 | — |
| **Cuirasse de tranchée** | 2 | Remplace le casque seul |
| **Armure de plaques** | 3 | *Lourde* : déplacement 6 m, Discrétion et Athlétisme défavorisés |
| **Bouclier de tranchée** | +2 | Seulement contre les attaques venant de face ; occupe une main |

---

## 7. Les Blessures

### La réserve de Blessures

Chaque personnage a un nombre de **Blessures égal à sa Chair** (de 8 à 14). Les dégâts subis s'en retirent.

### Blessure grave

Un personnage subit une **Blessure grave** quand :
- un seul coup lui retire **6 Blessures ou plus** ;
- **ou** ses Blessures tombent à 0.

Il lance alors **1d6** :

| d6 | Blessure grave | Effet jusqu'aux soins à l'arrière |
|---|---|---|
| 1 | **Commotion** | Jets d'Esprit défavorisés |
| 2 | **Bras touché** | Pas d'arme à deux mains ; jets de Chair défavorisés |
| 3 | **Jambe touchée** | Déplacement réduit de moitié |
| 4 | **Éclat dans l'œil** | Tir et Vigilance défavorisés |
| 5 | **Hémorragie** | Perd 1 Blessure au début de chacun de ses tours, jusqu'à un jet de Médecine réussi |
| 6 | **Mutilation** | Une séquelle **permanente** au choix du MJ (doigt, oreille, visage…) ; Nerfs −1 cran |

Chaque Blessure grave entraîne aussi un **test d'usure de Nerfs**, et le personnage passe en **phase lente**.

### Hors de combat

À **0 Blessure**, le personnage est **hors de combat** : il ne peut plus agir. Au début de chacun de ses tours, il fait un **jet de Mort**, un jet de **Chair** :
- **Réussite :** il tient bon, et rien ne change.
- **Échec :** on coche une case. À la **troisième case cochée**, il meurt.

Il peut **prier** ou **pactiser** sur son jet de Mort. C'est souvent là que le Chapelet se vide.

Un allié qui réussit un jet de **Médecine** sur lui le **stabilise** : il n'a plus de jet de Mort à faire et récupère **1d4 Blessures**.

### Se soigner

| Situation | Effet |
|---|---|
| **Soigner** en combat (action, jet de Médecine) | Le patient récupère **1d6 Blessures**. Une seule fois par patient et par scène. |
| **Morphine** | Ignore les effets d'une Blessure grave jusqu'à la fin de la scène. |
| **Repos** à l'abri (une nuit) | Récupère toutes ses Blessures, sauf s'il souffre encore d'une Blessure grave non soignée. |
| **Soins à l'arrière** | Efface les Blessures graves (sauf les séquelles permanentes). |

---

## 8. La peur et la panique

Un personnage fait un **test d'usure de Nerfs** quand :
- il subit une **Blessure grave** ;
- un **allié tombe hors de combat** sous ses yeux ;
- il voit pour la première fois une créature dotée du trait **Effroi** ;
- le MJ le juge nécessaire (bombardement, gaz, scène atroce).

### Paniqué

Quand ses **Nerfs sont épuisés**, le personnage devient **paniqué** et passe en **phase lente**. À chacun de ses tours, il lance **1d6** :

| d6 | Réaction |
|---|---|
| 1–2 | **Fuite :** il utilise tout son tour pour s'éloigner du danger. |
| 3–4 | **Terré :** il ne peut que se mettre à couvert. |
| 5–6 | **Furie :** il charge l'ennemi le plus proche, sans réfléchir. |

**Se reprendre :** au lieu de lancer le d6, il peut tenter un jet d'**Âme** (Endurcissement ou Volonté s'appliquent). Un allié peut aussi le **rallier** avec un jet de Commandement. En cas de réussite, il n'est plus paniqué, mais ses Nerfs restent épuisés : au prochain test de Nerfs, il paniquera de nouveau.

---

## 9. Le terrain

| Terrain | Effet |
|---|---|
| **Boue** | Déplacement réduit de moitié |
| **Barbelés** | Pour traverser : jet d'Athlétisme, ou de Coup de main avec des cisailles. Échec : **immobilisé** et 1d4 dégâts |
| **Cratère** | Couvert léger ; en sortir coûte 3 m de déplacement |
| **Tranchée** | Couvert lourd contre les tirs venant de l'extérieur ; aucun couvert pour qui est dedans face à qui est dedans |
| **Fumée** | Couvert léger ; bloque la vue au-delà de 6 m |
| **Nuit** | Tir défavorisé au-delà de 20 m (sauf éclairage) |
| **Gaz** | Sans masque : 1d6 dégâts par tour, sans Protection, et test de Nerfs. Avec masque : Vigilance et Tir défavorisés |

---

## 10. Les ennemis

Pour que le MJ joue vite, les ennemis ont une **fiche courte**. Ils ne lancent qu'un seul score pour tout ce qu'ils font : la **Menace**.

| Valeur | Ce qu'elle indique |
|---|---|
| **Menace** | Le score à atteindre au d20 pour toutes leurs actions |
| **Blessures** | Leur réserve de Blessures |
| **Dégâts** | Leur attaque principale |
| **Protection** | Ce qu'ils retranchent aux dégâts reçus |
| **Déplacement** | En mètres |
| **Traits** | Leurs règles spéciales |

### Traits courants

| Trait | Effet |
|---|---|
| **Effroi** | La première fois qu'on la voit, la créature provoque un test d'usure de Nerfs. |
| **Démon** | Insensible à la peur. Les armes *Sacrées* et l'eau bénite lui infligent des dégâts doublés. |
| **Insensible** | Ne subit pas de Blessure grave ; tombe simplement à 0. |
| **Meute** | Favorisé s'il attaque une cible déjà au contact d'un allié. |
| **Chef** | Les alliés à 9 m ou moins sont favorisés à leur premier jet de chaque combat. |
| **Grand** | Occupe 3 × 3 cases ; ne peut pas se mettre à couvert. |
| **Rapide** | Déplacement de 15 m. |

### Bestiaire de test

| Ennemi | Menace | Blessures | Dégâts | Protection | Déplacement | Traits |
|---|---|---|---|---|---|---|
| **Hérétique de tranchée** | 10 | 8 | Fusil d8 (50/200 m) ou baïonnette d6 | 1 | 9 m | — |
| **Sous-officier hérétique** | 12 | 11 | Pistolet d6, sabre d8 | 2 | 9 m | Chef |
| **Chien de l'Enfer** | 11 | 6 | Morsure d6 | 0 | 15 m | Rapide, Meute, Démon |
| **Mort de tranchée** | 9 | 10 | Griffes d6 | 0 | 6 m | Insensible, Effroi |
| **Diablotin** | 12 | 10 | Griffes d8 | 2 | 9 m | Démon, Effroi |
| **Bête de l'abîme** | 14 | 30 | Écrasement d12 | 4 | 9 m | Démon, Effroi, Grand |

---

## Exemple de tour

Marcel (Nerf 12) et Lucien (Nerf 10) sont pris sous le feu de deux hérétiques retranchés à 60 m derrière un parapet.

**Initiative.** Marcel réussit son jet de Nerf : **phase rapide** (3). Lucien échoue : **phase lente** (1). Les hérétiques jouent en phase 2.

**Phase rapide.** Marcel rampe de 3 m vers un cratère (déplacement), puis **se met à couvert** (action) : jusqu'à son prochain tour, son couvert léger devient lourd.

**Phase ennemie.** Le premier hérétique tire sur Marcel : Menace 10, couvert lourd −5, portée longue −2 → il doit faire **3 ou moins**. Il fait 14 : raté. Le second tire sur Lucien, à découvert, à 60 m : 10 − 2 = **8**. Il fait 6 : touché. Le fusil inflige d8 = 5, moins le casque de Lucien (1) : **4 Blessures**. Lucien passe de 10 à 6.

**Phase lente.** Lucien plonge dans une tranchée (déplacement) puis **vise** (action). Au prochain tour, son tir sera favorisé.

---

## Récapitulatif

- **Échelle :** 1 case = 1,5 m ; toutes les distances en mètres.
- **Initiative :** un seul jet de Nerf par combat. Réussite → phase rapide (3), ennemis (2), échec → phase lente (1). On peut la reprendre (action + nouveau jet) ou la perdre (Blessure grave, panique).
- **Tour :** 1 déplacement (9 m) + 1 action, ou 2 déplacements. Réaction *Plonger* une fois par tour de jeu.
- **Tir :** Tir + couvert (0 / −2 / −5) + portée (0 / −2), puis test d'usure de Munitions.
- **Mêlée :** jet en opposition, Mêlée contre Mêlée ou Esquive.
- **Dégâts :** dé de l'arme − Protection.
- **Blessures = Chair.** Blessure grave sur 6+ en un coup ou à 0. Hors de combat : jet de Mort sous Chair, mort à 3 échecs.
- **Nerfs épuisés :** paniqué (fuite, terré, furie).
- **Ennemis :** une seule valeur, la Menace, pour toutes leurs actions.
