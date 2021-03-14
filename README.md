# practice_sql_in_browser

L'objectif est d'offrir une interface pour s'exercer au langage SQL dans un seul fichier, sans autre installation qu'un navigateur.
Il s'agît d'un mode "bac à sable", les modifications sont perdus lorsque la fenetre est actualisée ou fermée.

Vous pouvez par exemple tester les commandes suivantes :

+ SHOW DATABASES;
+ USE emmy18;
+ SELECT database();
+ SHOW tables;
+ DESCRIBE acteurs;
+ SELECT nom, prenom FROM acteurs;
+ SELECT * FROM tourne;
+ SELECT nom, diffuseur FROM series ORDER BY diffuseur;
+ SELECT acteurs.nom FROM acteurs;
+ SELECT acteurs.nom FROM acteurs LIMIT 3 OFFSET 5;

Les prochaines étapes sont :

+ ajout du mot clé OR pour la close WHERE
+ ajout des parenthèses dans la close WHERE
+ suppression d'une base de données
+ suppression d'une table
+ modification / suppression d'enregistrements
+ déclaration des clés étrangères
+ possibilité d'importer un fichier contenant des requêtes SQL
+ possibilité de télécharger une base de données sous la forme d'un fichier texte contenant les requêtes necessaires.
