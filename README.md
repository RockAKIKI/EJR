# EJR
(Pour le projet de Netflix)

Cahier de charge Projet Fil Rouge PRF .NET / ReactJs.

Le but du projet fil rouge est de réaliser une application qui représente un clone du site web NETFLIX.

Notre Application sera composée de plusieurs parties.

Partie 1 : La partie interface client (Front).

Partie 2 : Gestion des données et logique métier (Back).

Partie 3 : Une application mobile (Bonus).

---- ------------------- -------------- -----------------

Partie 1

La partie interface client est un site web qui permet aux utilisateurs de :

-	S’inscrire.
-	Se connecter.
-	Naviguer entre les différentes catégories de vidéos.
-	Visualiser un élément.
-	Une page de Foire aux questions.

Le site web peut être réaliser avec le framework ReactJs ou Blazor.

---- ------------------- -------------- -----------------

Partie 2

La partie gestion de données et logique métier (Back) est une api rest réalisée en Asp.NET Core.

La partie donnée sera gérée par une base de données relationnelles (Sql Server ou Mysql) ainsi que l’ORM EntityFrameWork Core.

L’api Rest doit permettre pour les utilisateurs non identifiés de :
-	Récupérer la foire aux questions (une question réponse).
-	De s’inscrire avec un nom, prénom, email et mot de passe.
-	De se connecter avec email et mot de passe.


L’api Rest doit permettre pour les utilisateurs identifiés en tant que client de :
-	Récupérer les catégories des ressources et leurs ressources. (Chaque catégorie possède un nom et un identifiant unique).
-	Récupérer une ressource (Film, série, documentaire...). (Chaque ressource possède un nom, une ou plusieurs images, un ou plusieurs url vers la ou les vidéos, une ressource peut être dans une ou plusieurs catégories).

L’api Rest doit permettre pour les utilisateurs identifiés en tant qu’admin de :

-	Ajouter, modifier ou supprimer une question réponse de FAQ.
-	Ajouter, modifier ou supprimer une catégorie de ressource.
-	Ajouter, modifier ou supprimer une ressource.
-	Voir la liste des utilisateurs et bannir un utilisateur.

L’api doit être sécuriser avec le pattern JWT.

---- ------------------- -------------- -----------------

Partie 3 (Bonus)

La partie 3 est une application mobile qui fournira les mêmes fonctionnalités que le site web.

L’application mobile doit être réalisé en Xamarin Forms.

Quelques imprimes écrans pour s’en inspirer.
