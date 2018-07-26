Human Talk - 15 mai 2018
---

**cme: a configuration checker and editor**
----
*Par Dominique Dumont*

De ce que j'ai compris, il s'agit la d'une sorte de gestionnaire de fichier de configuration intelligent pour les distribution Debian de Linux fait en bash.

Quel fichier sont supporté ? etc ... je n'ai pas compris grand chose étant donné que ma connaissance sur Linux s’arrête à ce qu'on à appris au campus.

On peut contrôler tout ça via la console ou alors sur une interface que Dominique à aussi développé lui même.

	
**Test unitaires et TDD - Partie 2 : petite démo**
----
*Par Xavier NOPRE*

J'avais déjà suivis la conférence de Xavier Nopre à Agile Grenoble, qui est présenté sur Java. 
Mais nous n'avions pas encore vu ce langage.
ça m'as donc permis de revoir ce sujet et comprendre beaucoup mieux ce qu'il fait en live coding.

Le TDD est donc une méthodologie de travail agile, qui permet d'obtenir le MVP (most valuable product) et éviter la régression tout en ayant un environnement de développement agréable.
Cette méthode se déroule en 3 itérations simples que l'on répète tant que l'on à du code à faire.

1. Écrire le test
2. Écrire le code
3. Refactorer

Le but étant de ne pas écrire de test qui passerait directement mais qui décris le comportement que l'on veut obtenir.

Pour écrire le code il suffit juste d'aller droit au but le plus simplement possible sans anticipé de comportements futurs.

Pour finir on refactor le code pour le rendre plus lisible ou plus optimisé.

	

**Introduction à l'API Stream de Java**
----
*Par Marc Nazarian*

Les stream API de Java on était introduis dans la version 8 mais sont assez méconnus. 
C'est une autre façon de gérer des collections,le but premier est de les trier et de les filtrer.

Pour les utiliser il suffit d'ouvrir un stream sur une collection puis chainer les méthodes associées.
Il existe beaucoup de ces méthodes et cela permet de faire ce que l'on veut avec les listes.

Les noms de ces méthodes sont plutôt explicite, de ce fait les  stream rendent le code lisible et moins difficile à
 appréhender que des boucles.
