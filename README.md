# ANALYSE_RH-SQL-SERVER-POWER-BI
![Capture d'écran 2024-06-03 224653](https://github.com/AnalystDose/ANALYSE_RH-SQL-SERVER-POWER-BI/assets/169387833/4c6947e6-e5e5-4f5d-bb5f-1b4535173930)
## Description

Concevez un tableau de bord qui permet de surveiller les principales métriques liées aux ressources humaines, telles que le taux de rotation du personnel, la satisfaction des employés et les performances individuelles.

## Source et aperçu des données🚀
L'ensemble des données des ressources humaines faisant l'objet de notre étude est constitué de plus de 22k lignes.
Ces données relèvent des différentes informations sur les employés de l'entreprise à savoir le nom et le prénom, le genre, la date de naissance, la race, le département, le post, le type de post, la date d'embauche, la date de fin de contrat et la localité.

## Problèmes constatés dans les données ⚡
Lors de l'exploration et de l'analyse initiales de l'ensemble des données des ressources humaines, plusieurs problèmes ont été identifiés :

- Valeurs manquantes:  La colonnes « termdate »  présentait des valeurs manquantes qui a nécessité une manipulation et un calcul minutieux.

- Formatage incohérent: Ce problème a été observé dans différentes colonnes, d'où la nécessité de normaliser les données pour en assurer la cohérence.
 
## Outils utilisés ⚡

Pour le projet d'analyse de données des ressources humaines, les outils  suivants ont été utilisés :

- SQL: Pour le nettoyage des données et les requêtes pour l'analyse 
- Power BI : pour la visualisation des données.

Les données sont calculées grâce à des requêtes sql(cte, temp table, sous requêtes ) puis exporter en fichier csv pour être visualiser grâce à Power Bi.

NB: pas d'utilisation de fonctions DAX pour ce projet.



## Résumé des résultats

1. Il y a plus d'employés masculins
2. La race blanche est la plus dominante, tandis que la race amérindienne et hawaïenne est la moins dominante.
3. L'employé le plus jeune a 20 ans et le plus âgé 57 ans.
4. 3 groupes d'âge ont été créés (31-40, 41-50, 50+). Un grand nombre de salariés ont plus de 50 ans, suivis par les 41-50, tandis que le groupe le moins nombreux est celui des 31-40.
5. Un grand nombre d'employés travaillent au siège .
6. La durée moyenne d'emploi des employés licenciés est d'environ 7 ans.
7. La répartition des sexes entre les départements est assez équilibrée, mais il y a généralement plus d'hommes que de femmes.
8. Le département Audit a le taux de rotation le plus élevé, suivi par le département de comptabilité. 
9. Le taux de rotation le plus faible se trouve dans les départements juridiques et marketing.
10. Un grand nombre d'employés sont originaires de l'État de l'Ohio.
11. L'évolution nette du nombre d'employés à baissé au fil des ans.
