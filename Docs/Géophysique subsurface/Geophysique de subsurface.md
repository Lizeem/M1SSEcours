# Méthodes de prospection géophysique

- Application d'un ensemble de méthodes physiques : gravimétrie, électricité, magnétisme, sismique afin d'approcher les propriétés et / ou la structure du massif
- Mesure d'une grandeur physique et de leur variation
- Méthode indirectes et non-destructives de reconnaissance et d'auscultation
- Mesure volumique : technique aisée et peu coûteuse -> Etape préliminaire de nombreuses études (dégrossissage structural, repérage d'anomalie)

![Tableau récapitulatif des différents types de techniques](Images/tableau_recapitulatif.png)

Pour une polarisation spontanée électrique, il n'y a pas de variation de fréquence cumulée. Son unité est le mV.

Haute fréquence : période très petite (f: 1/T)

investigation géophysique -> acquisition de données 1,2 ou 3D :

- **profil** (1D) : déplacement au sol et profondeur fixée
- **log** (1D) : courbe en fonction de la profondeur
- **carte** (2D) : déplacement au sol selon x ou y (surface du sol)
- **coupe** (2D) : déplacement au sol selon une direction et une profondeur
- **bloc diagramme** (3D)

## I) Polarisation spontanée électrique 

### Introduction

Le géophysicien s'intéresse aux **propriétés électriques** des sols (inclus sol végétal) et des roches : **caractérisation et imagerie du sous-sol**. Spontané : polarisation naturelle

Propriété électrique : 

- activité électrochimique (base de la **PS**)
- **résistivité** : difficulté avec laquelle on peut faire passer un courant électrique dans la roche, contraire de la conduction, non naturel. L'unité est Ωm.
- constante diélectrique : capacité des roches à emmagasiner de l'énergié et à la rstituer, à la base de la **polarisation provoquée**

Accès à des profondeurs d'investigation élevées : structure invisible à d'autres méthodes

Point commun de ces méthodes : ***mesure potentiel électrique***

Différence entre les méthodes électriques et électromagnétisme : façon de générer les courants électriques. En électromagnétisme c'est le champ électrique fonction d'une fréquence va générer un champ électrique

Associée à des mécanismes de polarisation de charges électriques dans le milieu poreux. 

- phénomène physique qui correspond à la génération de potentiels électriques dans les sols sans influence humaine
- terme utilisé pour désigner la méthode de prospection basée sur la mesure du phénomène

La PS est causée par l'activité électrochimique ou mécanique : altération des sulfures, variation de la composition des roches aux contacts géologiques, activité bioélectrique du matériel organique, corrosion, gradients thermiques et pression dans les fluides souterrains.

Principe de mesure passive. Les données de potentiel spontanée sont mesurés en surface, on va ensuite pouvoir créer des modèles de circulation en profondeur. On mesure la **différence** de potentiel d'origine naturelle entre deux points du sol. Les courants électriques induits liés à des phénomènes **électrocinétiques** et **électrochimiques**.

En PS, on a uniquement une mesure de voltmètre (mV à 1 ou 2 V)

Deux phénomènes : 

- **phénomènes électrocinétiques** : mouvement de fluide, infiltration de l'eau de pluie écoulement des nappes, ***Ek***
- **phénomènes électrochimique** : 2 formation en surface contact, 

    - "solutions" à concentration différente (argiles et sables aquifères par exemple) -> phénomènes "**osmotiques**" 
    - **présence d'une masse conductrice** (amas de minéral métalliques ou schistes graphiteux) partiellement enfouie sous  le niveau hydrostatique

### A) Sources naturelles du potentiel électrique

#### 1. Potentiel électrocinétique 

Observé lorsqu'une solution de **résistivité ρ** et de **viscosité η** traverse un matériau poreux, d'origine mécanique il se produit généralement sous influence de la gravité.

![Formule électrocinétique](Images/electrocinétique.png)

Ek généralement d'effet négligeable, sauf pour les topographies marquées sur la conduction hydraulique de l'eau d'imbibition, ou que la végétation agit suffisamment sur le drainage de l'eau souterraine. Plus le terrain sera pentu, plus la circulation des électrons sera grande -> anomalie électrocinétique en fonction de la topographie.

Mouvement de fluide : pompages et infiltrations

![Pompages et infiltrations](Images/anomalies.png)

Migration de fluides :

- anomalies + -> flux de fluide en subsurface, zones de décharges, pompages
- anomalies - -> zones d'infiltrations

Facteurs lithologiques et structuraux :

- anomalies + -> zones très argileuses
- anomalies - -> zones d'accumulation de débris grossiers
- changement brusque de magnitude ou de signe -> contact géologique probable
- anomales - dans une roche homogène -> fractures


#### 2. Potentiel de diffusion

De nature chimique, f(T°C) il est dû à la différence de mobilité des ions dans une solution de concentration variable.  L'équilibre ne peut se faire également de part et d'autre et un ΔV est généré. 

![Potentiel de diffusion](Images/potentiel-de-diffusion.png)

Quand on a deux formations en électrochimie, on a deux types de formations différentes, Ec va être fonction de la température et des concentrations de fluide. Si les concentrations sont bien marqués, on aura une valeur élevée.

#### 3. Potentiel de Nernst

Lorsque deux électrodes métalliques sont immergées dans une solution dont la concentration est différente pour les deux électrodes, il y a un ΔV de crée. Il s'agit d'un phénomène chimique (les porteurs de charges sont des ions)

![Potentiel de Nernst](Images/potentiel-de-nernst.png)

Ed et Es définissent le **potentiel de membrane**

#### 4. Potentiel de contact électrolytique

Lorsque 2 électrodes de métaux différents sont introduites dans une solution électrolytique.  

Combinaison des potentiels de diffusion, Nernst et contact ≡ **potentiels de minéralisation** => anomalies souvent bien distinctes du bruit de fond et associées à des métaux.  ⇒ **détection de gisements métallifères par mesure de ΔV à la surface**.

#### 4. Autres sources  

- variations de T°C: un effet mineur (sauf volcanisme) 
- corrosion métallique (tuyaux, câbles, carcasses métalliques) : ΔV locaux 
- courants telluriques (induction de l'ionosphère, explosion nucléaire, tempêtes électriques) pas stables dans le temps 
- effet bioélectrique observé à la frontière entre clairière et forêt : eau souterraine drainée par les racines des arbres => ΔV pouvant être confondus avec ceux produits par les sulfures (de l'ordre de quelque centaines de mV)

### B) Le potentiel de minéralisation

Les porteurs de charge sont des électrons Associé avec les sulfures métalliques, le graphite et certains oxydes métalliques telle que la magnétite.

L'anomalie au dessus des sulfures métalliques (pyrite, chalcopyrite, pyrrhotite, sphalérite, galène, graphite) de quelques mV à 1 V, 200 mV étant considérée comme une bonne anomalie.  Les potentiels observés sont généralement négatifs, relativement stables dans le temps.  Possibilité de distinguer le potentiel de minéralisation des bruits de fond dus à toutes les autres causes (tendance à s’annuler). On peut s'en servir comme méthode d'exploration car ΔV sont stables dans le temps et les valeurs sont 1V au dessus de la minéralisation.

![Flux du courant](Images/flux-courant-total.png)

L : Propriétés de transports des ions, de l’eau porale et des électrons 
∇μ : gradients de potentiels chimiques respectifs 

### C) La PS comme méthode de prospection

Attention au choix des électrodes : performance dépend de leur polarisation et de leur dérive.  

**Polarisation** = potentiel mesuré entre une paire d'électrode en l'absence d'une source externe = effet dû uniquement à l'équipement qui peut perturber la mesure.  

**Dérive** = variation dans le temps de la polarisation (éviter électrodes métalliques et privilégier les «pots-poreux », plus chers, mais beaucoup moins polarisables).  

Sources de bruit possible : Induction magnétotellurique, potentiel thermo-électrique, potentiel bioélectrique, potentiel de diffusion (ou potentiel de membrane), les sources anthropiques

![PS](Images/PS.png)

### D) Les différentes méthodes d'acquisition

Technique du gradient : la paire d'électrodes se déplace simultanément, d'un point de mesure à l'autre : mesures le long d'une ligne => profil. Plusieurs profils => surface statique.  

Méthode rapide mais il faut additionner toutes les valeurs pour obtenir ΔV, les erreurs de zéro s'additionnent et il faut veiller à garder toujours la même polarité des électrodes. 

Technique Base-Fixe : on ne déplace qu'une électrode tout en gardant l'autre fixe. L'électrode mobile est déplacée de façon à couvrir la surface d'investigation. 

- Avantages : lecture directe car les mesures sont faites avec une même référence, et les erreurs de zéro entre les deux électrodes ne s'accumulent pas. 
- Désavantage principal : manipulation des fils fastidieuse.

### E) Interprétation des résultats 

Obtention de contours ou de profils.  

- anomalie située directement au dessus du corps la générant, ou déplacée par un effet topographique.  
- interprétation surtout qualitative ; idée du pendage avec le gradient des courbes de contours.  
- forme du corps anomal indiquée par la forme des contours 

### F) Applications de la polarisation spontanée

#### 1. Application à l'hydrologie

Le champ électrique, présent naturellement dans le sous-sol, est influencé par la géométrie de la source ainsi que par la distribution de la résistivité électrique du milieu => mesure ayant une origine dynamique liée à l’écoulement de l’eau 

Intérêt en hydrologie des mesures de PS : 

1. l’identification de la direction et de l’intensité des mouvements de fluides dans le sous sol 
2. la délimitation de systèmes hydrothermaux 
3. le suivi de panache de contamination 
 
Développements d’électrodes stables dans le temps, et outils de filtrages. Avantages : méthode non invasive, faible coût et facile à mettre en place, large surface d’investigation en peu de temps (=> 1000 mesures/j) 

PS = électro-diffusion + phénomène d'oxydo-réduction + **électro-filtration**

Electro-filtration : Excès de charges transporté par un écoulement du fluide dans le milieu poreux crée une source de courant d’origine électrocinétique  => Circulations hydriques à l’origine des signaux de PS associés aux essais de pompage / infiltration 

#### 2. Application à des panaches de contaminations

Le phénomène électro-rédox dans les panaches de contamination peut-être assimilé au phénomène d'oxydo-réduction rencontrés dans les gisements de minerai. Mais mécanisme de transfert de charges reste encore mal compris : rôle majeur probable des **bactéries**?

Les mécanismes de dégradation de la Matière Organique : dégradation aérobie, hydrolyse, acidogenèse, méthanogenèse, maturation

#### 3. Applications en volcanologie

Acide sulfurique H2S, dioxyde de soufre SO2 et CO2 : composants principaux des gaz volcaniques Les réactions chimiques entre ces gaz et les roches peuvent contrôler l’environnement chimique des volcans et des champs géothermiques avoisinants. Génération des ions sulfates ?? 

1. Oxydation par l’oxygène dissout dans l’eau de percolation :  H2S + 2O2↔H2SO4Mais 2O2 très faible, n’explique pas les formations des ions sulfates dans les sources chaudes 
2. Oxydation par l’oxygène de l’air : Vitesse trop lente 
3. Oxydation par des composés ferriques dans les roches : H2O + SO2↔H2SO3. Ce dernier réagit avec des ions ferriques, pour former l’ion sulfate

### Sondage électrique

Analyse de la résistivité apparente du sous sol mesurée par un dispositif quadripôle symétrique (ABMN) pour une succession d'écartement des électrodes AB

-> propagation d'un courant électrique dans le sol

Loi d'Ohm : U = RI

Pour 100m, on peut avoir une profondeur d'investigation entre 25m (conducteur) et 10m (résistant) en fonction de la résistivité du sol

### Trainée électrique

analyse de la résistivité apparente du sous-sol par un quadripôle symétrique ABMN de dimension constante, traîné le long d'un profil -> dimension du dispositif (fixe) induit une profondeur d'investigation à peu près constante

