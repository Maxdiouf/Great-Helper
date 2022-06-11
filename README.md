# Great-Helper
Robot interactif, intervient pour apporter de l'aide aux nouveaux étudiants en bachelor developpement web au sein d'Hetic.
<br>
<br>
Ce robot à été crée dans le cadre de notre formation de développeur web chez HETIC, encadré par Janin Loïc.
<br><br>
Il nous est demandé de crée un bot qui doit mener une discussion avec le(la) nouvel(le) etudiant(e), afin de filtrer et apporter un réponse précise à sa demande.
<br><br>
Nous proposont alors en groupe de quatre, le robot discord G-MEC, qui regroupe les fonctionnalitées suivantes :
<br><br>
Le robot fonctionne dans un serveur qui comporte deux channels: -Le channel Général : seul les commandes (lister plus bas) pourront y etre appliquer. -le channel G-MEC Help : résérvé à l'aide personnaliser en discutant avec le bot, on commence une discussion sur ce channel avec la commande suivante : 'g-mec!'., les commande sont aussi applicable sur ce channel.
<br><br>
Les commandes possibles (toute commande devra débuter par '$') : - $info -> permet d'afficher la liste des commandes possible - $date -> affiche la date - $heure -> affiche l'heure - $serveur -> afiche les informations relatives au serveur - $memes -> affiche un meme orienter developpement tiré au hazard - $citation -> affiche une citation tirée au hazard - $play -> faire jouer un morceau à travers un lien - $modo @username -> demander à un utilisateur de vous contacter - $add entrée sortie -> contribuer au developpement du robot en ajoutant une réponse à une entrée inconnue - $clear nb -> nettoyer l'historique de discussion en supprimer un nombre 'nb' de messages - g-mec! -> démarrer une discussion avec le bot.
<br><br>
Une fois le mode discussion activé avec 'g-mec!', et en supplément des commandes précédentes, pour mieux géré la discussion vous avez à disposition les commendes suivantes: - return -> reviens à la question précédente dans la chronologie de la discussion - reset -> redémarrer la discussion depuis le début - fin -> arreter la discussion
<br><br>
coté technique : La discussion et la chronologie de la discussion est géré avec un 'Arbre' et ses 'Nodes'. L'historique de discussion est géré avec les 'Classes' et les 'Listes', une fois la discussion terminer la 'Valeur'(en forme de liste) de la 'Clefs'(qui est le username) est vidée. La fonction de contribution '$add' est géré par un 'Dictionnaire'.
<br><br>
Membre du groupe et répartition des taches : Répartition des taches (chaqu'un c'est chargé de la partie sur laquelle il est plus à l'aise):
<br>
<a href="https://www.linkedin.com/in/diouf-maguette-2735ba204/">MAGUETTE DIOUF</a> <br>
Gajan Baskaran<br>
Emir Hakiri<br>
carim Belazzoug<br>
