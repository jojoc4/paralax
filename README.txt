Pour ce travail, nous avons réalisé les modifications suivantes au projet:

- Nettoyage et commentaires du code :
	Pour plus de clarté, nous avons commencé par commenter le code pour mieux nous y retrouver.
	Ensuite, nous avons supprimé les parties inutiles du code pour améliorer les performances du projet,
	comme par exemple une boucle dont les calculs n'étaient jamais utilisés dans le fragment shader.

- Respect des standards HTML :
	Le code de base ne respectait pas les standards HTML du W3C, donc nous l'avons adapté.

- Suppression des fichiers inutiles :
	Beaucoup de fichiers fournis ne servaient pas. Nous les avons donc enlevé pour alléger le projet.

- Logo GSGS :
	Nous avons pris le nouveau logo GSGS, car celui fourni datait de 2017.

- Factorisation du code :
	La fonction drawScene répétait plusieurs fois le même code pour l'affichage des textures.
	Nous l'avons factorisé dans la fonction drawTexture qui est appelée depuis drawScene.

- Inputs pour les facteurs de réglages :
	Nous avons intégré des inputs dans la page HTML pour permettre de facilement modifier la quantité
	de mouvemenent des plans du parallaxe.

- Utilisation du gyroscope :
	Pour permettre le fonctionnement sur mobile, nous avons permis l'utilisation du gyroscope pour
	animer le parallaxe.
	Fonctionne sur toutes les plateformes avec un navigateur prenant en charge le gyroscope.

- Utilisation de translations au lieu de rotations :
	Comme la méthode avec les rotations causait des collisions entres les différents plans, nous avons
	jugé bon de remplacer ces rotations par des translations des plans.

