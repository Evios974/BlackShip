# Blackship

Blackship est une bataille navale développée en C avec des fonctionnalités réseau.

Projet académique réalisé avec ❤️ par :
- [Evios17](https://github.com/Evios974/)
- [sklryb](https://github.com/sklryb)
- [ch2792](https://github.com/ch2792)

## 🛠 Compilation et installation

1. Clonez le dépôt :
```bash
git clone https://github.com/Evios974/BlackShip && cd Blackship
```

2. Compilez le projet :
```bash
cmake . && make
```

L'exécutable sera généré dans `executables/blackship`

## 🚀 Utilisation

### Mode interactif
Lancez simplement l'exécutable :
```
$ ./executables/blackship
╔══════════════════════════════════════════════════════════════╗
║                          BlackShip                           ║
╠══════════════════════════════════════════════════════════════╣
║ Description :                                                ║
║                                                              ║
║  - Bienvenue dans Blackship, une bataille navale solo et     ║
║    multijoueur jouable en ligne de commande                  ║
║                                                              ║
║  - Ce jeu a été crée en C, dans le cadre d'un projet         ║
║    d'étude universitaire                                     ║
╚══════════════════════════════════════════════════════════════╝

Sélectionnez votre mode de jeu :
[1] Lancez une partie solo
[2] Lancez une partie multijoueurs

➤  
```

### Options en ligne de commande
```
$ ./executables/blackship -h
Utilisation :
-o       -- Active le mode solo
-s       -- Active le mode serveur
-c       -- Active le mode client
-v       -- Affiche la version du programme
```