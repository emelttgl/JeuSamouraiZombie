# Jeu Samourai pour le projet de Prog. Avancée

Devoir réalisé par Emel Tatoglu (https://github.com/emelttgl) et Oberhauser Clément (https://github.com/ClemWasChoosen)

## Compilation (tested on linux and windows, macos is yet to try)
```sh
git clone --recurse-submodules https://github.com/emelttgl/JeuSamouraiZombie.git &&
cd JeuSamouraiZombie &&
mkdir build &&
cd build &&
cmake .. &&
make &&
./JeuSamouraiZombie
```

Si make ne fonctionne pas, essayez
```sh
cmake --build . -j 
```
