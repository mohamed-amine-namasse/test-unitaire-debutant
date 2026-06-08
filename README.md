## On initialise le projet nodeJS

On initialise le projet nodeJS avec la commande npm init
![alt text](image-1.png)
![alt text](image-2.png)

## On installe jest

On installe jest avec la commande npm install --save-dev jest
![alt text](image-3.png)

## On configure le package.json

![alt text](image-4.png)

## On lance un test avec jest et on voit bien qu'il passe

![alt text](image-5.png)

## On modifie volantairement le code pour le faire échouer

![alt text](image-6.png)
![alt text](image-7.png)
Après avoir lancé npm test on obtient bien l'erreur
![alt text](image-8.png)

## On recorrige l'erreur et on voit que le test passe au vert

![alt text](image-9.png)
