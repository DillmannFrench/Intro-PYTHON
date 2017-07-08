% Informatique
% Baudouin DILLMANN 
% 15 septembre 2016


# Cours

- Cycle Ingénieur International
- Informatique CT.1105
- ECTS 5 (soit 125 heures de travail, donc 2 heures de travail personnel pour 1 heure de cours)
- 14 sessions

# Intervenants

- Baudouin Dillmann 
- Nicolas Rousset 

# Évaluation

- contrôle continu (40%)
- devoir surveillé (20%, lundi 14 novembre)
- contrôle final (40%)

Les devoirs et contrôles finaux auront lieu sur papier.

# Objectifs du cours

- maîtriser les bases de l'algorithmique
- être capable d'écrire un algorithme pour résoudre un problème
- maîtriser les bases de la programmation en Python
- être capable de traduire un algorithme en Python

# Informatique

<center> Comment définir l'informatique ? </center>

## Un enjeu majeur de Société... 

----

\center\includegraphics[height=6.5cm]{./additional/Croissance.png}




# L'informatique et le Langage Python 

<center> Ouvrages de référence du Cours </center>

## Niveau Avancé

- Casamayou-Boucau et al. Programmation en Python pour les mathématiques. Dunod (2016)
- McKinney W. Analyse de données en Python, Manipulation de données avec pandas, NumPy et IPython. Eyrolles (2015)
- Chazallet. Python 3, Les fondamentaux du langage. Ressources informatiques (2014)
- Cormen et al. Algorithmique, Cours avec 957 exercices et 158 problèmes. Dunod (2010)
- Lutz et Ascher. Introduction to Python. O'Reilly (2000)

# L'informatique et le Langage Python 

## Pour les débutants

<center> Pour prendre le bon train </center>

- Monk. Programming the Raspberry Pi, Getting started with Python. Mc Graw Hill (2013)
- Eric Grimson, Introduction to Computer Science and Programming using Python, MITx:6.00.1x (2016)
- Nantais et Downey. Think Python How to Think Like a Computer Scientist, Version 1.1.20. Green Tea Press (2013)

# Informatique et Programmation: définition

- **informatique** = **informa**tion + automa**tique**

<center>  Objectifs </center>
- Les deux types de connaissance nécessaires pour résoudre des problèmes
- Quelles sont les étapes que l'ordinateur doit suivre pour **executer** une tâche ?
- Quelle est la syntaxe que doit suivre le **langage** pour transcrire nos idées en étapes mécaniques
 

# Algorithme : définition

- algorithme := suite finie et non ambiguë d'opérations élémentaires permettant de résoudre un problème
- opération élémentaire = **une instruction**
- **méthode de calcul pas à pas, que l'on peut automatiser avec une machine**
- le mot algorithme vient du nom du mathématicien perse Al-Khawarizmi ( 780 - 850 ), qui est également à l'origine du mot algèbre et de l'utilisation des chiffres arabes

  
# Algorithmes et ordinateurs

- les algorithmes ont existé avant les ordinateurs
- cependant certains algorithmes ne sont pas simples à appliquer/exécuter manuellement car
	- leur temps d'exécution est trop long pour une personne
	- la probabilité d'une erreur humaine est trop grande ( précision, répétition, ... )
- alors que les ordinateurs peuvent exécuter
	- très rapidement des instructions
	- de manière fiable
	- sans erreur

# L'ordinateur est une machine Logique :


|relation between expressions| meaning|
|----------|--------|
| (x) and (y)  | **SIMULTANEOUSLY** both True |
| not (x) | the negation of x is True |
| (x) or (y) | **INDEPENDENTELY**  True |


# Exemples

## "Computational Thinking"


## Plusieurs manières de faire Hello World!

~~~python
print('Hello world !')
~~~

~~~bash
echo 'Hello world !'
~~~

~~~{.c .numberLines startFrom="5"}
int main(int argc, char *argv[]) {
  cout << "Hello world ! \n" << endl;
  return 0;
} 
~~~

# Un problème de connaissance
pour résoudre un problème par le calcul, il faut des opérations fondamentales 

- Une  connaissance  des **déclarations** qui modélisent les aspects pertinents/essentiels du problème
- Une  connaissance  des  **méthodes systématiques**, les points sur lesquels il faut s'appuyer

# Premier exemple : somme des nombres (Problème)
On cherche à calculer la somme des nombres de 1 à n :  
$$
\sum_{k=1}^n k
$$


> - Que vaut la somme des nombres de 1 à 3 ?  
> - Que vaut la somme des nombres de 1 à 100 ? 

# Premier exemple : somme des nombres (Solution)

Au moins 3 manières de faire :

- commencer par les nombres les plus élevés  
- commencer par les nombres les plus petits
- appliquer la formule $\frac{n*(n+1)}{2}$


# Langages utilisés pour le cours

- Blocky : <https://code.google.com/p/blockly>
- Python : <https://docs.python.org/3/tutorial/>

# Blocky

- langage de programmation visuel
- intégré au navigateur web
- pour découvrir les notions de base de programmation

# Python

- créé par Guido van Rossum en 1989 ( première version écrite en une semaine )
- multi paradigmes : impératif, fonctionnel, objet
- à typage dynamique
- simple à apprendre
- très expressif : plus proche du cerveau que du processeur
- très populaire
- utilisé par de grandes entreprises : google, pinterest, dropbox, aldebaran pour la programmation de Nao, ...
- multi plateformes ( W$, MacOs X, iOS, linux, ... )

# Nous présenterons plusieurs algorithmes simples :

- Identification de Palindromes
- Calcul d'une racine carrée
- Détermination des années bissextiles

# Des citations...

Celle-ci est de [*Mitch Resnick*](https://en.wikipedia.org/wiki/Mitchel_Resnick).

> If you learn to read, you can then read to learn.\
> If you learn to code, you can then code to learn.
