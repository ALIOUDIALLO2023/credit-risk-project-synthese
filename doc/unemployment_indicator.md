# Indicateur macroéconomique : Taux de chômage (% de la population active)

##  Description générale
- **Nom de l’indicateur** : Unemployment, total (% of total labor force)  
- **Source principale** : International Labour Organization (ILO), via World Development Indicators (WDI) – Banque mondiale  
- **Couverture** : 209 économies  
- **Période disponible** : 1960 – 2023  
- **Fréquence** : Annuelle  
- **Unité de mesure** : Pourcentage de la population active  

##  Définition
Le taux de chômage représente la part de la population active qui est sans emploi mais disponible et en recherche active de travail.  
La population active = personnes employées + personnes au chômage.  

### Critères pour être compté comme chômeur :
1. Sans emploi durant la période de référence  
2. Disponible pour travailler immédiatement  
3. En recherche active d’emploi (ou ayant un contrat futur confirmé)  

##  Pertinence pour le projet
Cet indicateur est un **signal macroéconomique** qui influence directement :
- La capacité des ménages à rembourser leurs crédits  
- Le risque de défaut bancaire (plus le chômage est élevé, plus le risque augmente)  
- L’efficacité du marché du travail et la stabilité économique  

Il est reconnu comme un **indicateur clé** dans les Objectifs de Développement Durable (ODD), notamment l’ODD 8 : *Promouvoir une croissance économique soutenue, inclusive et durable, le plein emploi productif et un travail décent pour tous.*

##  Utilisation dans le projet de synthèse
1. **Analyse descriptive**  
   - Étudier l’évolution du chômage dans un pays donné (ex. Canada, USA)  
   - Comparer plusieurs pays ou régions  

2. **Visualisation**  
   - Courbes temporelles (1960–2023)  
   - Heatmaps par région ou par année  

3. **Séries temporelles (ARIMA)**  
   - Prévoir l’évolution du chômage dans les prochaines années  
   - Identifier les tendances et cycles économiques  

4. **Lien avec données microéconomiques (clients bancaires)**  
   - Croiser le chômage avec les défauts de crédit  
   - Montrer que le risque client dépend aussi du contexte économique global  

##  Limites et précautions
- Les définitions du chômage varient selon les pays  
- Les données agricoles et informelles sont difficiles à mesurer  
- Les femmes et certaines catégories sociales peuvent être sous-représentées  
- Les comparaisons internationales doivent être faites avec prudence  

##  Intégration dans le projet
Placer le fichier CSV dans : data/raw/unemployment_world.csv

Et documenter son usage dans le rapport :
- Section **Données macroéconomiques**  
- Section **Méthodologie – Séries temporelles**  
- Section **Discussion – Influence du contexte économique sur le risque de crédit**

