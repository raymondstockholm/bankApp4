BANKAPP
=================

Notre application bancaire a été écrite en JAVA avec le framework spring-boot.
Nous avons également développé une seconde application en AngularJS pour administrer les données.



Application bancaire
------------------------
Cette application est accessible à l'adresse suivante : 
http://bankapp4.hdp2.silca/

Elle comprend les fonctionnalités obligatoires suivantes :
- login
- création d'un compte
- visualisation d'un compte (solde)
- écran de saisie d'une transaction entre 2 comptes

Elle comprend également les fonctionnalités optionnelles suivantes :
- liste des transactions
- graphique sur les entrées et sorties d'argent

L'application est composée d'une application Web "bankApp4" et de 4 microservices REST(mslogin, mslistaccounts, mscreatetransaction, mscreateaccount) dont certains contiennent plusieurs fonctions.


Application d'administration
-----------------------

Cette application est accessible à l'adresse suivante : 
http://wsrestgeneration.hdp2.silca/myApp/

Elle comprend les fonctionnalités suivantes :
- dashboard
- changement des couleurs
- depuis le menu entité, on peut parcourir toutes les entités de notre application (comptes, transactions et les documents)
- sur chacunes des entités, on peut effectuer :
   - les opérations SQL de base (select, update, ...)  
   - les opérations plus spécifiques comme le tri,"elastic search" et l'export excel.
   


