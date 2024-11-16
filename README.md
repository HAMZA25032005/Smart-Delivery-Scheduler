# Smart Delivery Scheduler 🚚📦

## Description

Smart Delivery Scheduler est un projet d’optimisation logistique conçu pour résoudre le problème des tournées de véhicules avec contraintes de fenêtres temporelles (VRPTW). Ce projet vise à améliorer la planification des livraisons pour minimiser les temps de trajet tout en respectant les contraintes temporelles et opérationnelles.

Ce projet utilise des approches combinant des heuristiques et des métaheuristiques avancées pour garantir des solutions optimales ou quasi-optimales dans des contextes logistiques complexes.

## Objectifs du Projet 🎯

- **Planification optimisée des trajets**: Concevoir les itinéraires les plus courts pour une flotte de véhicules tout en couvrant l'ensemble des points de livraison.
- **Respect des contraintes temporelles**: Prendre en compte les fenêtres de temps spécifiques pour chaque client ⏰.
- **Minimisation du temps total de livraison**: Réduire les coûts opérationnels et le temps global des tournées 💸.

## Fonctionnalités Principales 🔧

### 1. Modélisation du problème VRPTW 🗺️
- Point de départ et retour au dépôt.
- Respect des fenêtres horaires pour chaque client.
- Optimisation des trajets pour une flotte donnée.

### 2. Solution initiale avec heuristiques de voisinage 🛠️
- Génération d’une première solution pour structurer les tournées.
- Réorganisation locale des trajets pour une amélioration rapide.

### 3. Optimisation par métaheuristiques 🚀
- Utilisation de l’algorithme **Tabou Search** pour explorer globalement l’espace des solutions.
- Recherche d’un compromis entre précision et temps de calcul.

### 4. Analyse des performances 📊
- Visualisation des résultats sous forme de graphiques :
  - Impact du nombre de véhicules et de clients sur les temps de trajet.
  - Influence de la taille de la liste Tabou sur les performances.
  - Évolution des performances en fonction des itérations.

## Approche Technique ⚙️

### Données d'entrée 📍
- Instances de villes générées aléatoirement avec coordonnées.
- Différents nombres de véhicules (k).
- Contraintes de fenêtres temporelles.

### Processus Méthodologique 🧭
- Génération de données aléatoires pour modéliser les points de livraison.
- Application d'une heuristique de voisinage pour créer une solution initiale.
- Optimisation de la solution initiale via l’algorithme Tabou Search.
- Analyse des résultats et visualisation des performances à l’aide de graphiques.

### Résultats Attendues 🏆
- Réduction des temps de trajet globaux pour des flottes allant de 2 à 10 véhicules.
- Identification des paramètres optimaux pour la taille de la liste Tabou et le nombre d’itérations.
- Visualisation claire des tendances de performances pour différentes tailles de problèmes.

## Technologies Utilisées 💻
- **Python**: Développement des algorithmes.
- **Bibliothèques Python**:
  - **NumPy** et **Pandas**: Manipulation et analyse des données.
  - **Matplotlib**: Visualisation des résultats.

