### Sujet:
Faites un programme qui génère une grille comme dans l'exercice 2 et qui applique 1 tour du jeu de la vie de Conway à cette grille.

Règles du jeu de la vie Conway:
- Une case est voisines à une autre si elle lui est directement adjacente, les diagonales comptes
- Une case avec 3 voisines remplies devient ou reste remplie
- Une case remplie avec 2 voisines remplies reste remplie
- Toutes les autres cases deviennent ou restes vides

exemple:
```shell
./ex3 5 10 40
0    000 0
   00 0  0
  00     0
00 0 0    
 00  0 00 
00  0  000
  00  0 00
0000  000 
  0  0  0 
   0 0 0 0
----------
      0   
   0 0   0
   0      
 0        
00     00 
 00    0 0
 000    00
 0 0  000 
   0   0  
        0 
```


### Indice
Vous ne pouvez pas modifier la grille que vous lisez.

https://bitstorm.org/gameoflife/
