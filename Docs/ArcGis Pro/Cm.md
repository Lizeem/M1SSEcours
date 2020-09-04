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

## Notion à définir

Cartographie

Géodésie : géoïde, ellipsoïde, système géodésiques

Systèmes de projections, systèmes de coordonnées

## Historique de la cartographie

Cartographie : besoin de **reconnaître** les lieux habités et parcourus. Information sur les **distances**, les **directions**, le **nom** de lieux. D'abord **descriptive** (notions écrites et dessins sommaires) puis mathématiques.

Ératosthène : premières estimations du rayon terrestre. Un des premiers à créer la projection plate carrée.

Période romaine : Ptolémée (90-168), grec Alexandrie, géomètre, astronome et géographe 

Les temps modernes : Al Edrisi, géographe arabe compléta l'oeuvre de Ptolémée

Waldseemüller : cartographie en fuseaux en 1507

Planisfères -> terres nouvellement découvertes très déformées par la projection plate carrée

Mercator : projection à latitude croissantes, recueil de 107 cartes gravées : **Altas** (géant légendaire qui portait le monde sur ses épaules)

XVIII eme : cartographie de l'Europe réalisée, observations astronomiques -> contours des royaumes, projections : tous les types de cavenas essayés et construites géométriquement (Lambert, Bonne, Gauss).

Cependant, il y a eu des querelles

- théorie de Newton (terre aplatie aux pôles)
- théorie de Cassini (terre aplatie à l'équateur)

Académie des Sciences : expéditions de mesure des arcs des méridiens terrestres en Laponie et au Pérou.

XIXe siècle : développement de nombreux réseaux géodésiques, création d'éllipsoïdes, prise de conscience Terre =/= ellipsoïde, réseaux nationaux = ne concordent pas entre eux. 1886 : Création de l'Association Internationale de Géodésie

Mesures de pesanteur : déviation relative à la verticale

XXe : mesures électromagnétiques, calcul et informatique, gravimétrie

- astrogéodésie 
- méthodes spatiales
- affiner la connaissance de la forme de la terre : le géoïde

Géodésie spatiale : réseaux qui entourent la Terre

## Géodésie

La géodésie est l'étude mathématique de la forme et des dimensions de la Terre et l'étude de son champ de pesanteur

**Géoïde** : surface équipotentielle de pesanteur (égal **g**) proche du niveau moyen des mers.

**Ellipsoïde** : modèle mathématique simple qui représente le mieux la géométrie de la Terre.

L'altitude est définie par rapport au niveau de la mer. Il n'est pas forcément égal à la hauteur ellipsoïdale.

## Systèmes géodésiques

La géodésie est la science de la forme et de la dimension de la Terre et de son champ de pesanteur.

Localisation d'un objet -> **référentiel géodésique**

Réalisation numérique du référentiel : **système géodésique**

Méridien : Nord-Sud

Coordonnées géodésique : valeurs relatives. Dépendent d'un modèle théorique choisi

Dans un système de référence géodésique, un point terrestre est quasiment fixe bien que soumis à de faibles mouvements.

Ellipsoïde de référence : position calculée par rapport à une surface de référence arbitraire, forme élémentaire de la Terre : une sphère aplatie aux deux pôles

Altitude du satellite : au dessus de l'ellipsoïde de référence = distance S

Niveau des océans : hauteur SSH = mesure par rapport à l'ellipsoïde de référence.

Géoïde : Surface irrégulière correspondant au niveau moyen des mers et qui constitue par par convention la surface d'altitude zéro.

## Réseaux géodésiques

Réseau = ensemble de points physiquement liées à la croûte terrestre (bornes, piliers...) dont on décrit la position par des coordonnées estimées et leurs variations.

Différents types de réseaux :

- planimétriques
- nivellement
- tridimensionnel géocentré

## La nouvelle Triangulation de la France Système local

Objectif : réalisation de la cartographie nationale à moyenne échelle. Triangulation similaire à celles de Cassini et des Ingénieurs Géographes.

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
- les angles

## Les systèmes de projection

Projection cylindrique : La surface de projection est un cylindre tangent ou sécant au modèle de la Terre 

Projection conique : La surface de projection est un cône tangent ou sécant. Les projections Lambert et Lambert-93 utilisent ce type de projection.

Projections azimutales : projection sur un plan, utiliser pour avoir une projection sur un pôle.

Pour la France, projection conique Lambert, on divise la France en 4 parties.

Une image est une matrice de chiffres (classiquement de 0 à 255) à laquelle on applique une palette de couleur afin de la visualiser. A l'opposé un polygone n'est défini que par ses sommets.










