# Calculabilité & Complexité

## Calculabilité

### Définitions et Théorèmes

__Cohérence__ : propriété d’un système formel dans lequel unénoncé et sa négation ne peuvent être démontrés vrais tous les deux. (notion universelle de la vérité)

__Complétude__ : propriété d'un système où tout énoncé vrai est démontrable.

__Décidabilité__ : existence, dans un système formel, d’un procédé systématique (algorithme) qui permet de déterminer la véracité / fausseté d’un énoncé démontrable. (automatisation des preuves)

__Semi-décidabilité__ : Il existe un algorithme qui termine en temps fini et répond "oui" si l'entrée est vraie.

__Th. De complétude__ : La logique des prédicats est complète.

__1er Th. d'incomplétude__ : Tout système formel "un peu riche" (contenant la thérorie des nombres) est soit incohérent soit incomplet.

__2nd Th. d'incomplétude__ : La cohérence d'un système formel (un peu riche) n'est pas démontrable au sein de ce système.

__Turing__ : Tout système formel "un peu riche" est indécidable.

__Th. de Rice__ : Toute propriété sémantique non triviale d'un programme est indécidable.

__Thèse de Church-Turing__ : Il y a équivalence entre :

* les fonctions intuitivement calculables

* les machines de Turing (ordinateur)

* les fonctions récursives (langage de programmation)

* le lambda-calcul (langage fonctionnel)

* les langages récursivement énumérables (ensemble de termes)

### Machines de Turing

Il existe une __machine de Turing universelle__ qui, ayant en entrée le codage $<M>$ d'une machine $M$ et un mot $m$, calcule l'application de $M$ à $m$. En 2007, il suffit de 2 états, 3 symboles et 6 transitions.

__Turing-complet__ : Un système formel est Turing-complet s’il est aussi puissant que les machines de Turing, c-à-d qu’on peut y décrire toute fonction calculable par une machine de Turing, ou de manière équivalente, avec lequel on peut simuler une machine de Turing universelle.

__Turing-équivalence__ : Un système formel est Turing-équivalent s’il réalise exactement les mêmes fonctions que les machines de Turing.

![indecidable.png not loading](/home/theo/Documents/indecidable.png)

__Indécidabilité du rejet__ : savoir si une machine n'accepte pas un mot est un problème ni décidable, ni semi-décidable.

__Indécidabilité du test à zéro__ : savoir si une machine n'accepte aucun mot est indécidable.

__Indécidabilité de l'équivalence__ de 2 machines de Turing.

Tout problème ayant un nombre __d'instances finies__ est décidable.

__Ackermann__ est une fonction calculable non récursive primitive.

## Complexité

* P = classe des problèmes solubles en temps polynomial de la taille de l'entrée.

* NP = classe des problèmes vérifiables en temps polynomial.

* NP-complet = problèmes vérifiables en temps polynomial, pas soluble en temps polynomial (sans doute, voir P=NP?).

* EXPTIME = problèmes solubles en temps exponentiel.

* LSPACE = problèmes nécessitant moins que $log(n)$ espace.

* PSPACE = problème nécessitant un espace polynomial.

* EXPSPACE = problèmes nécessitant un espace exponentiel.








