# TurnoverRiskAnalysis
Développement d’un modèle de prédiction des départs des salariés pour aider les entreprises à réduire le turnover et planifier les stratégies de rétention des talents. Le projet utilise des algorithmes de classification supervisée (SVC) pour anticiper les risques de départ et identifier les indicateurs clés.

## Description
Ce projet vise à prédire les départs des collaborateurs d’une entreprise afin de diminuer les coûts liés au turnover et de mieux planifier la rétention des talents. Grâce à un algorithme de classification supervisée (SVC), le modèle identifie les salariés à risque et les indicateurs clés associés à leur départ.

## Contenu du projet
1. **Données** :  
   - Jeu de données fictif d'IBM contenant 35 variables quantitatives et qualitatives décrivant 1450 employés.  
   - Données nettoyées et standardisées pour améliorer la qualité des prédictions.  

2. **Analyse exploratoire** :  
   - Étude des caractéristiques des salariés, de leur satisfaction et des facteurs influençant leur départ.  
   - Identification des variables importantes comme l'ancienneté, la rémunération et les heures supplémentaires.  

3. **Modélisation** :  
   - Algorithmes testés : régression logistique, SVC, Random Forest, etc.  
   - Modèle final : **SVC** (classification par vecteurs supports) avec une précision de 75 % et un rappel pour les départs de 72 %.  

4. **Résultats** :  
   - Probabilité de départ calculée pour chaque salarié.  
   - 145 salariés identifiés comme étant à très haut risque de départ (>70 % de probabilité).  

5. **Recommandations** :  
   - Ajuster les politiques RH pour limiter les heures supplémentaires et équilibrer la fréquence des voyages d'affaires.  
   - Mettre en place des plans de rétention pour les employés à risque élevé.  
   - Recueillir des données supplémentaires pour améliorer la précision du modèle.  

## Technologies utilisées
- **Python** : pandas, scikit-learn, seaborn, matplotlib.  
- **Modèle retenu** : SVC (Support Vector Classifier).  

## Prochaines étapes
- Étendre l’analyse à des données sur plusieurs années.  
- Intégrer d'autres facteurs explicatifs pour enrichir le modèle.  
