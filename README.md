# practice_sql_in_browser

L'objectif est d'offrir une interface pour s'exercer au langage SQL dans un seul fichier, sans autre installation qu'un navigateur.
Il s'agît d'un mode "bac à sable", les modifications sont perdus lorsque la fenetre est actualisée ou fermée.

Vous pouvez par exemple tester les commandes suivantes :

+ SHOW DATABASES;
+ USE emmy18;
+ SELECT database()
+ SHOW tables;
+ DESCRIBE acteurs;
+ SELECT nom, prenom FROM acteurs;
+ SELECT * FROM tourne;
+ SELECT nom, diffuseur FROM series ORDER BY diffuseur;
