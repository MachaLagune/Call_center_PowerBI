# Call_center_PowerBI
Elaboration d'un tableau de bord à partir de différentes tables issues de l'activité d'un call_center.


Description des différentes tables :

Call Charges
- Call Charges 2018 (Min) : Année 2018 - Prix de l'appel par minute (en dollar)
- Call Charges 2019 (Min) : Année 2019 - Prix de l'appel par minute (en dollar)
- Call Charges 2020 (Min) : Année 2020 - Prix de l'appel par minute (en dollar)

Employees
- EmployeeID : Identifiant unique de l'employé
- EmployeeName : Nom de l'employé
- Site : Nom/localisation du bureau
- ManagerName : Manager de l'employé

Call type
- CallTypeID : Identifiant unique du type d'appel
- CallTypeDesc : Description du type d'appel

Call Data (2018-2021)
- CallTimestamp : Date et heure de l'appel
- Call Type : Type d'appel
- CallDuration : Durée de l'appel (en secondes)
- WaitTime : Temps d'attente avant que l'appel soit pris (en secondes)
- Call Abandoned : L'appel a été abandonné



Etape 1:
Traitement des coquilles, outliers ou erreurs présents dans le jeu de données, ajout de colonnes dans Power Query

Etape 2:
Modélisation des données: mise en place d'un schéma en étoile entre les différentes tables, et création d'une table de date

Etape 3: 
Création des mesures nécessaires pour les différents axes d'analyse, avec le langage DAX.

Etape 4:
Mise en place du tableau de bord pour présenter:
- Une vision globale du service clients: nombre d'appels total à différents niveaux, taux d'appel Within SLA ou Outside SLA par secteur, bureau, temps d'appel moyen, KPIs
- Une vision des revenus par appels: évolution des renenus d'une année à l'autre, revenus par secteur, équipe

