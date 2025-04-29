Ce projet est un jeu éducatif en langage C qui propose différents types d’exercices de mathématiques, niveau CM1.
En effet, on y retrouve l'addition, la soustraction, les mutiplications et les tables, les divisons et la parité d'un nombre.

Le joueur arrive sur l'interface du jeu etdoit entrer son nom.
Puis le menu d'affichage apparait, avec les différents jeux proposés et le joueur est invité à sasir un nombre pour choisir son jeu.
Le jeu choisi est alors lancé et le joueur doit résoudre des calculs générés aléatoirement. 
Un système de points est attribué selon le nombre d'essais (maximum 3 essais et entre 0 et 10 points attribués par question).
Les scores sont enregistrés avec le nom de joueur, la date et l'heure dans un fichier texte (scores.txt). 
Lorsque les joueurs saisissent leurs noms au debut, les anciens scores sont automatiquement affichés (s’ils existent).

Pour la compilation et l'éxécution, j'ai utilisé le compilateur en ligne : ONLINE C COMPILER.
Ce qui a évité les problémes de compatibilités de certaines applications, sur les différents ordinateurs avec lesquels j'ai travaillé.
J'utilise aussi le fichier texte "scores.txt" pour stocker les différents scores au cours du jeu.

Pour les outils et commandes utilisés, j'ai fait appe; à différents bibliotheques :


stdio.h, pour les entrées/sorties standard comme printf ou scanf par exemple

stdlib.h : pour rand() et srand() (ce qui concerne la génération de nombres aléatoires)

time.h : pour time() et strftime() (ce qui concerne la gestion de la date et de l’heure)

string.h : pour la gestion de chaînes de caractères (strstr() qui permet de retrouver un nom dans le fichier)
