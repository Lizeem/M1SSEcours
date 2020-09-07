# Initiation à un Système d'Information Géographique

## Un SIG ça sert à quoi au juste ?

Les SIG sont des **outils** informatiques qui permettent de manipuler des **données géoréférencées**. Les opérations qui peuvent être réalisées avec un SIG comprennent tout d'abord 4 fonctionnalités de base :

- la **saisie** (**numérisation**) des données
- le **stockage** (base de données graphiques et attributaires)
- l'**analyse** (**requête**, modélisation, simulation)
- la **sortie** (production de cartes, tableaux et graphiques, exportation et transfert de fichiers).

Le SIG permet :

- de gérer une multitude d'informations de tous types (images satellitaires, photos aériennes, cartes, données chiffrées, bases de données...).
- de les mettre à jour très rapidement, de faire des requêtes (classiques et spatiales).
- de générer de nouvelles couches d'informations par le biais de ces croisements.

## Quel type d'information?

Le SIG est d'abord un système de recueil d'informations liées spatialement (affectation du sol, occupation du sol, types de végétations, pédologie, altitudes..) et qui permet la superposition de diverses couches d'informations dans un but d'analyse.

## Notion à définir

**Cartographie** : discipline qui englobe la conception, la production, la diffusion et l'étude des cartes. La cartographie est aussi le terme utilisé pour désigner la **représentation spatiale** en elle-même, soit la carte. 

**Géodésie** (géoïde, ellipsoïde, système géodésiques) : science qui est désignée à l'origine pour le tracé des cartes

**Systèmes de projections, systèmes de coordonnées**

## Historique de la cartographie

Cartographie : besoin de **reconnaître** les lieux habités et parcourus. Information sur les **distances**, les **directions**, le **nom** de lieux. D'abord **descriptive** (notions écrites et dessins sommaires) puis mathématiques, orientation des objets et lien avec des observations de la voûte celeste.

Ératosthène : premières estimations du rayon terrestre. Un des premiers à créer la projection plate carrée.

Période romaine : Ptolémée (90-168), grec Alexandrie, géomètre, astronome et géographe. Développe la projection dite Homéotère : les parallèles représentées par des cercles concentriques et méridiens par des courbes tracées points par points. 

Les temps modernes (Moyen-Age): Al Edrisi, géographe arabe compléta l'oeuvre de Ptolémée sur les routes empruntées par les commerçants arabes.

Waldseemüller : cartographie en fuseaux en 1507

Planisphères -> terres nouvellement découvertes très déformées par la projection plate carrée

Mercator : projection à latitude croissantes, recueil de 107 cartes gravées : **Altas** (géant légendaire qui portait le monde sur ses épaules)

XVIII eme : cartographie de l'Europe réalisée, observations astronomiques (contours des royaumes), projections : tous les types de cavenas essayés et construits géométriquement (Lambert, Bonne, Gauss), réalisation rigoureuse des propriétés de conformité et d'équivalence.

Cependant, il y a eu des querelles

- théorie de Newton (terre aplatie aux pôles)
- théorie de Cassini (terre aplatie à l'équateur)

Académie des Sciences : expéditions de mesure des arcs des méridiens terrestres en Laponie et au Pérou pour connaître la vraie hypothèse.

XIXe siècle : développement de nombreux réseaux géodésiques, création d'ellipsoïdes, prise de conscience Terre =/= ellipsoïde, réseaux nationaux = ne concordent pas entre eux. 1886 : création de l'Association Internationale de Géodésie

Mesures de pesanteur : déviation relative à la verticale. Définition des surfaces équipotentielles de niveau (perpendiculaires en tout point à la verticale locale).

XXe : mesures électromagnétiques, calcul et informatique, gravimétrie (astrogéodésie, méthodes spatiales, affiner la connaissance de la forme de la terre -> géoïde).

Géodésie spatiale : réseaux qui entourent la Terre, positionnement absolu et relatif en coordonnées géocentriques.

Géodésie : base scientifique de l'étude de la physique du globe, étude des mouvements et déformations de la croûte terrestre.

## Géodésie

La géodésie est l'étude mathématique de la forme et des dimensions de la Terre et l'étude de son champ de pesanteur

**Géoïde** : surface équipotentielle de pesanteur (égal _**g**_) proche du niveau moyen des mers.

**Ellipsoïde** : modèle mathématique simple qui représente le mieux la géométrie de la Terre.

L'altitude est définie par rapport au niveau de la mer. Il n'est pas forcément égal à la hauteur ellipsoïdale dont la hauteur est donnée par les systèmes satellites.

## Systèmes géodésiques

La géodésie est la science de la forme et de la dimension de la Terre et de son champ de pesanteur.

Localisation d'un objet -> **référentiel géodésique**, repère affine dont le centre est proche du centre des masses de la terre. 2e axes : plan de l'équateur. 3e axe proche de l'axe de rotation des pôles.

Réalisation numérique du référentiel : **système géodésique**

Méridien : Nord-Sud

Coordonnées géodésique : valeurs relatives. Dépendent d'un modèle théorique choisi

Dans un système de référence géodésique, un point terrestre est quasiment fixe bien que soumis à de faibles mouvements (marées terrestres, mouvements tectoniques, surcharge océanique).

**Ellipsoïde de référence** : position calculée par rapport à une surface de référence arbitraire, forme élémentaire de la Terre : une sphère aplatie aux deux pôles

**Altitude du satellite** : au dessus de l'ellipsoïde de référence = distance S

**Niveau des océans** : hauteur SSH = mesure par rapport à l'ellipsoïde de référence.

**Géoïde** : Surface irrégulière correspondant au niveau moyen des mers et qui constitue par convention la surface de référence altimétrique ou la surface d'altitude zéro.

## Réseaux géodésiques

Réseau = ensemble de points physiquement liées à la croûte terrestre (bornes, piliers...) dont on décrit la position par des coordonnées estimées et leurs variations.

Différents types de réseaux :

- planimétriques
- nivellement
- tridimensionnel géocentriques

A partir de ces bornes, on peut déterminer les coordonnées de n'importe quel point de triangulation.

## La nouvelle Triangulation de la France Système local

Objectif : réalisation de la cartographie nationale à moyenne échelle. Triangulation similaire à celles de Cassini et des Ingénieurs Géographes. Sue le terrain, réseau géodésique hiérarchisé avec plus de 65 000 points référencés

## WGS84 système spatial

Mis au pont par le département de la défense des USA à partir d'observations satellites

## Le systèmes de coordonnées

### Coordonnées planes

Représentation plane ou projection pour :

- ne pas se promener avec un globe sous le bras
- avoir des valeurs métriques plus exploitables que des valeurs angulaires
- rendre plus facile l'évaluation des distances 
- mais : déformations

Possibilité de conserver : 

- les surfaces (projection équivalentes)
- les angles (projections conformes : les plus utilisées)
- ni les angles, ni les surfaces (projections aphylactiques)

Projection équidistante conserve les distances à partir d'un point donné mais aucune projection ne peut conserver toutes les distances -> notion de module linéaire et d'altération linéaire.

## Les systèmes de projection

**Projection cylindrique** : la surface de projection est un cylindre tangent ou sécant au modèle de la Terre. Les projections UTM, Gauss utilisent ce type de projection. 

**Projection conique** : la surface de projection est un cône tangent ou sécant. Les projections Lambert et Lambert-93 utilisent ce type de projection.

**Projection azimutale** : le plan lui-même est tangent au modèle de la terre. Le stéréographie polaire,...). Les intersections entre le plan de projection et l'ellipsoïde forment des lignes appelées automécoïques. 

Pour la France, projection conique Lambert, on divise la France en 4 parties.

Une image est une matrice de chiffres (classiquement de 0 à 255) à laquelle on applique une palette de couleur afin de la visualiser. A l'opposé un polygone n'est défini que par ses sommets.










