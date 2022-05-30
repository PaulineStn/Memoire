# Analyse de la diversité du virus SARS-CoV-2 dans les eaux usées par des approches de séquençage

### Mémoire M2
*Annexe*


### Comptes rendus de séquençage

Comptes-rendus générés pour Nice (Station d'épuration et aéroport) et pour l'Europe.
Les sites étudiés en Europe sont : 
-Montpellier, Cergy (France), 
-Hof, Rosenthal, Braunschweig (Allemagne),
-Prague (République Tchèque), 
-Rome, Venise (Italie), 
-Zaragosa (Espagne), 
-Edinburgh (Royaume-Uni).

Dans les comptes-rendus générés, les deux premières parties "Samples" et "Parameters" contiennent le nom, la date des échantillons et les paramètres utilisés pour l’analyse (dont la profondeur minimale, la fréquence minimale). Le paramètre Range correspond à la région du génome et all signifie que les Heatmaps sont construites avec les variations de tout le génome.

Les différentes analyses disponibles sur le fichier sont les suivantes : 
- Heatmap triée selon la position de la variation et selon la date de prélèvement des échantillons,
- Heatmap en cluster, 
- Diagramme de couverture du génome selon la position, 
- Histogramme de la distribution des variants,
- Tableau de données de fréquence pour les mutations caractéristiques des variants.



### Amplification de la région Spike
La séquence et la position des amorces utilisées est disponibles au format .bed

MN908947.3 correspond à la référence Genbank de SARS-CoV-2
Pool A (1Kb)
Pool B (1Kb)
Pool C (2Kb)
Pool D (4Kb)

### Langages utilisés
Bash (Script Bash) : analyse des données de séquençage
Python (code Python) : représentation graphique des données


### Calcul des variants
Liste de mutations utilisées pour calculer les proportions des variants circulants 

### Auteurs
Pauline Steichen et Rainer Waldmann
