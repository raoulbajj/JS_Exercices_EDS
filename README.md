# Exercices JavaScript pour Débutants

Bienvenue dans cette série d'exercices conçus pour vous aider à vous familiariser avec les bases de la programmation JavaScript. Chaque exercice vise à renforcer une compétence spécifique en JavaScript.

**CHAT GPT INTERDIT**  
**EXERCICES NON NOTÉS, C'EST POUR PROGRESSER EN JAVASCRIPT, VOUS FAÎTES ÇA POUR VOUS.**

## Instructions Générales

### Création et Utilisation des Branches Git

Avant de commencer les exercices, chaque élève doit créer sa propre branche de travail :

1. Ouvrez votre terminal ou invite de commandes.
2. Naviguez jusqu'au répertoire du projet Git.
3. Créez votre branche personnelle en exécutant `git checkout -b [nom_de_votre_branche]`. Remplacez `[nom_de_votre_branche]` par votre nom, par exemple `jean_dupont`.
4. Travaillez sur cette branche pour tous les exercices. N'oubliez pas de faire régulièrement des commits de vos progrès.

### Travail sur les Exercices

Dans votre branche, travaillez sur les exercices fournis. Attention : ne poussez jamais votre code directement dans la branche principale (main). Une fois que vous avez terminé les exercices, poussez votre code sur votre branche et créez une demande de fusion pour la revue de code.

## Exercice 1 : Conversion de Températures

### Description

Créez un programme qui convertit les degrés Celsius en degrés Fahrenheit et inversement. Vous devrez demander à l'utilisateur de saisir la température et le type de conversion (de Celsius à Fahrenheit ou vice versa).

### Indice

Utilisez la fonction `prompt()` pour collecter la saisie de l'utilisateur et `console.log` pour afficher le résultat.

## Exercice 2 : Calculateur de Somme

### Description

Écrivez une fonction qui prend deux nombres en arguments et retourne leur somme. Testez votre fonction avec différents ensembles de nombres.

### Indice

Déclarez une fonction en utilisant `function` et utilisez l'opérateur `+` pour additionner les nombres.

## Exercice 3 : Vérificateur d'Âge

### Description

Demandez l'âge de l'utilisateur et affichez s'il est majeur ou mineur. Considérez l'âge de la majorité comme 18 ans.

### Indice

Utilisez `prompt()` pour obtenir l'âge de l'utilisateur et les instructions `if/else` pour la logique conditionnelle.

## Exercice 4 : Compteur de Boucles

### Description

Utilisez une boucle pour afficher les nombres de 1 à 10 dans la console.

### Indice

Exploitez la boucle `for` ou `while` pour répéter les instructions.

## Exercice 5 : Générateur de Nombres Aléatoires

### Description

Écrivez un programme qui génère un nombre aléatoire entre 1 et 100, puis demandez à l'utilisateur de deviner le nombre. Indiquez si leur supposition est trop haute, trop basse, ou correcte.

### Indice

Utilisez `Math.random()` pour générer un nombre aléatoire et `prompt()` pour la saisie de l'utilisateur.

## Exercice 6 : Fetch et Affichage de Données avec Framework et Vite

### Description

Utilisez un framework JavaScript de votre choix (comme React, Vue, Svelte, etc., disponibles via Vite) pour créer une application web. Dans cette application, faites une requête fetch vers une API publique (par exemple, une API de blagues, de météo, etc.) et affichez les données récupérées.

### Instructions

Créez un nouveau projet avec Vite en sélectionnant le framework de votre choix.
Dans votre application, écrivez une fonction asynchrone qui utilise fetch pour récupérer des données depuis une API.
Utilisez `async/await` pour gérer les promesses.

### Indice

Utilisez la syntaxe `await` devant votre appel `fetch` pour attendre la réponse, puis traitez la réponse en utilisant `await`.

## Exercice 7 : Affichage de Cartes avec Données en Utilisant un Framework et Vite

### Description

En reprenant votre application de l'exercice 6, affichez les données récupérées sous forme de cartes HTML. Chaque objet de données doit être affiché dans sa propre carte. Assurez-vous que votre application est responsive et bien structurée.

### Instructions

Utilisez les composants de votre framework pour créer des "cartes" qui afficheront les données.
L'affichage doit être responsive pour la version mobile au plus petit (300px de largeur).

### Indice

Dans le framework que vous avez choisi, utilisez une méthode de rendu dynamique pour itérer chaque élément que vous allez afficher, comme `.map` en React, pour passer sur chaque objet de données et retourner un composant ou un élément HTML pour chaque objet.

## Exercice 8 : Affichage des Saisies de Formulaire

### Description

Créez un formulaire HTML simple avec des champs pour le nom d'utilisateur, l'adresse e-mail, et un mot de passe. Après la soumission du formulaire, utilisez JavaScript pour afficher les saisies de l'utilisateur dans une alerte.

### Instructions

Créez un formulaire HTML avec trois champs : nom d'utilisateur, adresse e-mail et mot de passe.
Ajoutez un bouton de soumission à votre formulaire.
Écrivez un script JavaScript qui intercepte la soumission du formulaire et affiche les données saisies dans une alerte.

### Indice

Utilisez l'événement `onsubmit` sur le formulaire pour intercepter la soumission. Récupérez les valeurs des champs de saisie et utilisez `alert()` pour les afficher. N'oubliez pas d'utiliser `e.preventDefault()` pour empêcher la soumission réelle du formulaire.

## Exercice 9 : Manipulation du DOM

### Description

Créez une page Web avec quelques éléments HTML (par exemple, des paragraphes, des images, des boutons). Utilisez JavaScript pour modifier ces éléments de manière dynamique (par exemple, changer le texte, déplacer des images, changer la couleur des boutons, etc.).

### Indice

Utilisez les méthodes du DOM comme `getElementById()` ou `querySelector()` pour sélectionner des éléments et les modifier.

## Exercice 10 : Gestionnaire d'Événements

### Description

Ajoutez des gestionnaires d'événements à votre page Web (de l'exercice 9). Par exemple, changez le contenu d'un paragraphe lorsque l'utilisateur survole une image, ou affichez une alerte lorsque l'utilisateur clique sur un bouton.

### Indice

Utilisez `addEventListener()` pour attacher des événements aux éléments du DOM.
