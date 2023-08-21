# Jeu du Morpion (Tic-Tac-Toe) en React

Ce projet est une implémentation du jeu du Morpion (Tic-Tac-Toe) en utilisant React. Il permet aux joueurs de s'affronter en alternant entre "X" et "O", et le jeu détecte automatiquement le gagnant ou le match nul.

## Fonctionnalités

Deux joueurs peuvent s'affronter : "X" et "O".
Les joueurs alternent automatiquement à chaque coup.
Le jeu détecte automatiquement le gagnant ou le match nul.
Les scores de chaque joueur sont suivis et affichés.
## Comment jouer

Clonez ce dépôt sur votre ordinateur :

git clone https://github.com/votre-utilisateur/nom-du-repo.git
Accédez au répertoire du projet :

cd nom-du-repo
Installez les dépendances nécessaires :

npm install
Lancez l'application :

npm start
Ouvrez votre navigateur et accédez à http://localhost:3000 pour jouer au jeu du Morpion.

## Structure du projet

java
Copy code
nom-du-repo/
├── src/
│   ├── components/
│   │   ├── Board.js
│   │   ├── Box.js
│   │   ├── ResetButton.js
│   │   ├── Scoreboard.js
│   ├── App.js
│   ├── index.js
├── public/
│   ├── index.html
├── README.md
├── package.json
└── .gitignore
Le dossier src/components contient les composants réutilisables pour le jeu.
App.js est le composant principal qui assemble les différents composants pour créer le jeu.
public/index.html est le point d'entrée de l'application.
README.md contient des informations sur le projet et ses fonctionnalités.
package.json contient les dépendances et les scripts du projet.
## Personnalisation
Si vous souhaitez personnaliser ce jeu, vous pouvez modifier le style CSS, ajuster les règles du jeu ou ajouter de nouvelles fonctionnalités selon vos besoins.

## Auteur
Florent Nkita