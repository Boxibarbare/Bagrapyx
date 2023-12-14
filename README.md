# Bagrapyx 🔪

Bagrapyx est un jeu inspiré de jeux Roblox (Bakon, Granny, Piggy), créé avec les bases de pytactx, un moteur de jeu développé pour aider à apprendre le développement par Jusdeliens.

## Contexte 🔎

Lors de nos cours de développement numérique, nous avons dû créer un jeu en utilisant PytactX de Jusdeliens. Le jeu est accompagné d'un ensemble de contraintes, comme l'uitlisation de n'importe quel moteur de jeu. Nous avons décidé d'obté pour un jeu de Hunter car les règles sont plutôt simples malgré quelques difficultés à mettre en place et ce type de jeu est apprécié
 par tous les joueurs.

## Règles 📜

### Composants du jeu 

<img width="236" alt="monstre" src="https://github.com/Boxibarbare/Bagrapyx/assets/151009711/6aa232a3-d014-400a-a2cc-683662271ed9">


Dans ce point de vue de l'arène, vous pouvez voir les différents composants de Bagrapyx:

- 🔵: équipe 1 -> Monstres
- 🟢: équipe 2 -> Survivants
- 🟥: porte de sortie
- 🔹: parcours / pièges
- 🟣: stun
- 🗝️: clés à obtenir

### Comment jouer 

Il y a 2 équipes. La première, les joueurs sont des survivants, ils doivent obtenir une somme de clés définie et doivent les ramener dans la porte. Malgrès tout, ils ont une contrainte qui consiste à avoir qu'une clé en main. 
La deuxième équipe, les joueurs sont des monstres, ils doivent capturer tous les survivants en les touchant. Tout comme les survivants, ils ont une contrainte. Cette contrainte consiste, pour les survivants, à utiliser une orb pour paralyser tous les monstres de la ma pendant 3s, les survivants doivent passer sur les orbs pour les activer. De plus il se déplace plus lentement que les survivants.

### Fin du jeu 

Il y a 2 fin. La première, quand toutes les clés sont posées dans la porte par les survivants, la porte s'ouvre et les survivants peuvent sortir. La deuxième, les monstres ont capturé tout les survivants pour que la partie s'arrête.


## Uses Cases 

### Admin

### Player

Les Monstres (🔵) :
- Mettre 3 pièges (quand ils le voudront) qui immobiliseront le joueur qui marche dessus pendant 5sec.
- Bouges plus lentement que les survivants 🟢
- Ne peuvent pas tirer, uniquement toucher (collision)
- Ne peuvent pas respawn


Les Surviants (🟢) :
- Ne peuvent que prendre une clé par personne
- Peuvent récupérer des orbs
- Ne peuvent pas respawn
- Bouges plus rapidement que les monstres 🔵
- Ne peuvent pas faire des dégâts

## Architecture matérielle 📐✏️

SOON

## Pre-requisites ☑

- Python 3.12 or higher
- An arena in Pytactx

## Installation 🔧

(Installation of necesary packages automatically occur when an agent is created.)

## Test 🧪

SOON

## Author

PytactX : Julien Arné

Bagrapyx : Cédric / Marin

## Licence

SOON








