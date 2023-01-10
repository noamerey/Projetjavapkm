## WEB API

![api](https://user-images.githubusercontent.com/95354215/211629189-f6bf9d55-7db5-4821-8208-7b828c3418d0.png)


Le but de Notre projet est de créer une api restfull avec node js
Nous avons donc choisi de créer une API qui est une sorte de mur de publication comme Twitter, sur lequel les utilisateurs peuvent poster des messages. Les utilisateurs peuvent s'enregistrer et ensuite se connecter. Les messages peuvent être liké et disliké. Chaque utilisateur pourra poster son propre message

## Pour commencer

Pour bien débuter le projet il vous voudras des bases en js et en back grace a des cours ou encore des formations a suivre sur des sites comme openclassroom

### Pré-requis

- Visual Studio : https://visualstudio.microsoft.com/fr/vs/whatsnew/
- Node js : https://nodejs.org/fr/download/
- postman : https://www.postman.com/downloads/
- mamp : https://www.mamp.info/en/downloads/
- terminal

### Installation

Pour les installation c'est super simple il vous faudra juste de telecharger tout les pré-requis cité plus haut et d'utiliser notre code sur visual studio

## Démarrage

Pour tester notre projet il faudra utiliser les fichiers fournis sur le gitub sur visual studio. Ils faudra lancé un serveur avec mamp et taper la commande sur un terminal nodemon server.js ensuite si tout est bon il faudra utiliser postman pour pouvoir tester notre api dans un premier temps il faut s'enregistrer sur l'application comme ceci: ![image](https://user-images.githubusercontent.com/95354215/211646672-6c673e8f-89e1-425f-9740-b9400b9466f2.png)
Ensuite il faudra vous connecter pour récuperer le token de l'utilisateur comme ceci:![image](https://user-images.githubusercontent.com/95354215/211647351-b14f3f5a-0e43-47d9-bb6b-972a7b6c11c3.png) une fois le token copié il faudra le collé avec un Bearer ici pour pouvoir envoyé un message ![image](https://user-images.githubusercontent.com/95354215/211648186-0d7a8c0d-59a0-45d2-99c3-84e0a3ae24db.png)
c'est ici(body) qu'on ecris le messages et le titre que l'on veut :![image](https://user-images.githubusercontent.com/95354215/211648436-dd9bf18a-a6a3-4e4b-9f22-d10d94d2f0e8.png)
Ensuite ici on récuperer les informations du l'utilisateur: ![image](https://user-images.githubusercontent.com/95354215/211652962-acc332a9-2213-4cc8-bf3b-f4b92ab5fefb.png)
ici on peux voir le mur de messages avec les userid=l'utilisateur id=le nombres du messages et le messages en question avec la possibilité de faire apparaitre autant de message qu'on veut ![image](https://user-images.githubusercontent.com/95354215/211653801-0253e02b-177f-4607-a58e-d0968c7c733e.png)
il y aussi une fonctionnalité qui est de pouvoir liké ou disliké. les likes et les dislikes vont apparaitre sur le mur  de publication. j'ai crée 3 autre users, 2 vont disliké et un va liké donc a chaque fois il faudra changer le token dans le bearer pour pouvoir liké sous le pseudo alexistest par exemple et en mettre l'id correspondant au messages: ![image](https://user-images.githubusercontent.com/95354215/211657403-8451e17c-4bdf-4a03-bf13-98a60f1048aa.png)
et le mur de plublication avec les likes et les dislikes:![image](https://user-images.githubusercontent.com/95354215/211657899-d24709a2-0ecc-4a40-9917-b7ba31ac5b16.png)





## Versions
 
**async :** 3.2.4  
**bcrypt :** 5.1.0  
**body-parser :** 1.20.1  
**express:** 4.18.2  
**git  :** 0.1.5  
**jsonwebtoken :** 9.0.0  
**mysql  :** 2.18.1  
**mysql2 :** 2.3.3  
**sequelize :** 6.28.0   
    

## Auteurs

* **Noa**   _alias_ [@noamerey](https://github.com/noamerey)
* **Alexis** _alias_ [@RainderAx](https://github.com/RainderAx)
* **Kenan** _alias_ [@Kenan932](https://github.com/Kenan932)



