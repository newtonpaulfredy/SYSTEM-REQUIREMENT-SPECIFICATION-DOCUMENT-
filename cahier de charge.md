APPLICATION DE GESTION DE NOTE

Version:1.0.0


1-PRESANTATION DU PROJET:

l'objectif principal de notre projet est developper une application de gestion de notes des etudients et permettre aux etudients de pouvoir consulter leurs note en toute securite.
cette application sera destinee aux etablissements scolaires telques les lycees, les universites, les colleges... et doit offir une interface simple, intuitive et securisee, utilisable sur windows et portable.



2-OBEJECTIF DU SYSTEME

     Notre système a plusieurs objectifs et nous pouvons les classer en plusieurs catégories parmi lesquelles :
-Objectifs techniques et fonctionnels :

       .Automatiser les calculs:générer automatiquement les. moyennes,classements,coefficients,et bulletins réduisant les erreurs humaines ;
       
       .Gagner du temps:alléger les charges administratives du personnel éducatif et des enseignants ;
       
       .Assurer la sécurité des données:protéger les informations sensibles grâce à des systèmes d’authentification et de sauvegarde .
       
-Objectifs pédagogiques et organisations :
       .Centraliser les données académiques:regrouper toutes les notes,moyennes,appréciations et bulletins dans une base de données unique et accessible ;
       
       .Suivre la progression des élèves:permettre une visualisation claire de l’évolution des résultats au fil des trimestres ou semestres ;
       
        .Favoriser la transparence:offrir aux élèves et aux parents un accès sécurisé aux résultats ,réduisant ainsi les erreurs et les malentendus.
        
         
     En somme , notre système a pour principal objectif d’automatiser,centraliser et sécuriser le suivi des performances académiques des apprenants , tout en facilitant le travail des professeurs et des administrateurs .



3. Environnement technique
_(Ange Michelle)_


4. Objectifs techniques
_(Ange Michelle)_


5-ACTEURS ET UTILISATEURS

I.	Utilisateurs 

Un utilisateur est une personne qui utilise le système. Ils sont entre autres :

•	Enseignants : Rôles : saisir et modifier les notes ; consulter les résultats ; gérer les absences, Besoin : saisir les notes ; accéder aux notes de l’étudiant ; consulter les résultats ; gérer les absences 

•	Etudiants : Rôles : consulter les notes ; consulter les résultats, besoin : accéder au notes ; consulter les résultats ; suivre les absences

•	Parents : Rôles : consulter les notes ; consulter les résultats, Besoin : accéder au notes de leurs enfants ; consulter leurs résultats ; suivre les absences 

•	Administrateurs : rôles : gérer les utilisateurs et leurs droit d’accès ; assurer la sécurité et l’intégrité des données ; audit et journalisation, Besoin : accéder aux informations des utilisateurs ; gérer les utilisateurs 

•	Secrétariats pédagogique : gestion des rôles administratifs 


II.	Acteurs 

Un acteur est une entité qui interagit avec le système il peut s’agir d’une personne, d’un système informatique ou d’un site web

•	Ministère de l’éducation : Rôles : définir les politiques et les normes pour la gestion des notes, Besoin : accéder aux informations concernant les notes ; les résultats et les absences

•	Directeurs de l’établissement : Rôles : superviser la gestion des notes, Besoin : accéder aux informations concernant les notes ; les résultats et les absences

•	Fournisseurs de services : Rôles : fournir des services de gestion des notes, Besoin : accéder aux informations concernant les notes ; les résultats et les absences

•	Système de gestion des notes : rôles : gérer les notes des étudiants 

•	Base de données des étudiants : rôles : gérer les informations des étudiants 

•	Services de paiement en ligne : rôles : gérer les informations de paiement des étudiants

•	Services de messagerie électronique 



6. Diagramme du contexte
_(PRISCA)_


7-CAS D'UTILISATION

Un système de gestion de notes est utilisé par plusieurs acteurs pour saisir, traiter, stocker et consulter les résultats académiques des étudiants. 

Listons les différents  cas d'utilisation, organisés par acteur :

ENSEIGNANT:
Ses cas d'utilisation incluent : 
-Saisir les notes : Entrer les résultats des examens, devoirs et évaluations pour les cours dont il a la charge.
-Modifier les notes : Corriger ou mettre à jour les notes si nécessaire.
-Consulter les listes d'étudiants : Accéder aux listes des élèves inscrits dans ses classes.
-Calculer les moyennes ;
Publier les notes : Rendre les notes et les résultats accessibles aux élèves et aux parents sur la plateforme. 

ETUDIANT:

 Ses cas d'utilisation sont : 
 
-Consulter ses notes : Accéder à ses résultats détaillés pour toutes les matières et tous les examens.
-Suivre sa progression : Visualiser l'évolution de ses moyennes au fil du temps.
-Recevoir des notifications : Être informé de la publication de nouvelles notes ou d'informations importantes. 

ADMINISTRATEUR

L'administrateur a un rôle de supervision et de gestion globale du système. Ses cas d'utilisation incluent : 

-Gérer les comptes utilisateurs : Créer, modifier ou supprimer les comptes des enseignants et des étudiants.
-Générer des rapports et des bulletins : Produire des documents officiels comme les relevés de notes semestriels ou annuels.
-Paramétrer le système : Définir les barèmes de notation, les coefficients des matières, et d'autres règles de gestion.
-Sauvegarder les données : Assurer la sécurité et l'archivage des données scolaires. 


8. Besoins fonctionnels
_(Linda)_



9-OUTILS UTILISES

Pour le développement et la gestion du projet d’application de gestion de notes, on vas utiliser de nombreux outils qui sont entre autre :

--Environnement de developpement

qui est l'ensemble des logiciels utilises pour coder notre application. nous auront besoin de :

- Visual Studio Code : éditeur de code dans lequel notre application sera coder
- Java : langage principal pour l’application 
- JavaFX : pour la création de l’interface utilisateur 

--Gestion de version

qui seera notre dossier de sauvegarde des version

- Git : pour le suivi des modifications du code source.
- GitHub : hébergement du dépôt et collaboration entre les membres via les branches, commits, pull requests.

--Base de données
- SQLite  : pour stocker les informations sur les étudiants, matières, notes et les autres informations

--Design / Maquettes
- Figma : pour concevoir l’interface utilisateur avant le codage
- Draw.io : pour les schémas 

--Documentation
- Markdown sur GitHub : fichier d'extension ".md" sur github pour rédiger le cahier des charges et la documentation technique




10. Problèmes possibles
_(Suzanne)_

12. Livrables attendus
_(Martine)_

13. Maquettes / Interfaces
_(Ben et Divine Ides)_



14 Besoin non fonctionnel

Cahier des Charges – Besoins Non Fonctionnels
1. Performance
Objectifs : Temps < ouverture 3s au plus, au moins 500 utilisateurs , disponibilité 99%. Réalisation : Cache (Redis), backend optimisé (Spring/Django/Express), SQL indexé, minification
front, load balancing, cloud + monitoring, réplication BDD.
 2. Sécurité
Objectifs : Authentification forte, données protégées. Réalisation : JWT/OAuth2, HTTPS, hachage scrypt, chiffrement AES-256, logs (ELK), backups
quotidiens + tests.
 3. Fiabilité
Objectifs : Continuité du service. Réalisation : Transactions ACID, sauvegarde locale temporaire, serveur secondaire, validations
strictes.
 4. Compatibilité
Objectifs : Fonctionne partout. Réalisation : HTML5/ES6, responsive mobile, API REST + Swagger.
 5. UX / Ergonomie
Objectifs : Interface simple et accessible. Réalisation : UI légère (Material/Bootstrap), prototypes Figma, WCAG 2.1, i18n JSON.
 6. Maintenabilité
Objectifs : Code durable et clair. Réalisation : MVC/microservices, documentation Swagger/UML, tests (JUnit/Jest/PyTest), CI/CD.
 7. Scalabilité / Portabilité
Objectifs : Facile à faire grandir. Réalisation : Docker, CI/CD, architecture modulaire, Redis distribué, PostgreSQL.
 8. Audit / Confidentialité
Objectifs : Traçabilité + protection. Réalisation : RBAC strict, aucune donnée sensible côté front, triggers SQL + logs Kibana.
9. Conformité
Objectifs : Respect des règles. Réalisation : Politique de confidentialité, masquage données, consentement, conservation limitée. Résumé final (1 phrase)
Application rapide, sécurisée, fiable, compatible, scalable et conforme, avec des solutions
techniques simples pour chaque exigence.
