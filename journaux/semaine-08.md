---
title: "Semaine 08"
date: 2014-10-27T13:15:29+01:00
---

*Du 27 au 31 octobre 2014.*

Jour 36 — Lundi 27 octobre 2014
-------------------------------

Ce matin, rendez-vous à l'[Archipel](http://www.larchipel.paris/).
Visite et discussion, il ny a toujours pas internet. Les gars qui s'en
occupent court après Fred depuis un mois apparement ?

Avec Alix, nous partons louer un camion pour récupérer du matériel
informatique qui servira surtout pour la formation référent numérique,
et aussi un peu de mobilier qui nous servira tout de suite. Pendant ce
temps les quelques élèves qui sont venus sont dans la chapelle. Beaucoup
de poussières, je crois que certains ne viendront pas à l’archipel.

Beaucoup de temps perdu, à peine l'occasion de faire une rapide
présentation de [Haskell](https://www.haskell.org/).

Doit-on compter ces journées comme cours ou pas ? Même question que pour
les interventions TV et les hackathons qui empêchent l’accès au local.

L’agencement «bureau avec des petites pièces et une grande principale»,
voir une deuxième pour la partie nourriture et repos semble vraiment
parfait.

Jour 37 — Mardi 28 octobre 2014
-------------------------------

Arrivé tôt à l’Archipel. Rangement des affaires déménagées le lundi.
Beaucoup de merde, des étagères inmontables, du matériel informatique un
peu collector, des livres anciens (informatique) et des classeurs vides…

Kata Morpion en [Python](https://www.python.org), en deux phases: aprs
la pause nous avons continu ! Surprenant et intressant. Il faudra le
refaire en partant de linterface graphique la prochaine fois, dune
manire gnrale, il faudrait faire a maintenant pour faire le lien avec
les projets en cours et ajouter un peu de motivation. Raccourcir la
boucle de feedback.

Il manque pas mal de matos à l’archipel. Mais en dépannage, on se
débrouille pas trop mal. Il faudra quand même faire une liste pour
déclencher des achats. Le routeur semble bousillé, nous n’avons pas
réussi à le faire marcher.

Un lve nous prsenter le binaire, lhexadecimal, le moyen de convertir, et
rapidement le calcul. Quelque dbordement sur wiresh\[ark. Les
s\](https://www.wireshark.org/)ujets qui viennent deux sont assez
intressants, une lve voulais faire un truc, je lui ait propos de
travailler sur les types dans les langages. Prsentation base sur le
volontariat au bout dun moment, cest srement le mieux faire pour rduire
la voilure et donner plus de temps pour le code.

Longs échanges sur la façon de faire les projets. J’évoque mes
problèmes:

-   pas de livraison
-   niveau hétérogène dans les groupes
-   pas de lecture de code

Ma proposition était de faire un seul groupe de 24 avec tirage au sort
des paires, dans un ordre aléatoire, puis chacun choisirait à son tour
une des tâches restantes de la liste que j’aurais préparée. Le jeudi
restitution/présentation devant tout le mode.

Une alternative est proposée : Garder les équipes, faire des vrai
sprint, définir les sprints après avoir faire la démo le jeudi après
midi. En 4h il faut avoir fini. C’est faisable, ça résoudra peut-être le
soucis de livraison et j’espère mettra la pression sur les équipes pour
travailler ensemble. Point à surveiller : est-ce que cela ne déclenchera
pas des tensions dans les équipes ?

Pour la lecture du code, je vais utiliser le concept du tirage au sort
de paires, que je brancherais à des programmes à lire, et ils feront une
présentation dès que c’est fait, le midi, nous pourrions voir 4 à 8
présentations de code. Mettre en place cet outils, avec la possibilitée
à terme de saisir les commentaires de code directement sur la plateforme
? Se baser sur les relecture de code peut-être ?

Rodolphe a rencontré un des fondateurs de
[pullreview](https://www.pullreview.com/) à
[Paris.rb](https://www.rubyparis.org). Ce dernier aimerait que nous nous
en servions. Je n'ai pas envie, je ne vois pas l'intérêt. Des outils
comme [CodeClimate](https://codeclimate.com/),
[pep8](https://www.python.org/dev/peps/pep-0008/), et autres existe en
librairies diverses pour chaque langage. Je préfère donc utiliser de
l'open source, adapté aux divers langages que nous allons utiliser
(pullreview ne propose que du [Ruby](https://www.ruby-lang.org/) pour le
moment).

Petit dojo en fin de journe sur n\[umber to roman
\](http://codingdojo.org/cgi-bin/index.pl?KataRomanNumerals)en Ruby.
Sans moi. Ils sont tombs dans le pige de faire I, puis II, puis III Dur
ensuite de reprendre le bon sens

Jour 38 — Mercredi 29 octobre 2014
----------------------------------

À 10h, peu de monde et à 11h Fred doit venir pour parler avec les
élèves, du coup on fait un mode questions/réponses large. Cela permet de
revenir sur les objets instances et les classes, sur un peu de
shell/terminal et autres.

Fred leur parle un peu de ce qu’il se passe à Simplon : Archipel,
Essaimage, et de ce qu’il pourrait y avoir dans le futur. Des points
réguliers sont annoncés, une idée de truc pour Noël évoqué, une rando au
col du Simplon aussi… Certains élèves demandent des formations sur le
community management et autres trucs un peu hors du cursus dev. Pas de
soucis, on peut prendre des créneaux pour ça. Nous parlons aussi de la
partie média, Fred parle d’organiser des scéances de média training.
Hmm.

Après la réunion d’équipe, nous abordons groupe par groupe un petit
point de situation projet, avec ensuite une série de tickets à faire
pour le sprint qui viens. Jeudi prochain, démo et livraison de ce qui à
été fait. Je reste sur l’idée que ça ne change pas grand chose à deux
soucis : lecture de code et gestion de groupe/équipe. Le code + la
gestion d’équipe, c’est très intéressant à aborder, mais tellement dur.
Les faire coder en binônme, avec une gestion ouverte de la grosse équipe
(équipe complète) me semble toujours plus intéressant. Mais là au moins
je peux temporiser.

Il manque, pour pouvoir les faire travailler par paire, la gestion de la
fin de travail et du commencement d’un nouveau travail. Comment faire ?
En une fois, tous ensemble, c’est intéressant pour partager les
résultats (bon ou mauvais), mais ça peut prendre du temps. Au fil de
l’eau ça pose le problème du la rotation des équipes. Est-ce qu’une
paire doit attendre qu’une autre au moins ait terminé pour pouvoir faire
une rotation ?

Je vais travailler sur un outil de lecture de code par paire, en
commenant sur la problmatique de gnrer des paires. Est-ce que je me base
sur la librairie existante issue du wago\[n ?
P\](https://www.lewagon.com/)ourquoi pas :-).

En fin de journée, nous avons essayé de travailler sur les projets, mais
sans internet (ou en tout cas sans débit suffissant pour un groupe tel
que le nôtre), c’est difficile. Nous partons donc pour faire un dojo
rapide en Haskell sur ma machine (qwerty). Je crois que les élèves
apprécient de découvrir un nouveau paradigme. Nous abordons un truc
oublié dans la présentation de lundi : le pattern matching.

Pas d’enregistrement, il faut que j’installe Istanbul sur ma machine
pour pouvoir faire des screencasts.

Jour 39 — Jeudi 30 octobre 2014
-------------------------------

Nous sommes aujourdhui lOpe\[nWorldForum.
A\](https://fr.wikipedia.org/wiki/Forum\_mondial\_du\_libre)musant de
voir certains arriver discuter avec des exposants et trouver
potentiellement des entretiens

Beaucoup de questions : comment doit-on se vendre ? À quel poste peut-on
prétendre ? Mettons en place ce moment/atelier pour les aider à y voir
clair, et les préparer à ça.

Ils sont très intéressés par le programme de demain, nous reportons la
FOAD et la rétrospective soit à lundi, soit on la fait sauter. Nous
déciderons lundi.

Dans ce genre d’événement, je pourrais présenter l’orientation
apprentissage par le code source ouvert que nous mettons en place. La
lecture du code source pour apprendre, une des libertés du logiciel
libre…

Quelques retour d’élèves qui apparement on des retour positifs sur le
contenu de leur formation (dojo, mob programming, libre, projet,
langages varié).

Une belle confrence sur lIR\[ILL e\](https://www.irill.org/)xpliquant
quils travaillent fdrer des industrielles, des chercheurs et le grand
public autour du logiciel libre. Ils sont intresss par : les boites qui
peuvent les aider (financirement et autres), les enseignants qui peuvent
partager (moi et mes pratiques peut-tre ?), les tudiants pour
participer. Nous pouvons surement utiliser leurs sujets comme tude de
cas pour travailler

Jour 40 — Vendredi 31 octobre 2014
----------------------------------

Les élèves sont retourné à l’OpenWorldForum. Je prépare le tableau
d’information pour leur retour, je réponds à des emails…

Ceci est [l'histoire d'une de mes expriences en tant que formateur dans
un bootcamp](https://yaf.github.io/journal-d-un-formateur-en-2015/).
