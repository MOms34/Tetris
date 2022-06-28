# Tetris

Le projet est une reconsitution du jeu mythique Tetris. En effet, grâce à la librairie N-Curses, nous avons dû reproduire ce jeu.

## But du programme

Le but de ce projet est de recréer le jeu Tetris dans un terminal UNIX, avec les règles de la version Gameboy, Vous devez utiliser ncurses. Dans le dossier de votre binaire, il doit y avoir un répertoire tetriminos qui contient les fichiers qui décrivent les pièces du jeu.

## Fonctions autorisées

```

	rand, srand, getopt, getopt_long, clock,
	
```

## Mise en route

Ces instructions vous permettront d'obtenir une copie du projet opérationnel sur votre machine locale à des fins de développement et de test.

### Pré-requis

De quoi avez-vous besoin pour installer le logiciel et comment l'installer ?

```

gcc
make

```

### Installation

Compilation du projet

```
make
```

Lancement du projet

```
Usage:

./tetris --help | cat -e

Usage: ./tetris [options]$

Options:$

--help

Display this help$

-L --level={num}

Start Tetris at level num (def: 1)$

-l --key-left={K}

Move the tetrimino LEFT using the K key (def: left arrow)$

-r --key-right={K}

Move the tetrimino RIGHT using the K key (def: right arrow)$

-t --key-turn={K}

TURN the tetrimino clockwise 90d using the K key (def: top

arrow)$

-d --key-drop={K}

DROP the tetrimino using the K key (def: down arrow)$

-q --key-quit={K}

QUIT the game using the K key (def: ‘q’ key)$

-p --key-pause={K}

PAUSE/RESTART the game using the K key (def: space bar)$

--map-size={row,col} Set the numbers of rows and columns of the map (def: 20,10)$

-w --without-next

Hide next tetrimino (def: false)$

-D --debug

Debug mode (def: false)$
```






