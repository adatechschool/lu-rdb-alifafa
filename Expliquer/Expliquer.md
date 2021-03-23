# Expliquer

En informatique, une base de données relationnelle est une base de données où l'information est organisée dans des tableaux à deux dimensions appelés des relations ou tables. Une base de données consiste en une ou plusieurs relations.  Les lignes de ces relations sont appelées des nuplets ou enregistrements. Les colonnes sont appelées des attributs.

# Entité

Une entité est un objet du monde réel avec une existence indépendante.

Une entité (ou type d’entité) est une chose (concrète ou abstraite) qui existe et est distinguable des autres entités.

L'occurrence d’une entité est un élément particulier correspondant à l’entité et associé à un élément du réel. Chaque entité a des propriétés (ou attributs) qui la décrivent. Chaque attribut est associé à un domaine de valeur. Une occurence a des valeurs pour chacun de ses attributs, dans le domaine correspondant.

# Association

Une association (ou une relation) est un lien entre une ou plusieurs entités

# Relation

Une association est traduite en relation. Une relation est définie par un verbe.

# Clé primaire

La contrainte d'unicité est une clé primaire simple ou composée. La clé primaire est tout simplement une clé que nous choisissons comme celle qui nous permettra d’identifier un tuple dans une relation. Dans une table, c'est un ensemble minimal de champs (colonnes) qui constitue un identifiant de ses enregistrements. Autrement dit, pour une clé primaire donnée, il n'existe qu'une seule ligne possible dans la table.

# Clé étrangère

La contrainte de dépendance est une référence ou clé étrangère. Dans une table, c'est un champ, ou une combinaison de champs, qui contient des copies de clés primaires (ou secondaires) d'une autre table.

# Cardinalité

Des cardinalités précisent la participation de l'entité à l'association, elles fonctionnent par couple. La cardinalité d'une association permet de représenter le nombre minimum et maximum d'instances qui sont autorisées à participer à la relation. La cardinalité est définie pour les deux sens de la relation.

La cardinalité minimale peut être de 0 ou de 1. La cardinalité maximale peut être de 1 ou de n.

# Jointure

Une jointure colle deux tables. Une jointure peut être interne ou externe et a une condition. Une jointure externe sert à garder toutes les informations d'une table(ou des deux) tandis qu'une jointure interne ne garde pas forcément ces informations. La jointure interne force les données d'une table à avoir une correspondance dans l'autre. Il existe également la jointure naturelle pour laquelle une condition n'est pas nécessaire.

# Normalisation

La normalisation est l'un des concepts de base de la modélisation des données relationnelles. Dans le modèle de base de données relationnelle, une bonne conception de base de données se caractérise par une redondance minimale.

La normalisation correspond au processus d'organiser ses données afin de limiter les redondances, divisant une table en plusieurs, et en les reliant entre elles par des clefs primaires et étrangères. L'objectif est d'isoler les données afin que l'ajout, l'effacement ou la modification d'un champ puisse se faire sur une seule table, et se propager au reste de la base par le biais des relations. Pour ce faire, la normalisation introduit en tout 6 formes normales. Un modèle relationnel doit être de 3ème forme normale(elle est la plus utilisée du fait de son équilibre entre redondance et performance).

# CRUD

Ce sont les quatre opérations de base sur la base de donnée.

- **C**reate (créer) ou en SQL: INSERT
- **R**ead ou **R**etrieve (lire)ou en SQL: SELECT
- **U**pdate (mettre à jour)
- **D**elete ou **D**estroy (supprimer)