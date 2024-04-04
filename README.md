Certificat de réussite : "Créez des pages web dynamiques avec JavaScript" 
Délivré par OpenClassrooms a Thomas Vernin

Compétences aquises : JAVASCRIPT, DOM, API, JSON

_______

Site internet : LES BONNES PIECES 

Après avoir cloné le repo utilisation de Node comme serveur web et VSCode comme éditeur de code.

Si vous utiliser VSCode ou un autre éditeur de code avec une extersion de serveur web comme live server, vous pouvez lancer direcement votre site avec l'extension que vous utilisez habituellement. 

Instalation des dépendances de ce projet avec `npm install` puis j'ai lancé le projet via la commande `npm start`. Termninal le lien vers le site (par defaut http://127.0.0.1:8080 )

/1 commit par étape/

Etape 1 : Manipuler la syntaxe JSON pour ajouter les pieces avec leurs infos.

Etape 2 : Génerer ma page web avec les éléments existant, ajout de la première pièce. Manipuler le le DOM, créer de nouveaux éléments avec createElement, afficher les nouveaux éléments avec appendChild. 
Utilisez des opérateurs pour vérifier vos données avant de les afficher : l’opérateur ternaire pour transformer une valeur en une autre selon 2 possibilités ; l’opérateur nullish pour fournir une valeur de remplacement quand une valeur est null, ou bien lorsqu’elle est undefined.

Etape 3 : Inserer les 4 filtres
Pour parcourir vos données afin de générer autant d’éléments du DOM qu’il y a d’éléments dans vos listes, utilisation de la boucle for et utilisation de la fonction sort pour réordonner les éléments. Utilisation de la fonction filter pour éliminer les éléments non désirés et conserver les éléments choisis.

Etape 4 : Inserez la MAP
Utilisation de la syntaxe lambda pour écrire des fonctions JavaScript simplifiées et fluidifier la lecture du code.
Mappez deux listes avec la fonction map pour transformer une information, pièces abordable et pièces disponible.
Supprimez des éléments dans une liste avec la fonction splice.

Etape 5 : Ajout d'une barre tarifaire intéractive relié aux pièces de la page
La propriété innerHTML permet d’effacer ou de remplacer le contenu d’un élément du DOM.
En manipulant le DOM, j'ai généré une nouvelle version de la page web.
La combinaison de ces deux opérations permet de mettre à jour la page lorsque l’utilisateur interagit avec elle.

Etape 6 : Envoyez une requete HTTP depuis le navigateur avec la fonction fetch 
Cette dernière prend en argument d’appel une chaîne de caractères comprenant l’adresse du serveur web et le chemin qui décrit la ressource que nous souhaitons manipuler. Le verbe utilisé par défaut par la fonction fetch est GET.
J'ai cloné le dossier Back-end, puis j'ai lancé l'API pour récuperer les avis.
serveur : http://localhost:8081/

Etape 7 : 


